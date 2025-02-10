# DictionaryApp

## Descrição

Aplicativo móvel para listagem e gerenciamento de palavras em inglês, utilizando a API Free Dictionary API. O projeto implementa conceitos modernos de arquitetura de software, incluindo Clean Architecture e Redux Toolkit para gerenciamento de estado.

## Arquitetura

O projeto utiliza **Clean Architecture** para separar as responsabilidades em camadas bem definidas, garantindo escalabilidade e facilidade de manutenção. O **Redux Toolkit** gerencia o estado global de forma eficiente, facilitando o compartilhamento de dados entre componentes sem dependências desnecessárias. Essa abordagem melhora a testabilidade do código e reduz a complexidade de interação entre módulos.

## Tecnologias Utilizadas

### **Frontend**

- React Native
- Redux Toolkit
- Styled Components (ou Material UI, a definir)
- React Navigation

### **Backend e Banco de Dados**

- Firebase (Autenticação e armazenamento de favoritos e histórico)
- AsyncStorage (Cache local para otimizar requisições)

### **Testes**

- Jest
- React Testing Library (para testes unitários)

## Como Instalar e Usar

1. Clone o repositório:

   git clone https://github.com/seuusuario/dictionaryapp.git
   cd dictionaryapp

2. Instale as dependências:

   npm install # ou yarn install

3. Execute o projeto no emulador ou dispositivo físico:

   npx react-native run-android # Para Android
   npx react-native run-ios # Para iOS

## Estrutura do Projeto

```
/
|-- src/
|   |-- app/                # Configuração do Redux Toolkit
|   |-- data/               # Fontes de dados(API, Firebase, AsyncStorage)
|   |-- domain/             # Casos de uso e regras de negócio
|   |-- presentation/       # Componentes e telas (UI)
|   |-- navigation/         # Configuração de navegação
|   |-- tests/              # Testes unitários e E2E
```

## Challenge by Coodesh
