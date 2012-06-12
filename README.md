AutoPatcher by TestBoy v1.00
=================

Jako 1. nahrajeme si na FTP všechny soubory, nastavíme jim CHMOD 777 a do šložky "\client" nakopírujete obsah clientu (bez patcher.cfg)...
2. Do clientu si přidáme soubor Patcher.exe, update.bin a patcher.cfg
3. V souboru patcher.cfg upravíme "patch_url" na vaší url, př. : http://client.wild-way.eu/ 
---POZOR !! ---
"patch_url" musí být nastavena na adresu kde máte patchlist.xml, status.txt, version.txt, patcher.xml, client a launcher, tzv. tam kam jsme dávali soubory na FTP !
4. Spustíme Patcher.exe a můžeme hrát !
PS
=================
P.S : Pokud jste změnili název Patcher.exe na jiný, musíte změnit název i na FTP ve složce "launcher" na souboru Patcher.exe a pak i v patcher.cfg v řárku : start_u
P.SS : Verzi v patcher.cfg můžete změnit, jen když změníte verzi v version.txt (na stejnou) !
P.SSS : Pokud v status.txt přepíšete text "povoleno" na nějaký jiný, tak vám nepůjde patchovat, a vždy vám to hodí  : Patchování je pozastaveno, chyba je pravděpodobně na naší straně ! Důvod : TEXT VYPLŇEN PO PŘEPSÁNÍ "povoleno".
