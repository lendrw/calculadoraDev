# 📱 Calculadora Dev

Uma calculadora de investimentos focada na carreira de desenvolvimento de software, permitindo simular o crescimento financeiro através das diferentes fases da carreira.

## 🚀 Funcionalidades

- **Simulação por Fases da Carreira**: Júnior, Pleno, Sênior e Tech Lead
- **Cálculo de Juros Compostos**: Suporte para juros anuais e mensais
- **Visualização de Resultados**: Gráficos e timeline do crescimento
- **Interface Responsiva**: Compatível com iOS, Android e Web

## 🛠️ Tecnologias

- **React Native** com Expo
- **TypeScript**
- **Expo Router** para navegação
- **React Native Reanimated** para animações

## 📋 Pré-requisitos

- Node.js (versão 18 ou superior)
- npm ou yarn
- Expo CLI

## 🔧 Instalação

```bash
# Clone o repositório
git clone https://github.com/lendrw/calculadoraDev.git

# Entre no diretório
cd calculadoraDev

# Instale as dependências
npm install

# Inicie o projeto
npm start
```

## 📱 Executar

```bash
# Android
npm run android

# iOS
npm run ios

# Web
npm run web
```

## 📊 Como Usar

1. **Tela Inicial**: Apresentação do app
2. **Calculadora**: Configure os parâmetros:
   - Tipo de juros (anual/mensal)
   - Taxa de juros
   - Valor inicial
   - Percentual de economia
   - Anos em cada fase da carreira
3. **Resultados**: Visualize o crescimento projetado

## 🏗️ Estrutura do Projeto

```
├── app/                 # Ponto de entrada
├── components/          # Componentes reutilizáveis
├── constants/           # Dados e configurações
├── pages/              # Telas principais
├── types/              # Definições TypeScript
└── utils/              # Funções auxiliares
```

## 📄 Licença

Este projeto está sob a licença MIT.