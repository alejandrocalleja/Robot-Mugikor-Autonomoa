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
