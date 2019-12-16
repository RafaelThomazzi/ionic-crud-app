# CRUD com IONIC 4 + Firebase
 Aplicação que cadastra, altera, atualiza, deleta e lista produtos alimentícios usando o Cloud Firestore (que é um banco de dados em nuvem) para armanezar os dados dos produtos.

# Instalação desse aplicativo (Instalando as dependências)
$ npm install

# Inserindo as credenciais do Firebase para usar o banco de dados
> Acesse https://firebase.google.com/
> Criar banco de dados
> Adicionar projeto
Copie suas credênciais e cole no arquivo que se encontra em:
src/environments/environment.ts

# Rodando o servidor no browser
$ ionic serve

# Gerando APK para IOS
Informações em: https://beta.ionicframework.com/docs/building/ios

$ ionic cordova platform add ios

$ ionic cordova build ios


# Gerando APK para Android
Informações em: https://beta.ionicframework.com/docs/building/android

$ ionic cordova platform add android

$ ionic cordova build android

No terminal será exibido o diretório onde o APK foi gerado.


