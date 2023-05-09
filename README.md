# DW10 - Dart Week 10

## Backend
Backend desenvolvido usando json_rest_server, ferramenta desenvolvida pela academina do flutter para criar backends de testes de forma fácil e rápida.

https://pub.dev/packages/json_rest_server

### Instalando o backend

Acesse a pasta `/dw10_delivery_api` e execute o comando
`````
dart pub global activate json_rest_server
`````
para fazer a instalação.

### Executando o backend
Acesse a pasta `/dw10_delivery_api` e execute o comando 
`````
json_rest_server run
`````

## Frontend
Imagens do figma estão na pasta `documentation/figma`


## Criando projeto Flutter
```
flutter create --project-name delivery_backoffice_dw10 --org br.dev.giovanitrevisol --platforms web ./delivery_backoffice_dw10
```

### configs iniciais

-> No arquivo `analysis_options` incluir após `include:...`
````
analyzer:
  exclude:
    - "**/*.g.dart"
````
e em `rules:`
````
  rules:
    avoid_web_libraries_in_flutter: false
    prefer_relative_imports: true
    prefer_single_quotes: true
    unnecessary_await_in_return: true
    prefer_final_locals: true
    prefer_final_fields: true
    avoid_unused_constructor_parameters: true
    always_declare_return_types: true
    require_trailing_commas: true
````
 
### MobX
https://mobx.netlify.app/getting-started/
````
flutter pub run build_runner watch --delete-conflicting-outputs
````

