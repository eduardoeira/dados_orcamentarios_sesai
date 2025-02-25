# Projeto de Análise de Dados Orçamentários

Este projeto tem como objetivo realizar a análise e visualização dos dados orçamentários da Secretaria de Saúde Indígena (SESAI). Utilizando Python, foram realizados tratamentos nos dados e criadas planilhas para diferentes finalidades de análise.

## Estrutura do Projeto

- **/src**: Contém os scripts em Python:
  - `criar_planilha_power_bi.py`: Script para gerar a planilha que será utilizada no Power BI.
  - `criar_tabela_dinamica.py`: Script para criar uma planilha em Excel com uma tabela dinâmica para análise rápida dos dados.

- **/dicionarios**: Pasta contendo os dicionários utilizados para tratar os dados.

- **README.md**: Este arquivo com informações sobre o projeto.

## Tecnologias Utilizadas

- **Python**: Para processamento e tratamento de dados.
- **Pandas**: Biblioteca para manipulação de dados em Python.
- **win32com**: Biblioteca para automação do Excel.

## Como Executar

1. Clone este repositório em sua máquina:
   ```bash
   git clone https://github.com/seu_usuario/nome_do_repositorio.git
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd nome_do_repositorio
   ```

3. Certifique-se de ter as bibliotecas necessárias instaladas:
   ```bash
   pip install pandas pywin32
   ```

4. Execute os scripts em Python encontrados na pasta `/src`:
   - Para criar a planilha utilizada no Power BI:
     ```bash
     python src/criar_planilha_power_bi.py
     ```
   - Para criar a planilha em Excel com a tabela dinâmica:
     ```bash
     python src/criar_tabela_dinamica.py
     ```

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença

Este projeto está licenciado sob a MIT License. Veja o arquivo LICENSE para mais detalhes.
