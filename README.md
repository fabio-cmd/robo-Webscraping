# Robô de Verificação de Domínios usando Python e Selenium

Este é um script Python que utiliza a biblioteca Selenium para automatizar a busca pela disponibilidade de nomes de domínio no site Registro.br

## Requisitos

Antes de executar o script, certifique-se de ter instalado em seu computador:

 - Python 3.x
 - Biblioteca Selenium
 - Google Chrome
 - Arquivo executável do ChromeDriver (o link para download pode ser encontrado em https://chromedriver.chromium.org/downloads)
 
 ## Como utilizar
 
1. Abra o terminal ou prompt de comando em seu computador.
2. Clone este repositório em sua máquina:

```git clone https://github.com/fabio-cmd/robo-Webscraping.git```

3. Navegue até a pasta do repositório:
```cd robo-Webscraping```

4. Insira os nomes de domínio que você deseja pesquisar na coluna A de um arquivo Excel e salve-o na pasta do projeto.
5. Execute o script através do comando:

```python3 domain_checker.py```

6. O resultado da busca será armazenado no arquivo "resultado.txt".

## Observações

- Este script é a solução ideal para automatizar tarefas repetitivas, como a verificação da disponibilidade de domínios na web. Além de ser fácil de usar e configurar, ele pode ser facilmente integrado em fluxos de trabalho automatizados, reduzindo o tempo e o esforço necessários para executar essas tarefas manualmente. No entanto, recomendamos que você teste cuidadosamente o script em um ambiente de desenvolvimento antes de usá-lo em um ambiente de produção para garantir que ele atenda às suas necessidades específicas. Com a flexibilidade e a eficiência que esse script oferece, você poderá se concentrar em outras tarefas importantes do seu projeto!
- Certifique-se de que o arquivo executável do ChromeDriver esteja atualizado na pasta do projeto antes de executar o script.
- Caso deseje fazer alterações no código, sugerimos utilizar um ambiente virtual para instalar as dependências.

## Licença

Este projeto é distribuído sob a licença MIT. Veja o arquivo LICENSE.md para mais informações.

## Autor
Este script foi desenvolvido por Fábio Diniz. Fique à vontade para entrar em contato em caso de dúvidas ou sugestões.
