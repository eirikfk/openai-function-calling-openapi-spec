# Function calling using Azure OpenAI and an OpenAPI spec

Based on the following tutorial: https://cookbook.openai.com/examples/function_calling_with_an_openapi_spec

OpenAPI specification is extracted from the Swagger sample server: https://petstore.swagger.io/, and the solution uses the endpoints exposed here.

## Prerequisite
1. Create a `.env` file in the root-folder
2. Populate the `.env` file as shown in `.env-example` with the Azure OpenAI API-key and URL

## Plug-and-play
Recommend running this in the VsCode Devcontainer provided as it will then be plug-and-play, just remember to set the Python Interpreter in VsCode to the Poetry environment created.