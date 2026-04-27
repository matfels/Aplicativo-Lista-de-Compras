<img width="739" height="1600" alt="ListaDeCompras-APP" src="https://github.com/user-attachments/assets/b1241f5a-f9d3-44cd-97b4-f7ec38c37f7a" />
# 🛒 Lista de Compras (Comprar)

![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-1B1F23?style=for-the-badge&logo=expo&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow?style=for-the-badge)

Este é um aplicativo móvel desenvolvido com **React Native** e **Expo**, projetado para ajudar na organização de compras do dia a dia. O app permite criar uma lista de itens e filtrá-los entre pendentes e comprados.

## 📱 Layout

<p align="center">
  <img src="src/assets/logo.png" alt="Logo do App" width="150">
</p>

> **Nota:** O design foi construído pensando em uma experiência de usuário limpa e intuitiva, com separação clara entre a área de inserção de dados e a lista de itens.

## 🚀 Funcionalidades

* **Adicionar Itens:** Campo de entrada para novos produtos na lista.
* **Filtragem de Status:** Alternância visual entre itens "Pendentes" e "Comprados" utilizando componentes de filtro customizados.
* **Interface Responsiva:** Utilização de Flexbox para garantir que o layout se adapte a diferentes tamanhos de tela.
* **Tipagem Estática:** Código robusto utilizando TypeScript e Enums para controle de status.

## 🛠️ Tecnologias Utilizadas

* **[React Native](https://reactnative.dev/):** Framework principal para desenvolvimento mobile.
* **[Expo](https://expo.dev/):** Plataforma para facilitar a criação, build e deploy da aplicação.
* **[TypeScript](https://www.typescriptlang.org/):** Superset do JavaScript para tipagem estática e segurança no código.
* **StyleSheet:** Estilização nativa do React Native.

## 📂 Estrutura do Projeto

O projeto segue uma estrutura organizada para facilitar a manutenção e escalabilidade:

```text
/src
├── app/
│   └── Home/            # Tela principal da aplicação
├── assets/              # Imagens e ícones (logos, splash screens)
├── components/          # Componentes reutilizáveis
│   ├── Button/          # Botão de ação padrão
│   ├── Input/           # Campo de texto customizado
│   └── Filter/          # Botões de filtro (Pendentes/Comprados)
├── types/
│   └── FilterStatus.ts  # Definições de tipos e Enums
└── ...
