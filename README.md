## Como adicionar os Botões da SOHTEC em seu Site.

Veja abaixo os passos necessários para inserir os botões da SOHTEC em seu site, e utilizar todos os recursos da nossa plataforma.

### 1º - Adicionar Biblioteca

Inserir entre as tags **HEAD** do site a chamada para o script da biblioteca da SOHTEC

Exemplo:
```html {.line-numbers}
<script src="https://sohtec.com.br/services/Scripts/ClientProd.js" type="text/javascript"></script>
```

### 1º - Adicionar Botão (Agende sua Visita e Alugue Online)

Adicione o código abaixo no lugar onde você deseja que o botão seja mostrado.
No lugar das variáveis substitua com os dados do imóvel que desejar. 

Obs: O **ID_DA_SUA_EMPRESA** é fornecido pela SOHTEC no momento do contrato.

Exemplo:
```html {.line-numbers}
<script type="text/javascript">
    SOH.Exec({
        "buttonColorBg": "blue",
        "clienteId": "ID_DA_SUA_EMPRESA",
        "imovelId": "",
        "imovelUrl": "",
        "imovelEndereco": "",
        "imovelNumero": "",
        "imovelComplemento": "",
        "imovelBairro": "",
        "imovelCidade": "",
        "imovelEstado": "",
        "imovelDormitorios": "",
        "imovelVagas": "",
        "imovelCep": "00000-000",
        "imovelAluguel": "",
        "imovelCondominio": "",
        "imovelIptu": "",
        "visitaAcompanhada": "false",
    });
</script>
```
