@echo off
setlocal enabledelayedexpansion
chcp 65001

:begin
cls
echo ██████╗  █████╗ ███╗   ██╗██████╗  ██████╗ ███╗   ███╗██╗███████╗███████╗ █████╗ ████████╗ ██████╗ ██████╗ 
echo ██╔══██╗██╔══██╗████╗  ██║██╔══██╗██╔═══██╗████╗ ████║██║╚══███╔╝╚══███╔╝██╔══██╗╚══██╔══╝██╔═══██╗██╔══██╗
echo ██████╔╝███████║██╔██╗ ██║██║  ██║██║   ██║██╔████╔██║██║  ███╔╝   ███╔╝ ███████║   ██║   ██║   ██║██████╔╝
echo ██╔══██╗██╔══██║██║╚██╗██║██║  ██║██║   ██║██║╚██╔╝██║██║ ███╔╝   ███╔╝  ██╔══██║   ██║   ██║   ██║██╔══██╗
echo ██║  ██║██║  ██║██║ ╚████║██████╔╝╚██████╔╝██║ ╚═╝ ██║██║███████╗███████╗██║  ██║   ██║   ╚██████╔╝██║  ██║
echo ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝╚═════╝  ╚═════╝ ╚═╝     ╚═╝╚═╝╚══════╝╚══════╝╚═╝  ╚═╝   ╚═╝    ╚═════╝ ╚═╝  ╚═╝
echo questo programma ti fa lanciare un dado virtuale. - discord.gg/chillspot


set /p start=Vuoi lanciare il dado? (si/no/): 
if /i "%start%"=="si" (
    cls
    goto start
) 
else (
    cls
    goto closing
)

:start
set /a num=%random% %% 6 + 1
if !num!==1 ( 
    echo sul dado e' uscito 1
    echo aspetta 3 secondi...
    timeout /t 3 /nobreak >nul
    cls
    goto continue
) else if !num!==2 ( 
    echo sul dado e' uscito 2
    echo aspetta 3 secondi...
    timeout /t 3 /nobreak >nul
    cls
    goto continue
) else if !num!==3 ( 
    echo sul dado e' uscito 3
    echo aspetta 3 secondi...
    timeout /t 3 /nobreak >nul
    cls
    goto continue
) else if !num!==4 ( 
    echo sul dado e' uscito 4
    echo aspetta 3 secondi...
    timeout /t 3 /nobreak >nul
    cls
    goto continue
) else if !num!==5 ( 
    echo sul dado e' uscito 5
    echo aspetta 3 secondi...
    timeout /t 3 /nobreak >nul
    cls
    goto continue
) else if !num!==6 ( 
    echo sul dado e' uscito 6
    echo aspetta 3 secondi...
    timeout /t 3 /nobreak >nul
    cls
    goto continue
) else (
    echo ERROR 404 NUMBER 1-6 NOT FOUND
    echo aspetta 3 secondi...
    timeout /t 3 /nobreak >nul
    cls
    goto continue
) 

:continue
set /p continue=Vuoi continuare? (si/no/start): 
if /i "%continue%"=="si" (
    cls
    goto start
)
if /i "%continue%"=="start" (
    cls
    goto begin
) else (
    cls
    goto closing
)

:closing
echo E' STATO BELLO TORNA A PIU' PRESTO!!
timeout /t 1 /nobreak >nul
ECHO 3...
timeout /t 1 /nobreak >nul
ECHO 2...
timeout /t 1 /nobreak >nul
ECHO 1...
timeout /t 1 /nobreak >nul
ECHO Closing...
timeout /t 1 /nobreak >nul
exit
