En el ejercicio FILE INCLUSION de DVWA, se tiene el código inicial (FILE-INCLUSION-INICIAL.txt)


El funcionamiento tradicional sería trabajar con los archivos file1.php, file2.php, file3.php:


![image](https://user-images.githubusercontent.com/46895869/51545181-6c40e800-1e2f-11e9-9153-b8023d5fa867.png)


Debido a que no hay validación de entrada ni filtros, podemos entrar a la ruta y visualizar el archivo phpinfo.php:


![image](https://user-images.githubusercontent.com/46895869/51545341-cd68bb80-1e2f-11e9-95f3-3610bd5e8a6f.png)


Para corregir el código, realizamos la validación de entrada:


![image](https://user-images.githubusercontent.com/46895869/51545597-4c5df400-1e30-11e9-8bac-1936dfe81cc6.png)


Luego al realizar la prueba de acceso al archivo phpinfo.php, no se visualiza el archivo:


