Mateus Teni Pierro - RM555125
# 📋 ListaTarefasPlus

O **ListaTarefasPlus** é um aplicativo mobile desenvolvido em **React Native** utilizando o **Expo**, com foco em produtividade e organização pessoal.  
O app permite que usuários criem, editem e gerenciem suas tarefas do dia a dia de forma simples, com recursos de **notificações, persistência local e integração com Firebase** para autenticação e sincronização.  

---

## 🖼️ Demonstração

(Adicione aqui prints de tela do aplicativo ou um GIF mostrando o uso)  

---

## 🚀 Tecnologias Utilizadas

Este projeto foi construído com as seguintes tecnologias e bibliotecas:

- [React Native](https://reactnative.dev/) – framework para desenvolvimento mobile
- [Expo](https://expo.dev/) – ferramenta para build, testes e publicação
- [Firebase](https://firebase.google.com/) – autenticação e backend
- [React Navigation](https://reactnavigation.org/) – navegação entre telas
- [AsyncStorage](https://react-native-async-storage.github.io/async-storage/) – armazenamento local
- [React Query](https://tanstack.com/query) – gerenciamento de estado assíncrono
- [i18next](https://www.i18next.com/) – suporte a múltiplos idiomas
- [Expo Notifications](https://docs.expo.dev/versions/latest/sdk/notifications/) – envio de notificações locais

---

## 📂 Estrutura do Projeto

ListaTarefasPlus/
│-- App.js # Arquivo principal do aplicativo
│-- index.js # Ponto de entrada
│-- package.json # Configurações e dependências do projeto
│-- app.json # Configurações do Expo
│-- assets/ # Ícones, imagens e splash screen
│-- node_modules/ # Dependências instaladas
│-- ...

markdown
Copy code

---

## 📦 Como Rodar o Projeto

Siga o passo a passo abaixo para rodar o projeto no seu ambiente:

### 🔧 Pré-requisitos

- [Node.js](https://nodejs.org/) (>= 16.x)
- [Expo CLI](https://docs.expo.dev/get-started/installation/) (instalada globalmente)
- [Git](https://git-scm.com/) (para clonar o repositório)
- Android Studio (para emulador Android) ou Xcode (para iOS) — opcional se for rodar apenas no celular físico

### ▶️ Passo a passo

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/Mateus07777/ListaTarefasPlus.git
   cd ListaTarefasPlus
Instale as dependências:

bash
Copy code
npm install
ou

bash
Copy code
yarn install
Inicie o servidor Expo:

bash
Copy code
npx expo start
Execute o app:

No terminal, pressione A para abrir no emulador Android

Pressione I para abrir no simulador iOS

Ou escaneie o QR Code gerado no terminal/browser usando o aplicativo Expo Go no seu celular

⚙️ Scripts Disponíveis
Do arquivo package.json, você pode rodar os seguintes scripts:

npm start → inicia o servidor do Expo

npm run android → abre no emulador Android

npm run ios → abre no simulador iOS

npm run web → abre no navegador

🔑 Funcionalidades
✅ Criar, editar e excluir tarefas

✅ Persistência local com AsyncStorage

✅ Lembretes e alertas com notificações locais

✅ Autenticação de usuário com Firebase Auth

✅ Sincronização de dados com Firebase

✅ Navegação simples e organizada entre telas

✅ Suporte a múltiplos idiomas com i18next

✅ Interface otimizada com Safe Area Context e React Native Screens
