# 🚀 PokeAI - Explorador de Pokémons

[![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)](https://expo.dev/)
[![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactnative.dev/)
[![PokeAPI](https://img.shields.io/badge/PokeAPI-FF6B35?style=for-the-badge&logo=pokemon&logoColor=white)](https://pokeapi.co/)

> Uma jornada interativa pelo mundo dos Pokémons! Descubra informações fascinantes sobre suas criaturas favoritas através de uma interface moderna e intuitiva.

## 📖 Sobre o Projeto

O **PokeAI** é um aplicativo móvel inovador desenvolvido com React Native e Expo que combina tecnologia e nostalgia. Inspirado nos jogos clássicos de Pokémon, este app permite aos usuários explorar dados reais de Pokémons através da poderosa PokeAPI, oferecendo uma experiência educacional e divertida para treinadores de todas as idades.

### 🎯 Objetivo

Demonstrar o poder das APIs modernas em aplicações móveis, proporcionando uma interface amigável para descoberta de informações sobre Pokémons, com foco especial nos três iniciais icônicos: Bulbasauro, Charmander e Squirtle.

## ✨ Funcionalidades

### 🏆 Principais Features

- **🎮 Seleção Interativa**: Escolha entre os três Pokémons iniciais lendários
- **📊 Dados em Tempo Real**: Busca instantânea de informações via PokeAPI
- **🖼️ Galeria Visual**: Imagens oficiais de alta qualidade dos Pokémons
- **📱 Interface Responsiva**: Design otimizado para dispositivos móveis
- **⚡ Performance**: Carregamento rápido e eficiente de dados
- **🌐 Multiplataforma**: Compatível com Android, iOS e Web

### 🔧 Recursos Técnicos

- **API Integration**: Consumo eficiente da PokeAPI
- **State Management**: Gerenciamento de estado com React Hooks
- **Error Handling**: Tratamento robusto de erros de rede
- **Offline Ready**: Estrutura preparada para funcionalidades offline

## 🛠️ Tecnologias Utilizadas

### Core Technologies

- **React Native 0.76.7** - Framework principal para desenvolvimento mobile
- **Expo ~52.0.37** - Plataforma de desenvolvimento e distribuição
- **React 18.3.1** - Biblioteca para construção da interface

### Dependências Principais

- `expo-status-bar` - Controle da barra de status
- `react-native-web` - Suporte para execução na web
- `@expo/metro-runtime` - Runtime otimizado do Metro

### Ferramentas de Desenvolvimento

- **Metro** - Bundler JavaScript para React Native
- **Babel** - Transpilador JavaScript
- **npm** - Gerenciador de pacotes

## 🚀 Instalação e Execução

### Pré-requisitos

Antes de começar, certifique-se de ter instalado em sua máquina:

- **Node.js** (versão 14 ou superior) - [Download](https://nodejs.org/)
- **npm** ou **yarn** - Gerenciador de pacotes
- **Expo CLI** - `npm install -g @expo/cli`
- **Git** - Para clonar o repositório

### 📥 Clonando o Repositório

```bash
git clone https://github.com/VictorAnizauBarros/pokeAi.git
cd pokeAi
```

### 📦 Instalando Dependências

```bash
npm install
# ou
yarn install
```

### ▶️ Executando o Projeto

#### Desenvolvimento Local

```bash
npm start
# ou
expo start
```

#### Plataformas Específicas

**Android:**

```bash
npm run android
# ou pressione 'a' no terminal do Expo
```

**iOS:**

```bash
npm run ios
# ou pressione 'i' no terminal do Expo (requer macOS)
```

**Web:**

```bash
npm run web
# ou pressione 'w' no terminal do Expo
```

## 📱 Como Usar

1. **Inicie o App**: Execute o comando de start e escolha sua plataforma
2. **Escolha seu Pokémon**: Selecione entre Bulbasauro, Charmander ou Squirtle
3. **Explore os Dados**: Toque em "Dados do Pokemon" para ver informações detalhadas
4. **Descubra**: Visualize nome, peso e imagem oficial do Pokémon escolhido

## 🔌 API Utilizada

Este projeto utiliza a **[PokeAPI](https://pokeapi.co/)**, uma API RESTful gratuita e open-source que fornece dados abrangentes sobre Pokémons.

### Endpoint Principal

```
GET https://pokeapi.co/api/v2/pokemon/{id}
```

### Dados Retornados

- Nome do Pokémon
- Imagem oficial (official artwork)
- Estatísticas básicas (peso, altura, etc.)
- Tipos e habilidades

## 📁 Estrutura do Projeto

```
pokeAi/
├── 📱 App.js                 # Componente principal da aplicação
├── ⚙️ app.json               # Configurações do Expo
├── 🚀 index.js               # Ponto de entrada
├── 📦 package.json           # Dependências e scripts
├── 🎨 assets/                # Recursos estáticos
│   └── 📸 images/            # Imagens e ícones
├── 📂 .expo/                 # Configurações do Expo (gerado)
├── 📂 node_modules/          # Dependências instaladas
└── 🔒 .gitignore             # Arquivos ignorados pelo Git
```

## 🤝 Contribuição

Contribuições são sempre bem-vindas! Este projeto é uma excelente oportunidade para aprender sobre:

- Desenvolvimento mobile com React Native
- Integração com APIs externas
- UI/UX design para aplicações móveis
- Boas práticas de código

### Como Contribuir

1. **Fork** o projeto
2. Crie uma branch para sua feature: `git checkout -b feature/nova-feature`
3. Faça suas alterações e commit: `git commit -m 'Adiciona nova feature'`
4. Push para a branch: `git push origin feature/nova-feature`
5. Abra um **Pull Request**

### Ideias para Contribuições

- ➕ Adicionar mais Pokémons à lista
- 🎨 Melhorar o design da interface
- 🌙 Implementar modo escuro
- 💾 Adicionar cache offline
- 🔍 Implementar busca por nome
- 📊 Adicionar mais estatísticas dos Pokémons

## 📄 Licença

Este projeto está licenciado sob a **0BSD License** - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

```
Copyright (c) 2024 Victor Anizau Barros

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
```

## 👨‍💻 Autor

**Victor Anizau Barros**

- 💼 [LinkedIn](https://linkedin.com/in/victor-hugo-anizau-barros-65a775322/)
- 🐙 [GitHub](https://github.com/VictorAnizauBarros)

---

## 🙏 Agradecimentos

- **PokeAPI** pela API incrível e gratuita
- **Expo** pela plataforma de desenvolvimento excepcional
- **React Native Community** pelo ecossistema robusto
- Todos os contribuidores e mantenedores dos projetos open-source utilizados

---

<div align="center">

⭐ Se este projeto te ajudou ou inspirou, dê uma estrela!

</div>
