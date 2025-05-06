# Avaliação - React Native
 
## Como criar um emulador no Android Studio
 
1. Abra o **Android Studio**.
2. Vá em **Device Manager** no topo direito.
3. Clique em **Create Device**.
4. Escolha um modelo de celular (ex: Pixel 5) e clique em "Next".
5. Clique em **Finish** para criar o emulador.
 
## Como habilitar o SDK
 
- No Android Studio, vá em **Preferences** (ou **Settings** no Windows).
- Vá até **Appearance & Behavior > System Settings > Android SDK**.
- Marque a versão mais recente do Android (ex: Android 11 - API 30).
- Clique em **Apply** para instalar o SDK.
 
## Como configurar o ANDROID_HOME e JAVA_HOME
 
### Windows:
1. Abra as **variáveis de ambiente** do sistema.
2. Adicione:
 
```bash
ANDROID_HOME=C:\Users\SEU_USUARIO\AppData\Local\Android\Sdk
JAVA_HOME=C:\Program Files\Java\jdk-VERSAO
 
## Como abrir o projeto no emulador

- No terminal dentro do projeto de o comando npm run android
