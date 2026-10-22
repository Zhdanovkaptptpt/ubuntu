**Выполнил:** Жданова Е.Д.  
**Логин Linux:** zdhanova-e-d  
**Дата выполнения:** 23 октября 2026 г.  
**Операционная система:** Windows 11 Pro + WSL (Ubuntu)

1. Установка WSL и создание пользователя
WSL установлен через Microsoft Store. Создан пользователь `zdhanova-e-d`.
Подсистема Windows для Linux (WSL) была установлена через Microsoft Store как официальное приложение Ubuntu. При первом запуске дистрибутива создан пользователь Linux с именем в формате "фамилия-инициалы" (zdhanova-e-d), что соответствует требованиям задания. В процессе инициализации автоматически настроена базовая файловая система и права доступа.
Проверка имени пользователя и даты:
<img width="322" height="101" alt="01" src="https://github.com/user-attachments/assets/35c8fd70-a82b-4a7d-b595-b71faee64197" />
<img width="680" height="207" alt="02" src="https://github.com/user-attachments/assets/7b1c1720-5070-4e06-a652-aabf3a9b1469" />

2. Установка интерпретатора Python 3
Интерпретатор Python 3 установлен через пакетный менеджер apt для обеспечения возможности выполнения скриптов на языке Python — одном из самых популярных языков для веб-разработки, анализа данных и автоматизации. В составе дистрибутива Ubuntu установлена актуальная стабильная версия 3.14.4 с полным набором стандартных библиотек.
Установка и проверка: 
<img width="737" height="197" alt="03" src="https://github.com/user-attachments/assets/5d833b15-c413-4161-98d8-13a5bdb9eb9c" />
<img width="162" height="37" alt="04" src="https://github.com/user-attachments/assets/58e1e14d-9679-44ba-8fdf-51226e59c27e" />

3. Установка компилятора GCC
Компилятор GCC (GNU Compiler Collection) версии 15.2.0 установлен для компиляции программ на языках C и C++. Это основной инструмент разработки системного программного обеспечения в среде Linux. GCC поддерживает множество архитектур и оптимизаций, являясь стандартом де-факто для разработки под Linux.
Установка и проверка:
<img width="675" height="232" alt="05" src="https://github.com/user-attachments/assets/b5697fca-0e7c-436e-9a92-2ed60508824c" />
<img width="310" height="39" alt="06" src="https://github.com/user-attachments/assets/0813570c-c591-4b81-bb73-33fa7ac8718f" />

4. Установка Java SDK (OpenJDK)
Комплект разработки Java (Java Development Kit) на базе OpenJDK версии 25.0.4.1 установлен для обеспечения возможности разработки и запуска Java-приложений. OpenJDK — это открытая реализация платформы Java SE, включающая компилятор javac, виртуальную машину JVM и стандартные библиотеки классов. Необходим для кроссплатформенной разработки корпоративных и веб-приложений.
Установка и проверка:
<img width="903" height="301" alt="07" src="https://github.com/user-attachments/assets/c11b1df2-cbb2-470f-8272-458db169fa42" />


5. Установка СУБД PostgreSQL
Реляционная СУБД PostgreSQL версии 18.6 установлена в качестве системы управления базами данных. PostgreSQL — мощная объектно-реляционная СУБД с открытым исходным кодом, поддерживающая стандарты SQL, транзакции ACID, хранимые процедуры и репликацию. В среде WSL1 служба PostgreSQL запускается вручную через init-скрипт (так как systemd не поддерживается полностью). Кластер базы данных инициализирован автоматически с кодировкой UTF-8 и стандартными настройками безопасности.
Установка:
Запуск:
Проверка статуса:
Результат — статус online:
<img width="808" height="240" alt="08" src="https://github.com/user-attachments/assets/3d0b05ef-593c-4864-91a4-49d65506a1c6" />
<img width="373" height="64" alt="09" src="https://github.com/user-attachments/assets/c0cdf3a1-378a-49b0-b075-a56286d29486" />
<img width="561" height="69" alt="11" src="https://github.com/user-attachments/assets/83bbe93b-f84b-4d26-9180-e30367c4149f" />
<img width="967" height="114" alt="10" src="https://github.com/user-attachments/assets/b8334717-c83c-45cc-9586-80d66707fd8a" />
<img width="970" height="151" alt="12" src="https://github.com/user-attachments/assets/82aa9bd3-8362-4477-8646-aa317cb07d41" />


6. Заключение
В ходе выполнения задания было успешно развернуто полнофункциональное окружение для разработки программного обеспечения в среде Windows Subsystem for Linux. Установлены и протестированы все необходимые компоненты: интерпретатор Python 3, компилятор GCC, Java SDK и СУБД PostgreSQL. 
