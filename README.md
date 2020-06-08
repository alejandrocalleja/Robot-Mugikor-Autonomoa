# Robot Mugikor Autonomoa

Robot Mugikor Autonomoaren simulazio bat da, C lenguaian programatuta. Windows edo Linux-en sistema eragiletan erabili ahal da.

## Erabiltzen hasi

Hasteko, deskargatu *executable* bertsioa eta deskonprimatu.

Windows-en, **.exe**  ireki eta erabiltzen hasi.

Linux-en, hurrengo pausuak jarraitu:

   - Hasteko, ireki terminala: **ctrl + alt + T**
   - Hurrengo pausua deskargatutako fitxategian sartzea da. Horretarako, idatzi *cd* karpetaren helbidearekin jarraituta, adibidez:


```bash
cd /home/defaultName/Downloads
```
   - Behin karpetara sartuta terminalaren bidez, hurrengoa jarri behar da karpetan dagoena ikusteko:

```bash
ls -ls
```

   - Karpetan ikusi behar da *PBL2_linux* baimenduta. Baimenduta ez badago, jarri hurrengoa baimenak emateko:

```bash
chmod +x ./PBL2_linux
```

   - Behin hori eginda, programa irekitzeko, jarri hurrengoa:

```bash
./PBL2_linux
```

## Instalazioa SDL LINUX

**KONTUZ!** Arazoak baldin badituzu, agian da SDL2-ko libreria zure ordenagailuan instalatuta ez daukazulako. Horrela bada, jarraitu hurrengo pausuak:

- Konprobatu SDL-ko libreria instalatuta baldin badago.

```bash
apt-cache search libsdl2
```

- Instalatu.

```bash
apt-get install libsdl2-dev
```

# Robot Logístico Autónomo

Este proyecto es una simulación de un robot autónomo, programado en C. Se puede utilizar los SO de Windows y Linux.

## Comenzar a usar

Para comenzar, descarga la versión *executable* del proyecto y descomprima.

En Windows, habra el **.exe**  y comience a usar el programa.

En Linux, siga los siguientes pasos:

   - Para comenzar, abra el terminal con: **ctrl + alt + T**
   - El siguiente paso es llegar al directorio donde se encuentra el programa. Para ello, escriba *cd* seguido de la ruta de la carpeta, por ejemplo:


```bash
cd /home/defaultName/Downloads
```

   - Una vez en la carpeta, el siguiente paso es ver el contenido de esta. Para ello, introduzca:

```bash
ls -ls
```

   - Debemos encontrar el archivo llamado *PBL2_linux*. Este archivo debe tener permisos especiales. Si no los tiene, introduzca:

```bash
chmod +x ./PBL2_linux
```

   - Por último, para abrir el programa, introduzca:

```bash
./PBL2_linux
```

## Instalación SDL LINUX

**ATENCIÓN!** Si tienes problemas para ejecutar *PBL2_linux*, es posible que no tengas la librería de SDL instalada en tu ordenador. Para proceder con la instalación, siga los siguientes pasos:

- Comprueba la versión de SDL que tienes instalada:

```bash
apt-cache search libsdl2
```

- Instala la librería:

```bash
apt-get install libsdl2-dev
```
