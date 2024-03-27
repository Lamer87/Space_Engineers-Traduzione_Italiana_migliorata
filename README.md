## Space Engineers: Traduzione Italiana migliorata 🇮🇹
### Versione gioco: `1.203.6` - *Anniversary Pack* 🎂
#### Versione della traduzione: `0.8`
[<img src="https://i.ibb.co/FVrhPxC/se-ita-flag.jpg" width="200"/>](https://github.com/Lamer87/Space_Engineers-Traduzione_Italiana_migliorata#space-engineers-traduzione-italiana-migliorata-)

Perchè?  
Durante il lockdown, non avendo niente da fare, ho passato 2 settimane a tradurre l'intero gioco in italiano, perchè all'epoca erano tradotte giusto poche righe del menù e nient'latro.  
Ho anche pubblicato la traduzione qui su github ma, poco tempo dopo e con l'arrivo di un nuovo DLC, la traduzione italiana è stata finalmente rilasciata.  
Finalmente avevano preso in considerazione la community italiana, ma poi mi sono reso conto che la traduzione faceva cagare (a dir poco), quindi ho pensato di apportare qualche miglioria.

---

- Lo scopo di questo progetto è quello di rendere più adeguata la traduzione in italiano del gioco, garantendone la stessa immersività della versione in inglese.

- Consiste in soli 2 file relativi alla lingua italiana, non viene toccato nient'altro.

- Tutti i cambiamenti fatti fino ad ora sono aggiornati alla v1.203.6, ma potrebbero essere necessarie altre modifiche. Ovviamente siete liberissimi di dare una mano!

- Se avete dei suggerimenti sulla traduzione, scrivetemi nelle [discussioni](https://github.com/Lamer87/Space_Engineers-Traduzione_Italiana_migliorata/discussions) con la parola o la frase che usa il gioco e quale dovrebbe essere quella corretta, così da trovarla e modificarla facilmente.

---
>[💾 Click qui per il download](https://github.com/Lamer87/Space_Engineers-Traduzione_Italiana_migliorata/archive/refs/heads/main.zip), o cliccate il tasto verde **`Code`** e poi su **`Download ZIP`**
---

- 🕹️ ***Installazione***:  

  - Estraete la cartella **"Content"** nella cartella del gioco, sostituendo i file:  
*dall'archivio* -> Space_Engineers-Traduzione_Italiana_migliorata \ `Content`  
*esempio cartella gioco* -> `C:\Program Files (x86)\Steam\steamapps\common\SpaceEngineers\`  

  - E' incluso un backup, nel caso vogliate ripristinare la traduzione di default, senza dover fare un recheck di tutti i file da Steam:  
*dall'archivio* -> Backup/`Content` -> *cartella del gioco*  
[<img src="https://i.ibb.co/h7hwpbn/Empty-png.png" width="1"/>](https://github.com/Lamer87/Space_Engineers-Traduzione_Italiana_migliorata#space-engineers-traduzione-italiana-migliorata-)

---

Giusto qualche esempio delle migliorie ("italiano del gioco" a sinistra - CORRETTO da me a destra):  

*dal blocco programmabile* : Corri = Esegui  
*dal generatore di ossigeno* : Riempi bottiglie = Riempi bombole  
*dal menù skin* : Ricicla la conferma dell'oggetto = Conferma il riciclo dell'oggetto  

Oltre alle migliorie ci sono anche degli aggiustamenti per far rientrare le parole nell'HUD o nella UI, per una migliore visibilità in tutti i contesti.

<details><summary>Cliccate qui per la lista completa dei cambiamenti (senza confronto con l'originale)</summary><p>

```
MyTexts.it.resx (\SpaceEngineers\Content\Data\Localization)


  <data name="AGravity" xml:space="preserve">
    <value>Gravità artif.</value> (così non esce fuori dall'HUD)

  <data name="BlockPropertyTitle_Refill" xml:space="preserve">
    <value>Riempi bombole</value>

  <data name="BriefingTutorial04Oxygen" xml:space="preserve">
    <value>Questo tutorial copre i vari blocchi relativi all'ossigeno, le fattorie idroponiche, i generatori, i condotti di ventilazione, le bombole, i serbatoi e il ghiaccio, comprese le funzioni del pannello di controllo. Viene anche affrontato il concetto di creare una camera a tenuta stagna per la pressurizzazione.</value>

  <data name="BriefingTutorial09ShipFlight" xml:space="preserve">
    <value>Questo tutorial offre istruzioni su come far volare una nave e utilizzare i tre strumenti della nave. Devi utilizzare ogni nave a turno per navigare attraverso diverse camere che dimostrano come smantellare, saldare e perforare, nonché come stoccare il carico di una nave e come attraccare con i connettori.</value>

  <data name="ControlMenuItemLabel_ShowAdminMenu" xml:space="preserve">
    <value>Apri menu admin</value>

  <data name="Description_AngleGrinder" xml:space="preserve">
    <value>Strumento per decostruzione e recupero. Tieni premuto {CONTROL:ABASE:PRIMARY_TOOL_ACTION} per smantellare.</value>

  <data name="Description_OxygenFarm" xml:space="preserve">
    <value>I generatori di ossigeno (fattorie idroponiche) producono piccole quantità di ossigeno quando sono a contatto con la luce del sole.

  <data name="Description_LockerRoom" xml:space="preserve">
    <value>Un armadietto per riporre strumenti, armi, munizioni e bombole. </value>

  <data name="Description_LockerRoomCorner" xml:space="preserve">
    <value>Un armadietto per riporre strumenti, armi, munizioni e bombole. </value>

  <data name="DisplayName_Category_ArmorBlocks" xml:space="preserve">
    <value>Blocchi Armatura</value>

  <data name="DisplayName_Category_CharacterAnimations" xml:space="preserve">
    <value>Animazioni Personaggio</value>

  <data name="DisplayName_Category_CharacterTools" xml:space="preserve">
    <value>Strumenti Personaggio</value>

  <data name="DisplayName_Category_Power" xml:space="preserve">
    <value>Blocchi di Energia</value>

  <data name="DisplayName_Category_ShipWeapons" xml:space="preserve">
    <value>Blocchi di Armi</value>

  <data name="DisplayName_Category_ShipTools" xml:space="preserve">
    <value>Blocchi di Strumenti</value>

  <data name="DisplayName_Item_AngleGrinder" xml:space="preserve">
    <value>Smerigliatrice</value>
    <comment>Smerigliatrice angolare per smantellare i blocchi</comment>

  <data name="DisplayName_Item_GravityGeneratorComponents" xml:space="preserve">
    <value>Componenti del Generatore di gravità</value>

  <data name="HelpScreen_ControllerHint9" xml:space="preserve">
    <value>Quando spari con un blocco arma di una nave che ha più armi dello stesso tipo, puoi alternare il fuoco con una singola arma o tutte in una volta con LB+LT</value>

  <data name="HelpScreen_ControllerHint10" xml:space="preserve">
    <value>Quando guardi alla porta dell'inventario con i blocchi nella coda del Planner di costruzione, puoi aggiungere componenti per i blocchi in coda alla produzione premendo {GAMEPAD_CONTROL:CHARACTER:BUILD_PLANNER_ADD_COMPONNETS}</value>

  <data name="HintKeyboardOnly05Text" xml:space="preserve">
    <value>Lo sapevi? 
    SPAZIOVUOTO
    SPAZIOVUOTO
Puoi scavare rapidamente gallerie senza produrre minerale utilizzando la funzione tasto destro del mouse con la tua trivella.</value>

  <data name="HintKeyboardOnly09Text" xml:space="preserve">
    <value>Puoi salvare le Creazioni premendo CTRL-B. Apri il menù progetti con F10.</value>

  <data name="Hint17Text" xml:space="preserve">
    <value>L'uso di una nave per smantellare un contenitore raccoglierà anche ciò che si trovava all'interno del contenitore.</value>

  <data name="HintKeyboardOnly04Text" xml:space="preserve">
    <value>Lo sapevi? 
    SPAZIOVUOTO
    SPAZIOVUOTO
La rotella del mouse, durante l'utilizzo di una telecamera o di una torretta, ti consente di ingrandire e rimpicciolire il campo visivo.</value>

  <data name="Hint21Text" xml:space="preserve">
    <value>Lo sapevi? 
    SPAZIOVUOTO
    SPAZIOVUOTO
Puoi controllare manualmente le torrette per mirare con precisione agli obiettivi.</value>

  <data name="Hint05Text" xml:space="preserve">
    <value>Lo sapevi?
    SPAZIOVUOTO
    SPAZIOVUOTO
La velocità del tuo jetpack può adeguarsi alla velocità delle griglie vicine utilizzando i relativi smorzatori.</value>

  <data name="Hint01Text" xml:space="preserve">
    <value>Lo sapevi?
    SPAZIOVUOTO
    SPAZIOVUOTO
Puoi usare /F per chattare solo con la tua fazione oppure /G per la chat globale.</value>

  <data name="Quote29Text" xml:space="preserve">
    <value>Un buon scienziato è una persona con idee originali. Un buon ingegnere è una persona che crea un progetto che funziona con meno idee originali possibili. Non ci sono prime donne nell'ingegneria.</value>

  <data name="TerminalControlPanel_RunCode" xml:space="preserve">
    <value>Esegui</value>

  <data name="TerminalControlPanel_RunCodeDefault" xml:space="preserve">
    <value>Esegui con il parametro di default</value>

  <data name="TerminalControlPanel_Warhead_SafetyTooltip" xml:space="preserve"> ?????? what ??????
    <value>Quando non selezionata, la testata può essere detonata manualmente. Questo non influenza la detonazione automatica dopo il conto alla rovescia.</value>

  <data name="ToolTipJoinGameServerSearch_Search" xml:space="preserve">
    <value>Aggiorna filtro di ricerca server attuale</value>

  <data name="ToolTipJoinGame_Search" xml:space="preserve">
    <value>Cerca inserendo il nome del server</value>

  <data name="ToolTipMods_Ok" xml:space="preserve">
    <value>Applica configurazione mod</value>

  <data name="Description_FAQ_Grinding" xml:space="preserve">
    <value>Puoi utilizzare una Smerigliatrice per smantellare i blocchi. I componenti vengono recuperati e trasferiti nel tuo inventario durante la smerigliatura. </value>

  <data name="Description_FAQ_UnknownSignals" xml:space="preserve">
    <value>I segnali indicano le posizioni delle capsule dove puoi ottenere un bottino e skin in modalità di sopravvivenza. I segnali deboli sono visibili solo a te. Segnali più forti sono visibili a tutti sul server, ma possono portare a un bottino migliore. </value>

  <data name="Description_FAQ_GPSColors" xml:space="preserve">
    <value>I Segnali Blu sono di tua proprietà. I segnali bianchi sono di proprietà di una fazione amica. I segnali rossi sono di proprietà di una fazione ostile. I segnali verdi e gialli indicano le capsule con un bottino. </value>

  <data name="DisplayName_DLC_DecorativeBlocks" xml:space="preserve">
    <value>Blocchi decorativi 1</value>

  <data name="Description_DLC_DecorativeBlocks" xml:space="preserve">
    <value>*** Descrizione dei blocchi decorativi 1 DLC ***</value>

  <data name="Contracts_AcceptConfirmation_Text" xml:space="preserve">
    <value>Accettando il presente contratto, l'utente è tenuto a soddisfare tempestivamente tutte le sue condizioni. 

  <data name="Economy_Notification_ReputationDecreased" xml:space="preserve">
    <value>Reputazione con {0} diminuita di {1}</value>

  <data name="Economy_Notification_ReputationIncreased" xml:space="preserve">
    <value>Reputazione con {0} aumentata di {1}</value>

  <data name="Description_BlockGroup_DeadBodies" xml:space="preserve">
    <value>I resti di sfortunati ingegneri. Possono contenere un bottino che altri possono trovare.</value>

  <data name="DisplayName_Category_SparksOfTheFuturePack" xml:space="preserve">
    <value>Blocchi Sci-Fi</value>

  <data name="DisplayName_DLC_Warfare1DLC" xml:space="preserve">
    <value>Blocchi Warfare 1</value>

  <data name="DisplayName_DLC_Warfare2DLC" xml:space="preserve">
    <value>Blocchi Warfare 2</value>

  <data name="DisplayName_Block_PassengerSeatOffset" xml:space="preserve">
    <value>Sedile del passeggero decentrato</value>

  <data name="DisplayName_Block_Railgun" xml:space="preserve">
    <value>Cannone a rotaia</value>

  <data name="DisplayName_Block_AirtightHangarDoorWarfare2A" xml:space="preserve">
    <value>Porta dell'hangar da guerra</value>

  <data name="DisplayName_Block_AirtightHangarDoorWarfare2B" xml:space="preserve">
    <value>Porta finestrata dell'hangar da guerra</value>

  <data name="DisplayName_Block_AirtightHangarDoorWarfare2C" xml:space="preserve">
    <value>Porta dell'hangar da guerra 2</value>

  <data name="DisplayName_Block_LargeReactorWarfare2" xml:space="preserve">
    <value>Reattore grande da guerra</value>

  <data name="DisplayName_Block_SmallReactorWarfare2" xml:space="preserve">
    <value>Reattore piccolo da guerra</value>

  <data name="NotificationHintLockTarget" xml:space="preserve">
    <value>{0} per agganciare il bersaglio</value>

  <data name="NotificationHintUnlockTarget" xml:space="preserve">
    <value>{0} per agganciare il bersaglio</value>

  <data name="DisplayName_Block_RocketLauncherWarfare2" xml:space="preserve">
    <value>Lanciarazzi da guerra</value>

  <data name="DisplayName_Block_BatteryWarfare2" xml:space="preserve">
    <value>Batteria da guerra</value>

  <data name="Description_MediumCalibreTurret" xml:space="preserve">
    <value>Gemello più lento e più grande del cannone automatico. Infligge danni considerevoli ai bersagli corazzati. Utilizza proiettili del cannone d'assalto.

  <data name="DisplayName_Item_LargeCalibreAmmo" xml:space="preserve">
    <value>Proiettile di artiglieria</value>

  <data name="Description_Railgun" xml:space="preserve">
    <value>Alta portata, massima penetrazione, cadenza di fuoco molto bassa. Ha bisogno di caricarsi prima di ogni colpo. Utilizza sabot per cannone a rotaia grande.

  <data name="DisplayName_Item_LargeRailgunAmmo" xml:space="preserve">
    <value>Sabot per cannone a rotaia grande</value>

  <data name="DisplayName_Item_SmallRailgunAmmo" xml:space="preserve">
    <value>Sabot per cannone a rotaia piccolo</value>

  <data name="Description_MediumCalibreGun" xml:space="preserve">
    <value>Gemello più lento e più grande del cannone automatico. Infligge danni considerevoli ai bersagli corazzati. Utilizza proiettili del cannone d'assalto.

  <data name="Description_SmallRailgun" xml:space="preserve">
    <value>Alta portata, massima penetrazione, cadenza di fuoco molto bassa. Ha bisogno di caricarsi prima di ogni colpo. Utilizza sabot per cannone a rotaia piccolo.

  <data name="BroadcastScreen_TakeControlButton_RemoteToolTip" xml:space="preserve">
    <value>Controllo Remoto pronto</value>

  <data name="DisplayName_Block_RemoteControl" xml:space="preserve">
    <value>Controllo Remoto</value>

  <data name="TerminalControlPanel_Cockpit_MainRemoteControl" xml:space="preserve">
    <value>Controllo Remoto principale</value>

  <data name="BroadcastScreen_RemoteControl" xml:space="preserve">
    <value>   Controllo Remoto</value>

---
---

MyCommonTexts.it.resx (\SpaceEngineers\Content\Data\Localization\Common)

  <data name="MessageBoxTextAreYouSureYouWantToDeleteSave" xml:space="preserve">
    <value>Sei sicuro di voler eliminare "{0}"?</value>

  <data name="MessageBoxTextAreYouSureYouWantToDeleteMultipleSaves" xml:space="preserve">
    <value>Vuoi davvero eliminare i file di salvataggio?</value>

  <data name="ScreenLoadInventoryRecycleItemMessageTitle" xml:space="preserve">
    <value>Conferma il riciclo dell'oggetto</value>

  <data name="IronSight_Hold" xml:space="preserve">
    <value>Tieni premuto per mirare</value>

  <data name="IronSight_Toggle" xml:space="preserve">
    <value>Attiva/Disattiva il mirino</value>

  <data name="ToolTipGameOptionsIronsightSwitchType" xml:space="preserve">
    <value>Cambia il modo di mirare con l'arma</value>

  <data name="IronSightSwitch" xml:space="preserve">
    <value>Tipo di attuazione della mira con l'arma</value>

```

</p></details>

[<img src="https://i.ibb.co/h7hwpbn/Empty-png.png" width="1"/>](https://github.com/Lamer87/Space_Engineers-Traduzione_Italiana_migliorata#space-engineers-traduzione-italiana-migliorata-)

---

- ⚠️ IMPORTANTE: se viene rilasciata una nuova major (quando introducono un nuovo DLC), NON riapplicate la traduzione attuale, altrimenti alcune nuove stringhe non saranno presenti e verranno mostrate in inglese all'interno del gioco.  
  - Basta aspettare l'aggiornamento della traduzione migliorata, tenendo d'occhio la versione qui in alto.  
- La traduzione è in continua evoluzione, verrà aggiornata man mano che si trovano parti da tradurre meglio.  

[<img src="https://i.ibb.co/h7hwpbn/Empty-png.png" width="1"/>](https://github.com/Lamer87/Space_Engineers-Traduzione_Italiana_migliorata#space-engineers-traduzione-italiana-migliorata-)
---

I file della lingua di Space Engineers possono essere aperti con un editor di testo, se volete potete modificarne il contenuto voi stessi:  

-"SpaceEngineers\Content\Data\Localization" MyTexts.it.resx ✔️  
-"SpaceEngineers\Content\Data\Localization\Common" MyCommonTexts.it.resx ✔️  
-"SpaceEngineers\Content\Data\Localization\CoreTexts" MyCoreTexts.it.resx ❌  

Sono 3 file in totale (uno per cartella), ma quello nella cartella CoreTexts non serve, traduce solo le linee riguardo ai crash del gioco.  
Per quanto riguarda la descrizione di alcuni degli scenari (nel menù nuova partita), andrebbero tradotti i file nelle cartelle degli scenari stessi, quindi vista la loro inutilità, non vale la pena tradurli.

[<img src="https://i.ibb.co/h7hwpbn/Empty-png.png" width="1"/>](https://github.com/Lamer87/Space_Engineers-Traduzione_Italiana_migliorata#space-engineers-traduzione-italiana-migliorata-)

---

- 📌 Se non volete pagare per i DLC, qui potete trovare il mio [DLC unlocker](https://github.com/Lamer87/Space-Engineers-DLC-unlocker)

[<img src="https://i.ibb.co/h7hwpbn/Empty-png.png" width="1"/>](https://github.com/Lamer87/Space_Engineers-Traduzione_Italiana_migliorata#space-engineers-traduzione-italiana-migliorata-)

---




<!--  -->
<!-- Useless code to use occasionally:

img download button:
[<img src="https://i.ibb.co/JxM2nh7/Donwload-button-png-LITE.png" width="175"/>](https://github.com/Lamer87/Space_Engineers-Traduzione_Italiana_migliorata/archive/refs/heads/main.zip)

img empty:
[<img src="https://i.ibb.co/h7hwpbn/Empty-png.png" width="1"/>](https://github.com/Lamer87/Space_Engineers-Traduzione_Italiana_migliorata#space-engineers-traduzione-italiana-migliorata-)
