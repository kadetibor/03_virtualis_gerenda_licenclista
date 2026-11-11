# Virtuális gerenda – licenclista

A [Virtuális gerenda](https://github.com/kadetibor/03_virtualis_gerenda_app) program licencének online része: a kiadó
által aláírt (Ed25519) lista a kiadott licencek lejáratának módosításairól és visszavonásairól. A program induláskor
letölti és a beépített nyilvános kulccsal ellenőrzi; a lista nem hamisítható.

A lista csak a licencek véletlen azonosítóit, lejáratát és visszavonását tartalmazza – nevet, e-mail címet, gép
azonosítót nem. A fájlt a kiadó eszköze (`licenc/licenc_kiadas.py`) írja; kézzel ne módosítsd.
