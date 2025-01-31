# ddos - современная ос
<!-- preimushestva list -->
## Преимущества
#### Скорость
Благодаря пакетному менеджеру pacman система работает быстро и стабильно (unstable означает, что версия *развивается*, а не вылетает каждые 5 секунд). 
А ещё ddOS запускается быстрее, чем Debian 9, Ubuntu, Fedora и openSUSE.
#### Простота
Система уже преднастроена и готова к использованию (установщика нет!)
А зачем установщик, если можно запускать систему из раздела внутреннего диска?
#### Чистота
На ddOS не установленны программы, которыми вы не пользуетесь.
Но вы сможете всегда их установить с помощью pacman.
## Как собрать
#### система собирается под ``archlinux``
#### зависимости — ``archiso``
1. С помощью ``neofetch`` гляньте *производителя* видеокарты. Модель неважна. Если производитель ``intel``, ``nvidia`` или ``amd``, то система будет работать.
2. Создайте папку ``release`` относительно файла build.sh или nvidia.sh
3. Если производитель видеокарты ``nvidia``, то запустите файл ``nvidia.sh``.
Если у вас видеокарта ``amd``/``intel``, запустите  ``build.sh``.
4. Когда .sh прогрузится в ``release/``, появится файл c названием ``ddos-V$V beta/aplha/pre-release/stable/unstable-$arch.iso``
где $V - версия, beta/aplha/pre-release/stable/unstable - состояние версии (см Релизы ), $arch - архитектура (обычно x86_64)
Пример:
``
ddos-V0.6 beta-x86_64.iso
``

*5. Вот и ваш .iso образ ddOS. Ставьте на флешку или в раздел внутреннего диска и готово!*
*(ахтунг: не ставьте полностью на весь диск, почитайте гайд по разделыванию диска под арч)*
## Как это выглядит:
![login](https://user-images.githubusercontent.com/61107330/147656439-af642cd4-c505-4279-b5b5-6f101dea0d27.png)
![osafterlogin](https://user-images.githubusercontent.com/61107330/147656499-63ef6e9e-9fc1-408f-aecf-50d55a5405fb.png)
![desktop](https://user-images.githubusercontent.com/61107330/147656541-c123457f-3b72-4667-b753-a13ce6f023ac.png)
![appmenu](https://user-images.githubusercontent.com/61107330/147390074-6befb1e9-98e3-4667-969c-f9eb90534fe1.png)
![defaultsettings](https://user-images.githubusercontent.com/61107330/147656585-989ef5ea-6b6a-4f64-a22a-f892ea78cfa8.png)
![lockscreen_meta+l](https://user-images.githubusercontent.com/61107330/147390119-abe920ac-1c38-4368-9947-464ac0792771.png)
![multitasking](https://user-images.githubusercontent.com/61107330/147656815-61999bd4-4389-45e6-ac98-87d66cb21bde.png)
![multitasking2](https://user-images.githubusercontent.com/61107330/147390514-55986025-d1f3-45c7-a91d-dd7a659e59fc.png)
![multitasking3](https://user-images.githubusercontent.com/61107330/147390093-6ea7d82b-367b-4da5-b4ca-b1261cb966fd.png)
## Релизы
V0.1 aplha - чистый archiso

V0.2 alpha - archiso с gnome
добавлены gnome, gpudrivers(intel,amd)
добавлено и включено gdm,networkmanager

V0.3 aplha - первый полный релиз ddOS
добвлен пользователь, обои, консольная утилита ddos_conf

V0.4 aplha - поддержка видеокарт nvidia

V0.5 beta - очищена от мусора

V0.6 beta - uefi только, чтобы загрузится с bios пересобирайте; багфикс

V0.7 pre-release - plasma

V0.8 pre-release - installer (наконец-то) (наверно)

V0.9 pre-release - оболочки на выбор (budgie, gnome, xfce, kubik³ и kde2 plasma)

V1.0 stable

V1.1 unstable

V1.2 stable

V1.3 unstable

V1.4 stable

V1.5 unstable

V1.6 stable

V1.7 unstable

V1.8 stable

V1.9 unstable

V2.0 stable
