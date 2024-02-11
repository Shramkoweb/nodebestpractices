# Оберніть загальні утиліти як пакети npm

<br/><br/>

### Пояснення за один абзац

Щойно ви почнете розвиватися та матимете різні компоненти на різних серверах, які використовують подібні утиліти, вам слід почати керувати залежностями – як ви можете зберегти 1 копію коду утиліти й дозволити багатьом споживчим компонентам використовувати та розгортати його? ну, для цього є інструмент, він називається npm... Почніть із того, що оберніть сторонні пакети утиліт своїм власним кодом, щоб зробити його легко замінним у майбутньому, і опублікуйте свій власний код як приватний пакет npm. Тепер уся ваша кодова база може імпортувати цей код і скористатися безкоштовним інструментом керування залежностями. Можна публікувати пакети npm для власного приватного використання, не публікуючи їх публічно, використовуючи [приватні модулі](https://docs.npmjs.com/private-modules/intro), [приватні регістри](https://npme.npmjs.com/docs/tutorials/npm-enterprise-with-nexus.html) or [локальні пакети](https://medium.com/@arnaudrinquin/build-modular-application-with-npm-local-modules-dfc5ff047bcc)
<br/><br/>

### Спільне використання власних спільних утиліт між середовищами та компонентами

![Структурування за компонентами](../../assets/images/Privatenpm.png "Структурування за компонентами")