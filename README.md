# Sistema de Gestão Sustentável para Emissões de Equipamentos


## **Visão Geral**

O *Sistema de Gestão de Emissão de Carbono de Equipamentos* é uma solução inovadora, inicialmente desenvolvida para empresas que desejam ter controle sobre as emissões de dióxido de carbono de seus equipamentos pesados, com foco inicial em mineiradoras. Este projeto, desenvolvido em Node.js com o framework Express e utilizando MySQL como banco de dados, foi concebido durante o Hack Faesa 12.0, sendo elaborado em um período de 28 horas como um protótipo inicial para apresentação. O sistema oferece uma abordagem eficiente para monitorar e analisar as emissões, promovendo práticas sustentáveis e transparência operacional.

## **Tecnologias Utilizadas**

- **Linguagem:** Node.js (JavaScript)
- **Banco de Dados:** MySQL
- **Framework:** Express.js
- **Bibliotecas:** `body-parser`, `MySQL2` (Conexão com o Banco de Dados)

## **Estrutura do Projeto**

O projeto é organizado de maneira modular para facilitar a manutenção e escalabilidade. Principais componentes incluem:

- **Rotas:** Definem endpoints para operações CRUD em equipamentos e categorias.
  
- **Conexão com o Banco de Dados:** Estabelecida por meio da biblioteca MySQL2, com informações configuráveis.

- **Tratamento de Erros:** Middleware dedicado para garantir respostas adequadas em situações de falha durante as requisições.

## **Funcionalidades Destacadas**

### Equipamento

- `GET /equipamento:` Lista todos os equipamentos.
- `POST /equipamento:` Adiciona um novo equipamento com base nos dados fornecidos.
- `GET /equipamento/emissao-total:` Retorna a emissão total de CO2 por equipamento.

### Categoria

- `GET /categoria:` Lista todas as categorias.
- `GET /categoria/emissao-total:` Apresenta a emissão total de CO2 por categoria.

## **Configuração**

1. Instale as dependências usando `npm install`.
2. Configure a conexão com o banco de dados no arquivo `connection.js`.
3. Inicie o servidor com `npm start`.
4. Acesse em [http://localhost:4000](http://localhost:4000).

## **Agradecimentos**

Nossos agradecimentos especiais a todos que contribuíram para o sucesso deste projeto:

- **Vitor**
- **André**
- **Icaro**

Agradecemos também aos alunos da comissão de organização do evento, à faculdade FAESA e aos nossos parceiros, Code n' App, Inflor, TecVitoria Incubadora e Vale. Esta jornada foi possível graças ao esforço coletivo e à colaboração incrível de cada pessoa envolvida.

## **Lições Aprendidas**

Durante o processo de desenvolvimento, aprendemos lições valiosas que moldaram nossa jornada:

- **Debate de Ideias:** O constante debate de ideias enriqueceu a diversidade de perspectivas, contribuindo para a solidez do projeto.
  
- **Troca de Experiências:** A troca de experiências entre os membros do grupo permitiu uma aprendizagem contínua, explorando diferentes abordagens e soluções.

- **Estratégias Variadas:** A experimentação de diferentes estratégias foi crucial para moldar a ideia do projeto, desde sua estrutura até sua missão.

Esta experiência não apenas representou um esforço coletivo, mas também proporcionou um ambiente de aprendizado e colaboração valioso para todos os envolvidos. Estamos ansiosos para continuar aprimorando e expandindo esta iniciativa.

*Nota: Este projeto é um protótipo inicial desenvolvido durante o Hack Faesa 12.0 e está sujeito a melhorias contínuas.*
