
# ionic-angular-native-resources

Este é um projeto de exemplo que utiliza Ionic e Capacitor para consumir a câmera (e outros futuros recursos) do dispositivo Android.

## Pré-requisitos

Certifique-se de que você tenha as seguintes ferramentas instaladas em seu sistema:

- Java Development Kit (JDK) e Java Runtime Environment (JRE)
- Android Studio
- Apache Ant
- NodeJS
- Git

## Passo a Passo

### 1. Clonar o Repositório

Clone este repositório para o seu ambiente local:
```sh
git clone https://github.com/seu-usuario/ionic-angular-native-resources.git
cd ionic-angular-native-resources
```

### 2. Instalar as Dependências

Instale as dependências do projeto usando npm:
```sh
npm install
```

### 3. Adicionar Capacitor ao Projeto

Instale Capacitor e inicialize-o no projeto:
```sh
npm install @capacitor/core @capacitor/cli
npx cap init
```

### 4. Adicionar a Plataforma Android

Adicione a plataforma Android ao projeto:
```sh
npx cap add android
```

### 5. Adicionar o Plugin de Câmera do Capacitor

Instale o plugin de câmera do Capacitor:
```sh
npm install @capacitor/camera
npx cap sync
```

### 6. Build do Projeto

Construa o projeto Ionic:
```sh
ionic build
```

### 7. Copiar os Arquivos Web para o Projeto Android

Copie os arquivos web construídos para o diretório Android do Capacitor:
```sh
npx cap copy
```

### 8. Abrir o Projeto no Android Studio

Abra o projeto Android no Android Studio:
```sh
npx cap open android
```

### 9. Executar a Aplicação no Android

Conecte um dispositivo Android ou inicie um emulador, e então clique em "Run" no Android Studio para instalar e executar a aplicação no dispositivo.

### 10. Build para Produção

Para construir a versão final do app para produção:
```sh
ionic build --prod
npx cap copy
```

## Contribuição

Sinta-se à vontade para contribuir com este projeto, fazendo um fork do repositório e enviando pull requests.
