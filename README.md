# WARPActivator
Активатор Cloudflare (TM) WARP для Windows-10/11.

В проекте использована утилита [GoodbyeDPI](https://github.com/ValdikSS/GoodbyeDPI) от `ValdikSS` (за что ему респект и уважуха).

Скачайте и установите Cloudflare (TM) [WARP](https://1111-releases.cloudflareclient.com/win/latest), примите условия Лицензии. Скачайте архив [WARPActivator.zip](https://github.com/AKotov-dev/WARPActivator/raw/main/WARPActivator.zip), распакуйте и запустите от Администратора файл `WARPActivator.exe`. Нажмите кнопку `Активация WARP` (см. скриншот). Если попытка соединения была неудачной, нажимайте кнопку до успешного подключения. Сделано в Windows-10, Lazarus-3.4.

1. Download and Install Cloudflare (TM) WARP,
a cloud icon will appear in the tray at the bottom right

2. Accept the terms of the WARP License

3. Run the `WARPActivator.exe` file as Administrator

4. Click the `WARP Activation` button

5. If the connection attempt was unsuccessful,
click the button again until the connection appears

![](https://github.com/AKotov-dev/WARPActivator/blob/main/ScreenShot-v0.5.png)

Начиная с версии `WARPActivator-v0.4` добавлен [экспериментальный режим](https://github.com/ValdikSS/GoodbyeDPI) "Редирект DNS". Если активация успешна именно в этом режиме, необходимо заменить системные DNS в параметрах сетевого подключения на Google или другие, которые не принадлежат провайдеру (yandex не рекомендуется).
