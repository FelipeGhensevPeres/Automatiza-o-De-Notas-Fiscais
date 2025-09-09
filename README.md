# Automatizacao de Notas Fiscais
Automação em Python com selenium, para preenchimento automático de formulários de emissão de notas fiscais a partir de uma planilha Excel.

Este projeto é uma automação desenvolvida em Python utilizando as libs (Selenium e Pandas).
O sistema faz login em uma página simples em HTML, lê os dados de clientes e produtos a partir de um arquivo Excel (NotasEmitir.xlsx) e preenche automaticamente todos os campos do formulário de emissão de notas fiscais sendo: nome, endereço, CPF/CNPJ, inscrição estadual, descrição, quantidade e valores.
Após o preenchimento, a automação conclui o processo clicando em um botão de envio para gerar a nota fiscal e fazer download.

Oque eu utilizei: Python
                  OS
                  Time.sleep
                  Selenium WebDriver
                  Pandas
                  WebDriver Manager (pra gerenciar o ChromeDriver)

Funcionalidades: Login automatico em página HTML.
                 Leitura e tratamento de dados de clientes a partir de uma planilha Excel.
                 Preenchimento automático do formulário das notas fiscais.
                 Emissão de múltiplas notas de forma rápida.
