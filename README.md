# msi-mpg-z390-gaming-edge-ac-hackintosh
My opencore hackintosh project

Конфигурация выглядит следующим образом
 - Процессор i9 9900k
 - Оперативная память Kingston 16G * 2
 - SSD M.2 Samsung 970 Evo плюс 500 ГБ
 - SSD M.2 WD Blue SN550 1TB NVMe
 - Версия BIOS 7B17vA7
 - Графика Radeon RX 5700 XT
 - Версия системы: 10.15.4
 - Интегрированная графика: используется только для вычислительных задач и не управляет дисплеем
 - Дискретная графика:  работает
 - Увеличенная частота процессора: 4.8 GHz
 - Звуковая карта: нормальная, выход dp не тестировался, а звуковая карта материнской платы работает отлично
 - Проводная сетевая карта: Работает
 - Материнская плата поставляется с беспроводной сетевой картой Intel, Bluetooth, установленный в системе, производства Intel и успешно активирован (только для обеспечения возможности использования Bluetooth).
 - Встроенный в материнскую плату WiFi НЕ РАБОТАЕТ


Не внесен в USBPorts.kext порт usb c, из-за отсутствия устройств с таким разъемом. 
![Не подписан на скриншоте](https://github.com/smaga38/msi-mpg-z390-gaming-edge-ac-hackintosh/raw/master/images/usb_map.png)

Огромное спасибо команде opencore
https://dortania.github.io/
также описание составления карты usb с помощью Hackintool
https://www.tonymacx86.com/threads/the-new-beginners-guide-to-usb-port-configuration.286553/#post-2029768

Использованный софт:
 - [gibMacOS](https://github.com/corpnewt/gibMacOS)
 - [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg/releases/)
 - [SSDTTime](https://github.com/corpnewt/SSDTTime)
 - [MaciASL](https://github.com/acidanthera/MaciASL/releases)
 - [ProperTree](https://github.com/corpnewt/ProperTree)
 - [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
 - [USBMap](https://github.com/corpnewt/USBMap)
 - [Hackintool](https://github.com/headkaze/Hackintool)
