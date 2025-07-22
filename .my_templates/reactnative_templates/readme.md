## Use this files with the folow "layer templates" in config params:

```
"scaffolding.layers.templates": [
    "{{root_folder}}/app/{{feature_name}}/_layout.template",
    "{{root_folder}}/app/{{feature_name}}/index.template",
    // "{{root_folder}}/app/{{feature_name}}/domain/usecases/{{usecase_name.snakeCase}}_usecase.template",
    // "{{root_folder}}/app/{{feature_name}}/domain/repositories/{{usecase_name.snakeCase}}_repository.template",
    "{{root_folder}}/app/{{feature_name}}/domain/usecases/",
    "{{root_folder}}/app/{{feature_name}}/domain/repositories/",
    "{{root_folder}}/app/{{feature_name}}/domain/errors/",
    "{{root_folder}}/app/{{feature_name}}/domain/entities/",
    "{{root_folder}}/app/{{feature_name}}/infrastructure/datasources/",
    "{{root_folder}}/app/{{feature_name}}/infrastructure/repositories/",
    // "{{root_folder}}/app/{{feature_name}}/infrastructure/repositories/{{usecase_name.snakeCase}}_repository_impl.template",
    // "{{root_folder}}/app/{{feature_name}}/infrastructure/datasources/{{usecase_name.snakeCase}}_datasource.template",
    "{{root_folder}}/app/{{feature_name}}/data/models/",
    "{{root_folder}}/app/{{feature_name}}/data/datasources/",
    // "{{root_folder}}/app/{{feature_name}}/data/datasources/{{usecase_name.snakeCase}}_datasource_impl.template",
    "{{root_folder}}/app/{{feature_name}}/presentation/pages/",
    "{{root_folder}}/app/{{feature_name}}/presentation/pages/{{feature_name.snakeCase}}_screen.template",
    "{{root_folder}}/app/{{feature_name}}/presentation/components/",
    "{{root_folder}}/app/{{feature_name}}/presentation/hooks/",
  ]
```
