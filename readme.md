# Sistema de Gestão para Medicina do Trabalho

Este é um sistema full-stack para gestão de saúde ocupacional, desenvolvido inteiramente com Python e o framework Django. O projeto nasceu da necessidade de uma clínica de medicina do trabalho de substituir uma complexa planilha Excel que funcionava como um banco de dados, relacionando diversas funções de trabalho aos seus respectivos códigos CBO (Classificação Brasileira de Ocupações), exames médicos exigidos entre outros detalhes.

O sistema foi projetado para ser utilizado simultaneamente por 5 a 15 médicos, está hospedado na plataforma PythonAnywhere e já se encontra em pleno funcionamento, atendendo às demandas da clínica.
Tecnologias Utilizadas

O projeto foi construído utilizando as seguintes tecnologias:

* **Python**: Linguagem principal do backend.

* **Django**: Framework utilizado para toda a estrutura do projeto, desde a lógica de negócios até a renderização do frontend.

* **HTML & CSS** (Bootstrap): Estrutura e estilo das páginas.

* **Django Templates**: O frontend foi totalmente integrado ao backend através do sistema de templates do Django.

* **API do Google Gemini**: O projeto foi conectado com a API do Google Gemini, como um primeiro passo na exploração de funcionalidades de Inteligência Artificial.

* **Hospedagem**: PythonAnywhere.

* **Desenvolvimento**: Durante a etapa de desenvolvimento foi utilizador Docker para virtualizar um banco de dados Postgresql.

## Desafios e Aprendizados

Este projeto representou uma jornada de imenso aprendizado, especialmente por ter sido meu primeiro grande sistema desenvolvido de forma autônoma e sem experiência prévia em empresas de tecnologia.
Desafios Técnicos

Algumas das partes mais desafiadoras da lógica do código incluíram:

* Migração da Lógica do Excel para o Banco de Dados: Traduzir a estrutura e as regras de negócio contidas na planilha para um modelo de dados relacional e robusto com o Django ORM.

* Gerenciamento de Acessos Concorrentes: Garantir que o sistema suportasse o uso simultâneo por vários médicos sem conflitos de dados ou perda de performance.

* Manipulação de Dados e Relatórios: Desenvolver consultas eficientes para registrar atendimentos e extrair relatórios e históricos.

* Integração com IA: Dar os primeiros passos com Inteligência Artificial, conectando o sistema à API do Google Gemini para explorar novas possibilidades.

## A Jornada de um Desenvolvedor Iniciante

Encarar um projeto completo sozinho, sendo iniciante em programação, foi o maior desafio de todos. Exigiu não apenas o aprendizado de novas tecnologias, mas também disciplina, resiliência e uma grande capacidade de resolver problemas de forma independente. Cada funcionalidade implementada e cada bug corrigido representaram uma pequena vitória e um passo importante na minha transição de carreira.
A Conexão entre Administração e Tecnologia

Minha formação em Administração de Empresas (**CRA-CE 20-89246**) foi um diferencial crucial para o sucesso deste projeto. Longe de ser um obstáculo, ela me proporcionou as ferramentas necessárias para:

* Levantamento de Requisitos: Conduzir reuniões com o cliente para entender profundamente suas dores e necessidades, traduzindo requisitos de negócio em especificações técnicas claras.

* Visão Sistêmica: Analisar os processos do cliente e desenhar um sistema que não apenas funciona, mas que otimiza e organiza o fluxo de trabalho existente, que antes era manual.

* Gestão do Projeto: Organizar o desenvolvimento em etapas, definir prioridades e garantir que o produto final estivesse perfeitamente alinhado com as expectativas e os objetivos estratégicos do cliente.

Este projeto é a prova de que a combinação de habilidades de gestão com conhecimento técnico pode gerar soluções muito mais eficazes e que realmente agregam valor ao negócio.

Obs.: Por motivos contratuais e de segurança o código fonte não pode ser exibido em sua totalidade. 