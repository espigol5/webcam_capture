# webcam_capture
Just webcam capture

## Tips
https://wiki.archlinux.org/index.php/webcam_setup

http://www.linuxintro.org/wiki/Set_up_a_Webcam_with_Linux


Tutorial:

1 - Instalar l'OpenCV amb la comanda sudo apt-get install libopencv-dev.

2 - Entrar amb el teu compte de github i anar al perfil de beta-robots.

3 - Entrar en el repositori amb nom "webcam_capture" i clicar en l'icona "Fork" situada a la part superior dreta de la pantalla.

4 - Clonar el repositori,el qual acabem de fer un fork, en la nostra màquina local, amb la comanda "git clone /camí_del_repositori".

5 - Instalar en git en cas de no tenir-lo, amb la comanda "sudo apt-get install git".

6 - Entrar en la carpeta on haguem ubicat el repositori webcam_capture i crear i entrar en una nova carpeta anomenada build per exemple: "mkdir build && cd build".

7 - Un cop en la carpeta build introduir la comanda "cmake .." i seguidament la comanda "make", per iniciar la llibreria cmake i compilar els executables indicats en l'arxiu CMakeLists.txt.

8 - Per últim, introduim la comanda "./webcam_capture" per executar el programa. Finalment veurem com s'obre una nova finestra que ens retransmetrà la imatge de la nostra càmera.
