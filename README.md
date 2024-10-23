# WeatherApp

Este é um aplicativo de previsão do tempo desenvolvido em Flutter que exibe informações detalhadas sobre o clima na localização atual do usuário. O app utiliza o padrão de arquitetura BLoC para gerenciar o estado e consome a API do OpenWeather para obter dados meteorológicos.

## Funcionalidades
- Localização Atual: O aplicativo obtém automaticamente a localização do usuário para mostrar o clima da cidade onde ele está.
- Temperatura Atual: Exibe quantos graus está fazendo no momento.
- Temperatura Mínima e Máxima: Mostra a temperatura mínima e máxima previstas para o dia.
- Nascer e Pôr do Sol: Informa os horários do nascer e do pôr do sol.
- Atualização Dinâmica: As informações são atualizadas em tempo real com base na localização e nos dados fornecidos pela API.

## Tecnologias Utilizadas
- Flutter: Framework usado para o desenvolvimento do aplicativo.
- BLoC: Padrão de gerenciamento de estado para separar a lógica de negócios da interface do usuário.
- API OpenWeather: Para obter as informações meteorológicas em tempo real.
- Geolocalização: O app utiliza a localização do dispositivo para fornecer dados relevantes ao usuário.
