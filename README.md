# DIO-Dashboard-de-Vendas

Desafio da plataforma DIO para desenvolver um Dashboard de Vendas de assinaturas do Xbox Game Pass.

## Descrição

Este projeto tem como objetivo desenvolver um Dashboard de Vendas de assinaturas do Xbox Game Pass, seguindo as diretrizes propostas pela plataforma DIO. O desafio é baseado na orientação do especialista Felipe Aguiar, com a implementação de soluções para requisitos específicos do Excel.

## Requisitos do Projeto

* Big Numbers de EA Play Season Pass e Microsoft Season Pass;
* Filtro de segmentação de dados sobre os períodos de assinaturas;
* Gráfico dinâmico com o Total de assinaturas do XBOX Game Pass, sendo auto-renovadas ou não.

## Passos para Criar e Estruturar o Dashboard no Excel

1. **Baixar o Arquivo**  
   Certifique-se de ter o arquivo Excel contendo a base de dados e o dashboard.

2. **Abrir no Microsoft Excel**  
   O dashboard foi desenvolvido utilizando funcionalidades do Excel, como tabelas dinâmicas e segmentações de dados.

3. **Organizar as Abas**  
   Crie as seguintes abas para estruturar o arquivo de forma clara e eficiente:
   - **Assets**: Armazena os elementos visuais, como ícones, logotipos e paletas de cores.
   - **Bases**: Contém a base de dados que alimenta o dashboard.
   - **Cálculos**: Exibe as perguntas de negócio e suas respostas, que são obtidas a partir das tabelas dinâmicas.
   - **Dashboard**: Apresenta as visualizações e métricas para análise.

4. **Criar os Cards**  
   Os "Big Numbers" devem ser extraídos da aba **Cálculos**, com base nos valores de **Grand Total** das tabelas dinâmicas.
   - **Card 1**: Utilize o **Subscription Type** como filtro, **Plan** como linhas e **EA Play Season Pass** como valor.
   - **Card 2**: Exiba o valor de **Microsoft Season Pass Price**.

5. **Criar o Gráfico Dinâmico**  
   O gráfico deve ser derivado de uma tabela dinâmica, utilizando os seguintes campos:
   - **Subscription Type** como filtro.
   - **Auto Renewal** como linhas.
   - **Total Value** como valores (configurado para soma).

6. **Adicionar Filtros**  
   Insira filtros interativos para que o usuário possa alternar entre diferentes períodos e visualizar métricas específicas.

7. **Utilize segmentações de dados** associadas às tabelas dinâmicas **tbl_annual_total** e **tbl_easeasonpass_total**.

8. **Definir o Layout**  
   - Coloque os elementos visuais da aba **Assets** diretamente no **Dashboard**.
   - Ajuste o layout, redimensionando as células, para garantir uma apresentação clara e intuitiva, permitindo que o usuário entenda facilmente as métricas.
   - Considere o estilo e a experiência do usuário ao projetar o painel, levando em conta os serviços e plataformas com os quais ele já está familiarizado.

9. **Finalização**  
   Oculte as outras abas, garantindo que o usuário tenha acesso apenas ao que é essencial para ele e **Salve o arquivo**!

## Tecnologias

* Microsoft Excel
* Business Intelligence

## Autor da Orientação

Felipe Aguiar (DIO)

## Licença

Este projeto é de livre utilização para fins educacionais.
