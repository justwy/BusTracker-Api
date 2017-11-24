## Swagger Codgen
The service API is managed using swagger tools.

All swagger related files are in configuration/api folder.

To generate a android retrofit2 client: (`assume swagger-codegen cli is installed on dev machine`)
`swagger-codegen generate -i swagger.yaml -o client -l java -c retrofit-client-config.json`
