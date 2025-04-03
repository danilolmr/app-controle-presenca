# 📱 App Controle de Presença

Este é um aplicativo desenvolvido em **Java e XML** no Android Studio para o controle de presença em eventos, utilizando **QR Code** para validação e **Firebase** como banco de dados.

## 🚀 Funcionalidades
- 📌 **Cadastro de Eventos**: Permite criar e gerenciar eventos.
- 🔑 **Autenticação Firebase**: Login com e-mail e senha utilizando Firebase Authentication.
- 📷 **Leitor de QR Code**: Implementado com a biblioteca ZXing para escanear códigos e validar presenças.
- 📊 **Registro de Presença**: Os dados são armazenados no Firebase Realtime Database.
- 🔍 **Consulta de Presenças**: Permite visualizar participantes registrados.

## 🛠️ Tecnologias Utilizadas
- **Java** e **XML** (Desenvolvimento nativo Android)
- **Firebase Authentication** (Gerenciamento de usuários)
- **Firebase Realtime Database** (Banco de dados em tempo real)
- **ZXing** (Biblioteca para leitura de QR Codes)
- **Google Services** (Integração com Firebase)

## 📦 Como Instalar e Executar
1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/portfolio.git
   ```
2. **Abra no Android Studio**: Vá em `File > Open` e selecione `app-controle-presenca`.
3. **Configure o Firebase**:
   - Crie um projeto no [Firebase Console](https://console.firebase.google.com/)
   - Baixe o arquivo `google-services.json` e coloque na pasta `app/`.
   - Habilite **Authentication** e **Realtime Database**.
4. **Execute no emulador ou dispositivo físico**.

## 📂 Estrutura do Projeto
```
app-controle-presenca/
│── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/eventoqrcode/
│   │   │   │   ├── LoginActivity.java (Tela de login)
│   │   │   │   ├── SignUpActivity.java (Cadastro de usuários)
│   │   │   │   ├── MainActivity.java (Tela principal)
│   │   │   │   ├── ScannerActivity.java (Leitura de QR Code)
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   ├── drawable/
│   │   ├── AndroidManifest.xml (Configurações do app)
│── google-services.json (Chaves do Firebase)
```

## 🎥 Demonstração do App  
<a href="https://drive.google.com/file/d/1yRflBjRcPU-Ftn-o1apxEQIJGcY1TC8U/view?usp=sharing" target="_blank">
  <img src="https://img.shields.io/badge/🎥%20Cadastro%20e%20Tela%20Principal-blue?style=for-the-badge&logo=google-drive&logoColor=white" style="border-radius:10px;">
</a>

<a href="https://drive.google.com/file/d/1s0_f1uc8SMwLVnKvQlKHHe1SefDL2c9E/view?usp=sharing" target="_blank">
  <img src="https://img.shields.io/badge/🎥%20Acesso%20Admin%20e%20Validação%20do%20QR%20Code-blue?style=for-the-badge&logo=google-drive&logoColor=white" style="border-radius:10px;">
</a>

## 📄 Licença
Este projeto está licenciado sob os termos da **MIT License**. Consulte o arquivo [LICENSE](./LICENSE) para mais detalhes.
