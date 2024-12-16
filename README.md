## Для запуска:
 - npm i
 - npm run start

## Комментарии к задаче:
 - основной стек: Typescript, MaterialUI, Redux Toolkit, Jest
 - create-react-app оказывается уже давно не поддерживается, работает с ошибками, из за этого пришлось использовать решение от Vite (с ним не работал, поэтому конфиги правил поверхностно), а писать сборку на Webpack`е посчитал не целесообразным из за непонятных дедлайнов
 - планировал использовать CSS-IN-JS, но он не поддерживается MUI 6, да и стилей очень мало, поэтому писал на чистом css
 - смутила формулировка в задании "использовать React Hooks", если речь про встроенные хуки, то без них и так никуда, а если речь про что то другое, то я не понял о чем :)
 - добавил вызов https://jsonplaceholder.typicode.com для симуляции работы с бэком, но как оказалось, он работает только с впн, иначе запросы падают. Оставил коммент, что убрать, чтобы отключить запросы
