# TheGame

Youtube: https://youtu.be/aomYtvGnl_o

====================== RU ====================== (Scroll down to EN)

Весь контент исключительно для демонстрации функционала.

Для корректной работы программы необходимо установить TheGame\Engine\Extras\Redist\en-us\UE4PrereqSetup_x64.exe

Если проверяете все на одном компьютере:
Достаточно просто запустить LoginServer.bat (логин сервер) и GameServer.bat (игровой сервер), а также TheGame.exe (Сама игра).
Менять ничего ненужно просто вводим любой логин + пароль и заходим.

Для игры по сети:
Настройка и запуск сервера: 
1) Найти файл с настройками по пути: TheGame\Saved\Config\WindowsServer\Game.ini (Если файла нету необходимо запустить один раз и закрыть LoginServer.bat и файл появится)
2) Вписать в поля 
	GameServer_Host - Адрес игрового сервера (внешний ИП), по умолчанию стоит 127.0.0.1
	GameServer_Port - Порт игрового сервера, по умолчанию 7777
3) Запустить LoginServer.bat и GameServer.bat, в дальнейишем можно сразу выполнять этот пункт

Настройка и запуск клиента:
1) Запустить TheGame.exe
2) В окне необходимо указать IP адрес и порт логин сервера, по умолчанию 127.0.0.1:7788
3) Вводим любой логин + пароль и заходим. Если пытаетесь подключится с тогоже компьютера на котором гейм сервер необходимо поставить галочку в правом верхнем углу перед входом.

Дефолтное управление (можно поменять в настройках)
W, A, S, D - Движение
E, Q - Поворот (Вертолет)
F - Войти (выйти) в транспорт
Space - Прыжок, Тормоз
LMB - Огон
RMB - Прицел
R - Перезарядка
G - Выбросить оружие
H - Бросить гранату
Mouse Wheel - Зум
1 - Предыдущее оружие
2 - Следующее оружие
Q - Спрятать оружие
Enter - Чат
L - Показать статистику команд
C - ПРО для вертолетов и танков
I - Инвентарь
X - Лечь
Ctrl - сесть

Серверные комманды (вводить в чат)
/loc - Текущие координаты
/reset - Сброс текущей позиции
/weapons - Выдать все оружие

/time norm - Нормальный ход времени
/time inc - Ускорение времени
/day - День
/night - Ночь
/bots on - Включить респавн ботов
/bots off - Выключить респавн ботов
/tidi on - Включить замедление времени
/tidi off - Выключить замедление времени
/rain - Включить(Выключить) дождь
/kill all - Убить всех
/notree - Убрать все деревья\столбы

Спавн техники:
/spawn uh60
/spawn mi24
/spawn bell407
/spawn btr80
/spawn buggy
/spawn bmw
/spawn abrams
/spawn grad
/spawn hamina
/spawn boat
/spawn pac3
/spawn f15c

/red - Сменить команду на RED
/blue - Сменить команду на BLUE
/name NewName - Сменить имя на NewName

====================== EN ======================

All content are for preview purpsses only!

Please install: TheGame\Engine\Extras\Redist\en-us\UE4PrereqSetup_x64.exe

If you play on one computer:
Just start LoginServer.bat and GameServer.bat and TheGame.exe for game.
Enter desired login + password and play.

For network play:
Setting up server:
1) Find config file: TheGame\Saved\Config\WindowsServer\Game.ini (if you don't have one just start one time LoginServer.bat and it will show up)
2) Change fields:
	GameServer_Host - Game server address (External IP), default 127.0.0.1
	GameServer_Port - Game server port, default 7777
3) Start LoginServer.bat and GameServer.bat, you should not modify these settings in future

Setting up client:
1) Start TheGame.exe
2) Modify IP address to Login Server external IP:Port, default 127.0.0.1:7788
3) Enter desired login + password and play. If you try to connect from the same computer that running GameServer than you need to check checkbox in right upper corner before connection.

Default controls (may be changed in game settings)
W, A, S, D - Movement
E, Q - Turn (Helicopter)
F - Enter (Exit) vehicle
Space -Jump, Handbrake
LMB - Fire
RMB - Aim
R - Reload
G - Drop current weapon
H - Grenade
Mouse Wheel - Zoom
1 - Previous weapon
2 - Next weapon
Q - Hide weapon
Enter - Chat
L - Shoow team statistic
C - Anti-missile for vehicles
I - Inventory
X - Prone
Ctrl - Crouch

Server commands (Enter in chat)
/loc - Current location
/reset - Reset current location
/weapons - Give all weapons

/time norm - Normal time speed
/time inc - Increased time speed
/day - Day
/night - Night
/bots on - Turn on bot respawn
/bots off - Turn off bot respawn
/tidi on - Turn on time dilition
/tidi off - Turn off time dilition
/rain - Rain
/kill all - Kil all
/notree - Remove all trees

Vehicle spawn commands:
/spawn uh60
/spawn mi24
/spawn bell407
/spawn btr80
/spawn buggy
/spawn bmw
/spawn abrams
/spawn grad
/spawn hamina
/spawn boat
/spawn pac3
/spawn f15c

/red - Change team to RED
/blue - Change teem to BLUE
/name NewName - Change current name to NewName

Системные требования / System requirements:
CPU:			Intel Core 2 Quad CPU Q6600 @ 2.40GHz / AMD Phenom 9850 Quad-Core Processor @ 2.5GHz
RAM:			2 GB
OS:			Windows 7 64 Bit SP1
Video Card:		NVIDIA GeForce 9800 GT 1GB / AMD Radeon HD 4870 1GB (DX 10, 10.1, 11)
Sound Card:		Yes
Free Disk Space:	2 GB