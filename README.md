# Arcdps-Traduction-FR

- Arcdps : https://www.deltaconnected.com/arcdps/

## Installation :
1. Télécharger **arcdps_lang.ini** (arcdps) ou **arcdps_table_lang.ini** (boon table).

2. Ouvrir l'Explorateur de fichiers ou avec le raccourci : Windows + E

3. Déplacer le fichier dans le dossier "arcdps" se trouvant dans le dossier de Guild Wars 2. <br>
   Exemple : "C:\Program Files (x86)\Guild Wars 2\addons\arcdps\"

   Si le jeu n'a pas encore été lancé avec ArcDPS ces dossiers n'existent pas. <br>
   Il est possible de le créer manuellement afin de ne pas avoir à démarrer le jeu.

4. Terminé, quand ArcDPS sera actif, il sera en français.

# Arcdps-Font
   - Police de caractère utilisée : "Roboto Medium".
   - Source : https://www.dafont.com/fr/roboto.font

## Notes :
**lang.ini**
- Si le fichier est édité, il est important de l'enregistrer avec l'encodage ANSI !
- Ne surtout pas l'enregistrer en UTF-8 sinon ArcDPS ne fonctionnera pas correctement <br>
  __ne tiendra pas compte des accents__ ou ne se chargera pas.

  Avec le "Bloc-notes" de Windows :
   - Aller dans le menu "Fichier" puis "Enregistrer sous ..."
   - Vérifier que l'encodage en bas de la fenêtre indique bien ANSI
   - Effectuer l'enregistrement en ".ini" et non en ".ini.txt" ou ".txt".

  Avec "Notepad++" :
   - En ouvrant le fichier, aller dans le menu "Encodage" puis sélectionner "ANSI"
   - Aller dans le menu "Fichier" puis "Enregistrer sous ..."
   - Effectuer l'enregistrement en ".ini" (MS ini file).

**font.ttf**
- Il est possible d'utiliser une autre police de caractères que celle proposée.
- Elle doit impérativement être au format TTF (True Type Fonts).
- Elle doit aussi être renommée "arcdps_font.ttf" afin qu'ArcDPS puisse la charger.
