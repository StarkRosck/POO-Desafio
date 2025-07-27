# Desafio POO - iPhone (DIO - Trilha Java Básico)

Este projeto simula a modelagem de um componente iPhone utilizando Programação Orientada a Objetos (POO) em Java. O sistema foi dividido em três interfaces principais, representando as funcionalidades do dispositivo:

## 🔧 Funcionalidades

### 🎵 Reprodutor Musical
- `tocar()`
- `pausar()`
- `selecionarMusica(String musica)`

### 📞 Aparelho Telefônico
- `ligar(String numero)`
- `atender()`
- `iniciarCorreioVoz()`

### 🌐 Navegador na Internet
- `exibirPagina(String url)`
- `adicionarNovaAba()`
- `atualizarPagina()`

## 🧱 Arquitetura

- `ReprodutorMusical.java` – Interface com métodos do player de música
- `AparelhoTelefonico.java` – Interface com métodos telefônicos
- `NavegadorInternet.java` – Interface com métodos do navegador
- `Iphone.java` – Classe concreta que implementa todas as interfaces
- `Main.java` – Classe de teste para simular as funcionalidades

## 🖼️ Diagrama UML

