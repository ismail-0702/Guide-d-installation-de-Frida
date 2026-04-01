# Guide-d-installation-de-Frida
Préparer Python et pip && Installer frida et frida-tools
<img width="1271" height="684" alt="Capture d&#39;écran 2026-04-01 172844" src="https://github.com/user-attachments/assets/c811bf01-a149-400b-aede-4d7a6f1a8059" />
Si plusieurs Python, forcer pip du bon interpréteur
<img width="1259" height="453" alt="Capture d&#39;écran 2026-04-01 172904" src="https://github.com/user-attachments/assets/5b6a71a7-73f8-4805-8d9a-b18161f12e3a" />
Frida bien installer et il affiche sa version 
<img width="659" height="68" alt="Capture d&#39;écran 2026-04-01 172918" src="https://github.com/user-attachments/assets/66f97d5c-fd22-4fcb-8580-8ec437217415" />
lister les processus en cours d'exécution
<img width="1062" height="676" alt="Capture d&#39;écran 2026-04-01 172929" src="https://github.com/user-attachments/assets/122f0ac2-8844-4ffa-967d-e1f7ed42bbd5" />
Allumez l'emulateur et accedez en tant que root
<img width="511" height="410" alt="Capture d&#39;écran 2026-04-01 173112" src="https://github.com/user-attachments/assets/0a17fdef-6224-4bf4-b20c-d77650102cd2" />
 Copier frida-server vers l’appareil Android
<img width="1262" height="118" alt="Capture d&#39;écran 2026-04-01 175300" src="https://github.com/user-attachments/assets/bb861cbf-2568-4ff0-8599-6a8854d3c449" />
listez les applications de l'emulateur et choisissez votre propre application pour faire les tests
<img width="1073" height="692" alt="Capture d&#39;écran 2026-04-01 180048" src="https://github.com/user-attachments/assets/6e18ad0a-4c19-48ef-a85e-d84da4c1c2f8" />
Lancer frida-server
<img width="1343" height="63" alt="Capture d&#39;écran 2026-04-01 180111" src="https://github.com/user-attachments/assets/1255a6e6-2222-4f44-80b9-8365d393f6a5" />
Créer un fichier nommé hello.js contenant le code suivant
<img width="809" height="278" alt="Capture d&#39;écran 2026-04-01 231349" src="https://github.com/user-attachments/assets/7b1fa172-4fed-45cf-bf5a-db2b562d92b4" />
Exécuter ensuite le script sur une application cible
<img width="1483" height="762" alt="Capture d&#39;écran 2026-04-01 220052" src="https://github.com/user-attachments/assets/4bb42822-80b4-4e67-a875-67b961b7be3c" />
Vérifier l’architecture du processus && Identifier le module principal de l’application && Inspecter une bibliothèque système critique && Vérifier la présence d’une fonction sensible
<img width="1090" height="630" alt="Capture d&#39;écran 2026-04-01 223337" src="https://github.com/user-attachments/assets/7b258f52-7862-45b3-83ae-6c95317d7815" />
Essayez d'autres script comme celui-ci qui permet au lieu d'incrementée une seule fois lorsqu'on appuis sur le bouton il s'incremente trois fois pour savoir qu'on peut changer la fonctionnalité de l'application 
<img width="1209" height="785" alt="Capture d&#39;écran 2026-04-01 231427" src="https://github.com/user-attachments/assets/c9656d7b-3011-4430-bcc6-35c312f973a0" />
Voici-ci le retour de Frida 
<img width="902" height="550" alt="Capture d&#39;écran 2026-04-01 222155" src="https://github.com/user-attachments/assets/5d5ecec4-3fe9-4c8a-a084-e3456a41eca1" />

