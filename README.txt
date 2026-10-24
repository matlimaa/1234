SIMULADOR DETRAN-SP — PROJETO ANDROID

Este ZIP contém o projeto-fonte do app Android offline e um workflow do GitHub Actions para compilar o APK na nuvem.

GERAR O APK SEM INSTALAR ANDROID STUDIO (requer conta GitHub e enviar o projeto para um repositório):
1. Extraia o ZIP.
2. Crie um repositório no GitHub e envie todos os arquivos desta pasta para ele (incluindo a pasta .github).
3. Abra o repositório no GitHub e vá à aba Actions.
4. Se solicitado, habilite os workflows.
5. Selecione “Build Android APK” e clique em “Run workflow”.
6. Quando terminar, abra a execução concluída e baixe o artefato “SimuladorDetranSP-debug-apk”.
7. Extraia o arquivo ZIP do artefato para obter app-debug.apk e transfira-o para o celular Android.
8. Ao instalar, o Android pode pedir autorização para instalar apps desta fonte.

O APK não foi compilado neste ambiente porque não há Android SDK/Gradle instalados e o ambiente não tem acesso à internet para baixar esses componentes.

Observação: o app reproduz a ficha histórica enviada na conversa e não confirma os critérios oficiais vigentes em São Paulo em 2026.
