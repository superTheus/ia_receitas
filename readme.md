## Pré-requisitos

Antes de executar o script, certifique-se de ter os seguintes itens instalados:

- Python 3.x

## Instalação

1. Clone este repositório para o seu ambiente local:
    ```sh
    git clone https://github.com/superTheus/ia_receitas.git
    cd ia_receitas
    ```

2. Execute o bash de inicialização do ambiente no powershell:
    ```sh
    init.ps1
    ```
Este é um script que inicia o ambiente python e instala a dependência necessárias

## Env

Para usar em ambiente local é necessário criar o arquivo ```.env```, e colocar as keys necessárias

```sh
GEMINI_API_KEY=SUA_CHAVE
AMB=dev
```

A KEY ```AMB``` precisa ter o valor ```dev``` para indicar que está usando o em ambiente local de desenvolvimento

## Executar

Use o comando:

```sh
streamlit run .\app.py
```

Isso irá iniciar um servidor local que dará acesso a interface streamlit