TestTcpConnection
=================

Tcp connection test. 

Use GCDAsyncSocket framework.

Реализовано на основе проекта GCDAsyncSocket；

Добавлен пользовательский тестовый интерфейс，

Реализована функция ручной отправки и получения сообщений，

Прост в использовании во время тестирования；

В оригинальной демонстрации GCDAsyncSocket тестовый интерфейс был относительно простым и неудобным в использовании.Кроме того, если сетевой кабель внезапно отсоединяется во время тестирования, socketConnection не может своевременно реагировать на состояние отключения сети, поэтому был добавлен класс достижимости, позволяющий судить об изменениях в состоянии сети.；

Тестовая ситуация: Wi-Fi, сети 2g/3g, мобильные телефоны переключаются между различными типами сетей, клиент внезапно отключает сетевой кабель, а сервер внезапно прерывает работу, и все это может реагировать корректно.；
