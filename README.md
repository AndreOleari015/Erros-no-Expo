### Bem vindo(a)
Esse repositório foi feito para ser uma biblioteca de erros, pode ser que isso já exista, mas como eu não encontrei algo que listase os errorls de forma simples e que logo abaixo mostra a as possiveis solucões resolvi Fazer minha propria e se você quiser também pode ajudar, se por um acaso você conseguiu resolver aquele ponto e virgula que tava faltando e quer ajudar outros devs a não ter que passar pelo mesmo estresse, coloque aqui a palavra chave do erro e a sua solucão, espero que esse repositório possa te ajudar :)

### Objetivo

Este documento tem como intuito documentar todos os erros que presenciei enquanto desenvolvia aplicativos usando o Expo CLI.

## ApiV2Error: Entity Not Authorized
- Conta do expo que esta logada não é a mesma que esta no "owner" do app.json
Possiveis Solucões:
- Alterar o owner para o usuario que está logado
- Deslogar a conta atual do expo e logar com a que está no "owner"

## Build.VERSION.SDK_INT < Build.VERSION_CODES.TIRAMISU
Possiveis Solucões:
- Mudar o compileSdkVersion e o targetSdkVersion para 33 em android/build.gradle
