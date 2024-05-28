# Meu Primeiro Projeto React Native

Este é um projeto básico de React Native criado para demonstrar os componentes básicos e a funcionalidade do React Native. Este projeto inclui uma tela simples com um título, um campo de entrada de texto e um botão.

## Componentes Básicos

### View
- O componente `View` é um contêiner que pode conter outros componentes. Ele é semelhante a uma `div` no HTML.
- No exemplo, a `View` principal (`container`) contém todos os outros componentes da tela.

### Text
- O componente `Text` é usado para exibir texto na tela.
- No exemplo, o componente `Text` com a classe `title` exibe a mensagem "Olá, React Native!".

### TextInput
- O componente `TextInput` é usado para entrada de texto do usuário.
- No exemplo, o `TextInput` possui um placeholder "Digite algo".

### Button
- O componente `Button` é usado para criar botões clicáveis.
- No exemplo, o `Button` possui um título "Pressione-me" e exibe um alerta quando pressionado.

## Estrutura do Projeto

```plaintext
MeuPrimeiroProjeto/
├── App.js
├── node_modules/
├── package.json
├── babel.config.js
└── README.md
```

## Funcionamento do React

React é uma biblioteca JavaScript para construir interfaces de usuário. No React Native, usamos componentes como blocos de construção para criar a interface do aplicativo. Cada componente possui propriedades (props) e estado (state) que controlam sua aparência e comportamento.

## Comandos para Baixar e Iniciar o Projeto

### Instalar Expo CLI

Expo CLI é uma ferramenta que facilita o desenvolvimento com React Native.

```bash
npm install -g expo-cli
```

### Criar um Novo Projeto Expo

Crie um novo projeto Expo com o template padrão.

```bash
npx create-expo-app@latest --template
```

### Iniciar o Projeto

Navegue até a pasta do projeto e inicie o servidor Expo.

```bash
npx expo start
```

### Trabalhar na Web

Para configurar o projeto para a web, instale as seguintes dependências:

```bash
npx expo install react-native-web react-dom @expo/metro-runtime
```

### Instalar React Navigation

React Navigation é uma biblioteca usada para gerenciar a navegação entre telas no React Native.

```bash
npm install @react-navigation/native
npm install @react-navigation/stack
```

## Conclusão

Este projeto demonstra a criação de um aplicativo básico com React Native, utilizando componentes fundamentais como `View`, `Text`, `TextInput` e `Button`. Para projetos maiores e mais complexos, recomenda-se seguir os princípios de design de software como SOLID para manter o código organizado e escalável.