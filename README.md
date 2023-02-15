### Objetivo

Este documento tem como intuito documentar todos os erros que presenciei enquanto desenvolvia aplicativos usando o Expo CLI.

## ApiV2Error: Entity Not Authorized
- Conta do expo que esta logada não é a mesma que esta no "owner" do app.json
Solução:
1 - Alterar o owner para o usuario que está logado
2 - Deslogar a conta atual do expo e logar com a que está no "owner"

## Build.VERSION.SDK_INT < Build.VERSION_CODES.TIRAMISU
Solução:
Mudar o compileSdkVersion e o targetSdkVersion para 33 em android/build.gradle
