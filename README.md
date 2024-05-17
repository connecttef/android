# Gerenciador de dependências

### Configure as variáveis de ambiente no seu sistema:
    - `CONNECTTEF_USERNAME`
    - `CONNECTTEF_TOKEN`

Para aplicar o gerenciador de dependências em seu projeto, siga os passos abaixo:

1. Ao final do arquivo `settings.gradle` do projeto, adicione o seguinte trecho de código:

```groovy
apply from: 'https://raw.githubusercontent.com/connecttef/android/main/settings.gradle'
```

2. Ao final do arquivo `build.gradle` do projeto, adicione o seguinte trecho de código:

```groovy
apply from: 'https://raw.githubusercontent.com/connecttef/android/main/dependencies.gradle'
```
