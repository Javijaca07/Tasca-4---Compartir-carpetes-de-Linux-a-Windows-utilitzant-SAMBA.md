# Tasca-4---Compartir-carpetes-de-Linux-a-Windows-utilitzant-SAMBA.md

Activitat 1

Crea una carpeta a la MV Linux a /srv/samba/compartida1 amb els permisos necessaris perquè pugui accedir tothom.
![image](https://github.com/user-attachments/assets/c18d01f4-a101-4fc4-9164-58a824c6df72)


Crea la configuració de SAMBA per compartir la carpeta per a convidats (sense autenticació) amb lectura i escriptura.
![image](https://github.com/user-attachments/assets/36154c8d-785f-4365-92d7-46716eac8304)
![image](https://github.com/user-attachments/assets/aef0037a-d6a7-4fbf-be57-283dc4ff271d)


Reinicia el servei SAMBA.
![image](https://github.com/user-attachments/assets/5181b2e0-bced-4cbf-8fbf-9a9336b102fc)


Comprova que tens accés des de Windows.

Crea algun fitxer a la carpeta.

Comprova que s'ha creat a Linux.


Activitat 2

Crea una carpeta a la MV Linux a /srv/samba/compartida2 amb els permisos necessaris.
![image](https://github.com/user-attachments/assets/b438e3a5-d831-40c7-b8d2-eb477be2bad6)

Crea un usuari local anomenat user1_X (on X és el teu cognom).
![image](https://github.com/user-attachments/assets/10e76dcd-7914-4208-9dd8-4105abb278f1)

Afegeux l'usuari anterior a SAMBA.
![image](https://github.com/user-attachments/assets/0f0c1fb1-8463-46f0-b331-36060aef4cc4)

Crea la configuració de SAMBA per compartir la carpeta per a l'usuari anterior amb lectura i escriptura amb màscara de fitxers 755.

Reinicia el servei SAMBA.

Comprova que tens accés des de Windows amb les credencials de l'usuari.

Crea algun fitxer a la carpeta.

Comprova que s'ha creat a Linux i té els permisos 755.
