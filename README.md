# FHIR to Swagger

A command line tool to convert FHIR R4 (4.0 Schema) with partial NZ Base IG to Swagger definitions.

[:construction: Work-In-Progress (Part-Timed) & Feature Requests are Welcomed]

## Build, Install & Run

### Build & Install

Clone or download the project and execute the following command (from the root directory) to install relevant dependencies

> Use NodeJS `11.14.0v` for error free instalation and execution

```shell
npm install
```

### Run

Execute the following command (from the root Directory) to link the tool with shell

```shell
npm link
```

and use the following command pattern to execute the tool

```shell
fhir-to-swagger [Resource_Name] [--combine] --output [Output_Directory]
```

for example:

1. Execute the following command to generate the swagger definition for `Coverage` resource. This will generate the swagger definition inside the current working directory

    ```shell
    fhir-to-swagger Patient --output ./generated-def
    ```
