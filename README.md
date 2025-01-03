# IMC Calculator React

Este é um projeto de uma **Calculadora de IMC (Índice de Massa Corporal)**, construída com **React**. O projeto permite calcular o IMC de uma pessoa a partir de sua altura e peso e exibir a classificação correspondente. O sistema também exibe uma tabela com as classificações de IMC e informações sobre a obesidade.

## Funcionalidades

- **Cálculo do IMC**: O usuário pode inserir sua altura e peso, e o IMC será calculado e exibido.
- **Classificação do IMC**: Com base no valor do IMC, o projeto exibe uma classificação (Abaixo do peso, Peso normal, Sobrepeso, etc.).
- **Tabela de Classificações**: Uma tabela exibe as faixas de IMC com suas respectivas classificações e informações sobre obesidade.
- **Limpeza de Formulário**: O formulário pode ser limpo para permitir um novo cálculo.

## Tecnologias Utilizadas

- **React**: Biblioteca JavaScript para construção da interface de usuário.
- **CSS**: Estilos para a formatação e layout das páginas.
- **Hooks do React**: Utilização de `useState` para gerenciar o estado da aplicação.

## Como Rodar o Projeto

Para rodar o projeto em sua máquina local, siga os seguintes passos:

1. Clone o repositório:
   ```bash
   git clone https://github.com/ravelsilva/imc-calculator-react.git
   ```

2. Navegue até a pasta do projeto:
   ```bash
   cd imc-calculator-react
   ```

3. Instale as dependências:
   ```bash
   npm install
   ```

4. Inicie o servidor de desenvolvimento:
   ```bash
   npm start
   ```

O projeto estará disponível em `http://localhost:3000`.

## Estrutura de Arquivos

- `src/`: Contém o código-fonte do projeto.
  - `App.js`: Componente principal onde a lógica de cálculo do IMC é gerenciada.
  - `Components/`: Contém os componentes reutilizáveis.
    - `ImcCalc.js`: Formulário de entrada de dados para o cálculo do IMC.
    - `ImcTable.js`: Exibe os resultados do IMC e a tabela de classificações.
    - `Button.js`: Componente de botão reutilizável.

- `public/`: Contém arquivos estáticos, como o `index.html`.

## Licença

Este projeto é de código aberto e pode ser utilizado de acordo com os termos da licença MIT.

## Curso

Este projeto faz parte do curso **Formação Front-end - HTML, CSS, JavaScript, React e +** da Udemy, ministrado pelo professor Matheus Battisti.
