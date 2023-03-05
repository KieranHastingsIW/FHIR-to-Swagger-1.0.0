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
1. Execute the following command to generate the swagger definition for `Patient` resource. This will generate the swagger definition inside the generated-def folder

    ```shell
    fhir-to-swagger Patient --output ./generated-def
    ```
