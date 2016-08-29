# Fullstack React.js Application boilerplate for 2016-2017 years

На данном этапе обсуждения и описание ведётся на русском языке, чтобы вам было удобней и комфортней. В сентябре всё будет переведено на английский. Благодарим за понимание.

Итак, друзья, уже шесть часов вечера, последний понедельник лета. Давайте подведём итог и пофантазируем?

Сейчас формируем некий Isomorphic React.js Application Boilerplate на следующие 12 месяцев.

Пока видим такой набор:

1. React 15.
2. На сервере - Node.js и Express.
3. CSS modules и <a href="https://github.com/kriasoft/isomorphic-style-loader">isomorphic-style-loader</a> для автоматической генерации Critical CSS при Server-side Rendering. Или всё-таки <a href="https://github.com/cssinjs/jss">JSS</a>,?
4. <a href="http://redux.js.org/">Redux</a> для взаимодействия внутри приложения. Или всё-таки <a href="https://facebook.github.io/relay/">Relay</a>?
5. Модульное тестирование через <a href="https://github.com/avajs/ava">AVA</a> и <a href="http://airbnb.io/enzyme/">Enzyme</a>. Или всё-таки <a href="https://facebook.github.io/jest/">Jest</a> с его автоматической генераций mock-объекта Browser?
6. UI-тестирование через <a href="http://nightwatchjs.org/">Nightwatch.js</a> + <a href="https://www.browserstack.com/start">Browserstack</a>.
7. Переводы через <a href="https://github.com/yahoo/react-intl">react-intl</a> и <a href="https://github.com/GertjanReynaert/react-intl-translations-manager">react-intl-translations-manager</a>.
8. Автоматическое определение языка на сервере через пакет <a href="https://www.npmjs.com/package/accept-language">accept-language</a>.
9. Автоматическое определение геопозиции через пакеты <a href="https://www.npmjs.com/package/maxmind">maxmind</a> и <a href="https://www.npmjs.com/package/ipaddr.js">ipaddr.js</a>.
10. Изоморфный логгер на базе <a href="https://github.com/trentm/node-bunyan">node-bunyan</a>.
11. <a href="https://github.com/gaearon/react-document-title">react-document-title</a> для динамического переключения заголовка вкладки.
12. <a href="https://github.com/matthew-andrews/isomorphic-fetch">isomorphic-fetch</a> для отправки HTTP-запросов (“AJAX”).
13. <a href="http://webpack.github.io/docs/what-is-webpack.html">webpack 1.x</a> для сборки. Или всё-таки <a href="https://webpack.github.io/docs/roadmap.html">webpack 2</a>?
14. <a href="https://webpack.github.io/docs/webpack-dev-server.html">webpack-dev-server</a> и webpack/hot/dev-server для Hot Module Reload.
15. Long-term Caching статических ресурсов (например: /assets/logo-8cdab5da.png).
16. <a href="https://www.npmjs.com/package/parallel-webpack">parallel-webpack</a> для ускорения сборки JavaScript bundle для каждого языка перевода (например: 5 разделов и 10 языков = это уже 50 JavaScript bundles).
17. <a href="https://robertknight.github.io/posts/webpack-dll-plugins/">webpack DllPlugin</a> для оптимизации размера JavaScript bundle.
18. <a href="https://github.com/reactjs/react-router-redux">react-router-redux</a> в качестве роутера.
19. <a href="http://eslint.org/">ESLint</a> и <a href="https://github.com/airbnb/javascript">eslint-config-airbnb</a> с небольшим изменением - не использовать точку с запятой.

Какие пункты можно изменить? Какие добавить? Что можно сделать лучше? Оставьте своё мнение в [Issues](https://github.com/StartupMakers/react-fullstack/issues).
