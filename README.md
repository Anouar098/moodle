# moodle
2. Configuració inicial de Moodle
2.1 Administració del perfil

    Inicia sessió com admin.

    Canvia correu i contrasenya a Preferències > Editar perfil.

    Afegeix un avatar.

2.2 Configuració del lloc

    Canvia nom del lloc:

        Administració del lloc > Primera plana > Paràmetres.

    Zona horària:

        Administració del lloc > Ubicació > Paràmetres.

    Idioma:

        Afegeix català si cal: Administració del lloc > Idioma > Paquets.

    Política de contrasenyes:

        Administració del lloc > Seguretat > Normatives del lloc.

3. Creació de cursos

    Curs A: 3 temes.

    Curs B: 5 temes.

    Accedeix a Administració > Cursos > Afegeix curs.

Personalització:

    Activa edició.

    Afegeix un PDF a un tema.

    Modifica títol d’un tema.

4. Gestió d’usuaris
4.1 Usuari manual

    Crea "Bob" com a usuari amb contrasenya segura.

4.2 Importació massiva

    Crea fitxer CSV amb 10 alumnes. 

username,firstname,lastname,email
alumne1,Anna,García,anna@example.com
alumne2,Biel,Martí,biel@example.com
alumne3,Clara,Solé,clara@example.com
alumne4,Dani,Rovira,dani@example.com
alumne5,Elena,Torres,elena@example.com
alumne6,Ferran,López,ferran@example.com
alumne7,Gemma,Vila,gemma@example.com
alumne8,Hugo,Puig,hugo@example.com
alumne9,Irene,Ferrer,irene@example.com
alumne10,Joan,Serra,joan@example.com
    Carrega’l des de Usuaris > Carrega usuaris.

    Elimina dos alumnes des d'Accions en bloc.

5. Matriculació d'usuaris
Curs A (públic):

    Desactiva mètodes d'inscripció.

    Assegura’t que es pot accedir sense login.

Curs B:

    Activa registre manual.

    Matricula:

        Bob com a professor.

        Alumnes com a estudiants.

6. Personalització del lloc

    Tema nou:

        Descarrega des de moodle.org/plugins > Instal·la complement.

    Canvia aparença:

        Header, footer, pàgina principal.

    Logotip:

        Afegeix-lo des de Administració del lloc > Aparença.

7. Continguts i activitats
Curs A

    Assigna professor i alumnes.

    Afegeix:

        Activitats (tasques, fòrums, etc.).

        Una tasca amb data límit i càrrega de PDF.

Curs B

    Utilitza Administració del curs > Importar per copiar continguts del curs A.

8. Qualificacions i insígnies

    Completa una activitat amb un usuari alumne.

    Configura:

        Administració del curs > Configuració de qualificacions.

    Crea una insígnia i assigna-la a un alumne.

9. Qüestionaris

    Crea un banc de preguntes amb categories.

    Afegeix un qüestionari al curs.

    Respon-lo amb un usuari alumne.

    Verifica la qualificació com a professor.

10. Importació / exportació de cursos

    Exporta una còpia de seguretat (.mbz) des de Administració > Còpies.

    Fes-la arribar a un company.

    Importa un curs des del fitxer rebut.

11. Seguretat

    Banneja una IP sospitosa des de:

        Administració del lloc > Seguretat > Polítiques del lloc.

    Justifica: intent d'accés no autoritzat, múltiples intents fallits, etc.

Recomanacions finals

    Organitza les captures per seccions.

    Utilitza títols clars i captacions descriptives.

    Inclou errors trobats i com els has resolt.

    Publica i comparteix l’enllaç del teu repositori GitHub amb el professorat.

Si vols, et puc ajudar a generar una plantilla README.md amb tot això estructurat. Vols que t’ho prepari?
Tú dijiste:
quiero que expliques cada paso de que hay que hacer y luego digas abajo del todo dejare las imagenes para entenderlo
ChatGPT Plus

Perfecto, aquí tens una explicació pas a pas de tota la pràctica amb una descripció clara de què s'ha de fer a cada apartat. Al final trobaràs la indicació sobre les imatges.
Pràctica: Instal·lació i Configuració de Moodle
Objectius generals

    Instal·lar i configurar Moodle en un entorn virtual.

    Aprendre a gestionar cursos, usuaris i continguts com a administrador.

    Explorar les funcionalitats d’un LMS aplicat a un entorn educatiu.

