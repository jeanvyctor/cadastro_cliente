# Sistema de Cadastro de Clientes

Este é um sistema simples desenvolvido em Python com interface gráfica usando Tkinter para cadastrar clientes, armazenar os dados localmente em um arquivo JSON e gerar relatórios em Excel.

## Funcionalidades

- Cadastro de clientes com campos como nome, telefone, data de nascimento, email e endereço completo.
- Busca automática de endereço via CEP usando a API do ViaCEP.
- Validação básica dos dados (formato do CEP, telefone e data).
- Geração de relatório Excel com os dados cadastrados.
- Limpeza dos dados armazenados.
- Interface amigável e navegação facilitada pelo teclado.

## Como baixar e usar o programa

O arquivo executável do programa está disponível para download no Google Drive:

[Download do cadastro_clientes.exe](https://drive.google.com/file/d/1kL7g18QYtM4gW9xt_DnRUacOtu7yfnia/view?usp=drive_link)

### Instruções para executar

1. Baixe o arquivo `cadastro_clientes.exe` pelo link acima.
2. Execute o arquivo em um computador com Windows (compatível com sua versão do Windows).
3. A interface será aberta para que você possa começar a cadastrar clientes.
4. Para gerar relatórios, use o botão correspondente e salve o arquivo Excel no local desejado.
5. Os dados são salvos localmente em `clientes.json` na mesma pasta do executável.



---

## Requisitos para rodar o código-fonte

- Python 3.x
- Bibliotecas: tkinter, pandas, requests, openpyxl (para exportar Excel)

Você pode instalar as bibliotecas necessárias com:

```bash
pip install pandas requests openpyxl
