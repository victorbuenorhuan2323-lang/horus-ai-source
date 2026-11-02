# HORUS AI — código recuperado do APK v2.7.3

Este repositório contém os arquivos de interface recuperados do APK do HORUS AI, incluindo HTML, CSS e JavaScript em `app/src/main/assets/index.html`.

**Atenção:** este **não** é o projeto Android Studio original completo. O APK contém arquivos `.dex` compilados, mas não o código-fonte Java/Kotlin original ou `build.gradle`; por isso esses arquivos não foram inventados.

## Estrutura
- `app/src/main/assets/index.html` — interface web (HTML, CSS e JavaScript).
- `app/src/main/assets/app_logo.png` — logo (se disponível).
- `app/src/main/assets/horus_profile_avatar.png` — avatar (se disponível).
- `CONFIGURACAO.example.txt` — exemplo sem credenciais.
- `.gitignore` — previne commits acidentais de chaves e segredos.

## Requisitos ausentes
A interface chama métodos de `QelvoriNative` que dependem de implementação Android. Para compilar um aplicativo equivalente, será necessário reconstruir a ponte Android e arquivos de projeto.

## Segurança
Nenhuma chave de API, token do GitHub, certificado, `.keystore` ou arquivo `xkiro.key` real deve ser publicado. **`SUA_CHAVE` é apenas um placeholder.** Para produção, configure chaves no backend, não no APK nem no frontend.

Recuperado do APK `HORUS_AI_v2_7_3_Sem_Imagem_Inicial_Assinado.apk`.
