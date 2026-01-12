# Arcdps-Traduction-FR

- Arcdps : https://www.deltaconnected.com/arcdps/ (par deltaconnected)
- **Téléchargement :** La traduction française la plus récente est disponible [ICI](https://github.com/Big759/Arcdps-Traduction-FR/releases/latest)

![alt text](https://github.com/Big759/Arcdps-Traduction-FR/blob/main/Capture.png?raw=true)

## Installation :
1. Télécharger **arcdps_lang.ini** (arcdps) ou **arcdps_table_lang.ini** ([boon table](https://github.com/knoxfighter/GW2-ArcDPS-Boon-Table)).

2. Ouvrir l'Explorateur de fichiers ou avec le raccourci : Windows + E

3. Déplacer le fichier dans le dossier "arcdps" se trouvant dans le dossier de Guild Wars 2. <br>
   Exemple : <code>"C:\Program Files (x86)\Guild Wars 2\addons\arcdps\"</code>

   Si le jeu n'a pas encore été lancé avec ArcDPS ces dossiers n'existent pas. <br>
   Il est possible de le créer manuellement afin de ne pas avoir à démarrer le jeu.

4. Terminé, au prochain lancement ArcDPS sera en français.

# Arcdps-Font
   - Police de caractère utilisée : "Roboto Medium".
   - Source : https://www.dafont.com/fr/roboto.font

## Notes :
**lang.ini**
- Si le fichier est édité, il est important de l'enregistrer avec l'encodage ANSI !
- Ne surtout pas l'enregistrer en UTF-8 sinon ArcDPS ne fonctionnera pas correctement, __ne tiendra pas compte des accents__ ou ne se chargera pas.

  Avec le "Bloc-notes" de Windows :
   - Aller dans le menu <code>"Fichier"</code> puis <code>"Enregistrer sous ..."</code>
   - (Re)nommer le fichier "lang" et ajouter ".ini" à la fin (lang.ini).
   - Sélectionner le type <code>"Tous les fichiers"</code>.
   - Vérifier que l'encodage en bas de la fenêtre indique bien <code>ANSI</code>
   - Vérifier que l'enregistrement a bien été effectué en ".ini" et non en ".ini.txt" ou ".txt".

  Avec "Notepad++" :
   - En ouvrant le fichier, aller dans le menu <code>"Encodage"</code> puis sélectionner <code>"ANSI"</code>
   - Aller dans le menu <code>"Fichier"</code> puis <code>"Enregistrer sous ..."</code>
   - Effectuer l'enregistrement en ".ini" (MS ini file).

**font.ttf**
- Il est possible d'utiliser une autre police de caractères que celle proposée.
- Elle doit impérativement être au format TTF (True Type Fonts).
- **Arcdps :** Elle doit être renommée "arcdps_font.ttf" afin qu'ArcDPS puisse la charger.
- **[Raidcore (Nexus)](https://raidcore.gg/Nexus) :** Elle doit être placée dans le dossier <code>...\Guild Wars 2\addons\Nexus\Fonts</code> et sélectionnée dans les options de style du menu Nexus. Le nommage n'a pas d'importance.
- Taille de la police recommandée : 13.0
