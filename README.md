@echo off
title Mayor y Menor de 3 Numeros
color 0A

echo ===============================
echo   MAYOR Y MENOR DE 3 NUMEROS
echo ===============================
echo.

set /p a=Ingrese el primer numero: 
set /p b=Ingrese el segundo numero: 
set /p c=Ingrese el tercer numero: 

rem Calcular mayor
set max=%a%
if %b% GTR %max% set max=%b%
if %c% GTR %max% set max=%c%

rem Calcular menor
set min=%a%
if %b% LSS %min% set min=%b%
if %c% LSS %min% set min=%c%

echo.
echo ===============================
echo El numero MAYOR es: %max%
echo El numero MENOR es: %min%
echo ===============================

pause