1. Instal·lació de Moodle
1.1 Preparació de l'entorn

    Accedeix a IsardVDI i crea un nou escriptori virtual.

    Instal·la els serveis necessaris: Apache, MySQL o MariaDB, i PHP.

    Descarrega Moodle des de https://moodle.org.

    Descomprimeix-lo a la carpeta web del servidor (normalment /var/www/html).

    Crea una base de dades nova per Moodle.

    Accedeix al navegador i finalitza la instal·lació seguint les instruccions pas a pas.

1.2 Documentació

    Crea un repositori a GitHub amb nom moodle-configuracio.

    Afegeix un fitxer README.md on aniràs explicant cada pas i afegint captures de pantalla.

2. Configuració inicial de Moodle
2.1 Administració del perfil d’usuari

    Inicia sessió com a usuari administrador.

    Canvia el teu correu electrònic i contrasenya des de Perfil > Editar perfil.

    Afegeix una imatge de perfil (avatar).

2.2 Configuració del lloc

    Canvia el nom del lloc (llarg i curt):
    Ves a Administració del lloc > Primera plana > Paràmetres.

    Configura la zona horària correcta:
    Administració del lloc > Ubicació > Paràmetres.

    Canvia l'idioma del lloc:
    Afegeix català si cal a Administració del lloc > Idioma > Paquets d’idioma.

    Estableix una política de contrasenyes:
    Mínim 8 caràcters, amb majúscules, minúscules i números.

3. Creació de cursos

    Crea dos cursos:

        Curs A amb 3 temes.

        Curs B amb 5 temes.

    Ves a Administració del lloc > Cursos > Afegeix curs.

Personalització

    Activa el mode edició dins del curs.

    Afegeix un document PDF a un dels temes.

    Canvia el títol d’un tema.

4. Creació i gestió d’usuaris
4.1 Creació manual

    Crea un usuari anomenat Bob des de:
    Usuaris > Comptes > Afegeix un usuari.

4.2 Creació massiva

    Crea un arxiu CSV amb dades de 10 alumnes.

    Carrega’l des de Usuaris > Carrega usuaris.

    Elimina 2 alumnes des de Accions amb usuaris en bloc.

5. Matriculació d’usuaris
5.1 Configuració

    Curs A:

        Desactiva tots els mètodes d'inscripció.

        Fes-lo accessible sense iniciar sessió.

    Curs B:

        Activa inscripció manual.

        Matricula Bob com a professor i la resta com a estudiants.

5.2 Verificació

    Accedeix al Curs A com a usuari anònim per comprovar que es pot veure.

    Comprova que per entrar al Curs B cal estar registrat.

6. Personalització del lloc

    Descarrega i activa un tema nou des de:
    Administració del lloc > Connectors > Instal·lar complement.

    Ves a Aparença > Selector de temes per activar-lo.

    Modifica:

        Capçalera (header).

        Peu de pàgina (footer).

        Pàgina principal.

    Afegeix un logotip al lloc.

7. Creació de continguts i activitats
Curs A

    Assigna un professor i matricula alumnes.

    Afegeix:

        Diverses activitats (fòrums, tasques, etc.).

        Una tasca amb data d'entrega i opció de pujar un PDF.

Curs B

    Clona els continguts del Curs A usant:
    Administració del curs > Importar.

8. Qualificacions i insígnies

    Un alumne completa una tasca.

    Configura el calificador per calcular notes automàticament.

    Crea una insígnia i atorga-la a un alumne des de Insígnies.

9. Qüestionaris

    Crea un banc de preguntes i organitza-les en categories.

    Crea un qüestionari i afegeix-hi preguntes.

    Completa’l amb un alumne.

    Revisa les qualificacions com a professor.

10. Importació i exportació de cursos

    Fes una còpia de seguretat d’un curs:
    Administració > Cursos > Còpies.

    Envia el fitxer .mbz a un company.

    Importa un curs que t’hagin enviat.

11. Seguretat

    Banneja una IP sospitosa des de:
    Seguretat > Polítiques del lloc.

    Justifica la decisió (ex: intents fallits d'accés o comportament maliciós).

Captures de pantalla

Al final del document, deixaré totes les imatges capturades durant cada pas per ajudar a entendre millor tot el procés.
