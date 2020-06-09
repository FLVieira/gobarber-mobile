<h1 align="center">
<img src="logo-purple.svg" width="180"/>

<br />
<br />
GoBarber 
</h1>

<p align="center">
  <a href="#tecnologias-utilizadas">Tecnologias utilizadas</a> |
  <a href="#instalação-e-execução">Instalação</a> 
</p>

Este é o cliente mobile de um projeto criado no Bootcamp da Rocketseat. Nele desenvolvemos um serviço apelidado de GoBarber onde os usuários podem se cadastrar como prestador de serviços na aplicação [web](https://github.com/FLVieira/gobarber-front) feita em ReactJS, e outros usuários podem agendar horário com estes prestadores através do aplicativo desenvolvido em React Native, sendo toda a lógica gerenciada pela [api](https://github.com/FLVieira/gobarber-api) (back-end), feita em NodeJS .

## Tecnologias utilizadas

- [axios](https://github.com/axios/axios)
- [date-fns](https://github.com/date-fns/date-fns)
- [immer](https://github.com/immerjs/immer)
- [prop-types](https://github.com/facebook/prop-types)
- [react](https://github.com/facebook/react)
- [react-native](https://github.com/facebook/react-native)
- [react-native-gesture-handler](https://github.com/kmagiera/react-native-gesture-handler)
- [react-native-linear-gradient](https://github.com/react-native-community/react-native-linear-gradient)
- [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons)
- [react-navigation](https://github.com/react-navigation/react-navigation)
- [react-redux](https://github.com/reduxjs/react-redux)
- [reactotron-react-native](https://github.com/infinitered/reactotron-react-native)
- [reactotron-redux](https://github.com/infinitered/reactotron-redux)
- [reactotron-redux-saga](https://github.com/infinitered/reactotron-redux-saga)
- [redux](https://github.com/reduxjs/redux)
- [redux-persist](https://github.com/rt2zz/redux-persist)
- [redux-saga](https://github.com/redux-saga/redux-saga)
- [styled-components](https://github.com/styled-components/styled-components)

## Instalação e execução

Pré-requisitos:

- Yarn/Npm
- [Back-end](https://github.com/FLVieira/gobarber-api) da aplicação executando.

```
# Configure o arquivo api.js dentro de src/services e o configure de acordo com as configuraçõs do seu emulador. 
# Se você estiver usando um dispositivo físico:
1 - No caso de um IOS, basta trocar o endereço contido por 'localhost'.
2 - No caso de um dispositivo android, coloque o endereço IPV4 da rede local do seu computador.

# Vá no seu terminal e digite os seguintes comandos:
1. git clone https://github.com/FLVieira/gobarber-mobile.git
2. cd gobarber-mobile
3. yarn 
4. yarn react-native start
5. yarn react-native run-android ( ou run-ios )
```
