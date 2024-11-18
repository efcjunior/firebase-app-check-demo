# Firebase App Check Demo

Este repositório contém um projeto de demonstração para configurar o **Firebase App Check** em aplicativos Flutter. Foi criado com o objetivo de apoiar equipes de desenvolvimento na implementação do App Check em projetos em desenvolvimento.

## 🚀 Funcionalidades

- Integração com Firebase App Check.
- Configuração básica para aplicativos Android.
- Estrutura simples para facilitar a adaptação.

## 🛠️ Como Configurar

### Pré-requisitos

- [Flutter](https://flutter.dev/docs/get-started/install) instalado.
- Projeto configurado no Firebase Console.
- Arquivo `google-services.json` baixado do Firebase Console.

### Passos para Configuração

1. **Clone o repositório**
   ```bash
   git clone https://github.com/efcjunior/firebase-app-check-demo.git
   cd firebase-app-check-demo
   ```

2. **Adicione o arquivo `google-services.json`**
   - Faça o download no [Firebase Console](https://console.firebase.google.com/).
   - Coloque o arquivo na pasta `android/app`.

3. **Instale as dependências**
   ```bash
   flutter pub get
   ```

4. **Execute o aplicativo**
   ```bash
   flutter run
   ```

## 📂 Estrutura do Projeto

```plaintext
firebase-app-check-demo/
├── android/                # Configurações específicas para Android
│   ├── app/
│   │   ├── google-services.json  # Deve ser adicionado manualmente
│   │   └── src/
├── lib/                    # Código-fonte principal do app Flutter
├── pubspec.yaml            # Dependências do Flutter
└── README.md               # Documentação do projeto
```

## 🔒 Observação de Segurança

O arquivo `google-services.json` **não deve ser enviado para o repositório**. Ele foi adicionado ao `.gitignore` para evitar vazamento de dados sensíveis.

## 📝 Licença

Este projeto é distribuído sob a licença [MIT](LICENSE).

---

**Mantido por [efcjunior](https://github.com/efcjunior).**
```

---
