# lab2continues

2. @echo off
set /p dirname="Введите имя директории"
mkdir %dirname%
cd %dirname%
set /p filename="Введите имя файла"
echo.>%filename%.txt
set /p text="Введите текст"
echo %text%>%filename%.txt
type %filename%.txt 

![image](https://github.com/KurakAlina/lab2continues/assets/148537804/d9a5f58a-1ac4-4ea6-8a7b-280bca3a5844)
![image](https://github.com/KurakAlina/lab2continues/assets/148537804/bd0defc3-4999-4bb4-8e7c-5d8813f69e43)
![image](https://github.com/KurakAlina/lab2continues/assets/148537804/b89dbfe3-1543-4d4d-bde5-b4c349613204)
![image](https://github.com/KurakAlina/lab2continues/assets/148537804/57829ce9-07ab-4808-b807-bde31e97ad59)

3. @echo off
set /p program="Введите имя программы"
start "" %program%


![image](https://github.com/KurakAlina/lab2continues/assets/148537804/273152f9-5ed8-490b-9d87-f2b11db5d548)
4. @echo off
wmic bios get smbiosbiosversion
systeninfo | findstr /B /C:"OS
Name" /C:"OS Version"

![image](https://github.com/KurakAlina/lab2continues/assets/148537804/05997232-8db8-4118-b320-85929d80a6ef)

6. @echo off
set /p path="Введите путь для поиска"
dir /s /b /ad "%path%\*Debug*">debug_folders.txt
type debug_folders.txt

![image](https://github.com/KurakAlina/lab2continues/assets/148537804/19617677-9af3-408d-9eb7-5b0a067d8507)
![image](https://github.com/KurakAlina/lab2continues/assets/148537804/910c95dc-ab6a-4aa1-95bc-e98bfb7c17e7)

5.@echo off
set /p newpath="Введите новый путь"
set path "%path%;%newpath%

![image](https://github.com/KurakAlina/lab2continues/assets/148537804/3cde4ca5-27cb-4473-8fab-a6d3345d6ec9)





