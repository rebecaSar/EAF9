===========================================================================
CREACI� I INSTAL�LACI� D'UNA M�QUINA VIRTUAL EN VIRTUALBOX PER REBECA SARAC
===========================================================================

.. sectnum::

.. contents:: Continguts

Introducci� a VirtualBox
~~~~~~~~~~~~~~~~~~~~~~~~~

Oracle VM VirtualBox �s un programari de virtualitzaci� per arquitectures x86/amd64. Actualment �s desenvolupat per Oracle Corporation com a part de la seva fam�lia de productes de virtualitzaci�.

Instal�laci� de VirtualBox
~~~~~~~~~~~~~~~~~~~~~~~~~~~
El primer que hem de fer, si no ho hem fet abans, �s instal�lar VirtualBox en el nostre sistema. Hem de descarregar la versi� corresponent al nostre sistema operatiu des de la seva p�gina web principal: https://www.virtualbox.org/.

Un cop descarregat, l'instal�lem seguint els passos per defecte.


Creaci� de la m�quina virtual
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Un cop instal�lat VirtualBox en el nostre sistema, l'executem i veurem una finestra semblant a la seg�ent.

.. image:: inici.jpg
    :width: 200px
    :align: center
    :height: 100px
    :alt: alternate text
    
Per crear una m�quina virtual nova premem sobre el bot� "Nova" i ens apareixer� l'assistent.

.. image:: crear_maquina.jpg
    :width: 200px
    :align: center
    :height: 100px
    :alt: alternate text

Triarem el sistema operatiu que voldrem instal�lar posteriorment. Podem posar-li el nom que vulguem i triar tant un fabricant (Microsoft, Apple, Linux, Oracle, etc) com la versi� del sistema operatiu (Windows 7, Windows 8, etc).

En el seg�ent pas hem de triar la mem�ria RAM que volem assignar al sistema operatiu. 

.. image:: ram.jpg
    :width: 200px
    :align: center
    :height: 100px
    :alt: alternate text
    
Despr�s configurem el disc dur virtual de la m�quina.

.. image:: discoduro.jpg
    :width: 200px
    :align: center
    :height: 100px
    :alt: alternate text

Podem triar si crear la m�quina sense un disc dur, crear un disc dur virtual nou o carregar un disc dur ja existent. 
En aquest cas crearem un disc dur nou.

Seguidament, afegim l'ubicaci� i la mida que tindr� el nostre disc dur.

.. image:: discoduro_tamano_ubicacion.jpg
    :width: 200px
    :align: center
    :height: 100px
    :alt: alternate text

A continuaci� marquem el tipus de disc dur. Segons l'opci� triada, ens permetr� obrir-lo amb altres programes de virtualitzaci� o no.

.. image:: discoduro_tipo.jpg
    :width: 200px
    :align: center
    :height: 100px
    :alt: alternate text

Finalment, podrem triar quina opci� d'emmagatzematge en el disc dur f�sic desitgem. 
Si triem en din�mic, la mida anir� augmentant segons augmenti l'espai ocupat en la m�quina virtual, en canvi, si triem en mida fixa, el disc dur ocupar� l'espai total assignat al nostre disc f�sic.

.. image:: discoduro_almacenamiento.jpg
    :width: 200px
    :align: center
    :height: 100px
    :alt: alternate text

Premem sobre el bot� "Crear" i ja tindrem la nostra m�quina virtual creada i llista per funcionar en VirtualBox.