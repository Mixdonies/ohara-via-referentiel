# ohara-via-referentiel

Contenu publié d'une application de formation continue au secourisme
des sapeurs-pompiers, éditée par Ohara Via.

L'application lit ce dépôt pour mettre à jour son contenu. Seul le
dossier `publication/v1/` est publié :

- `recapitulatif.json` : récapitulatif **signé** par l'éditeur. Il
  désigne les fichiers à jour par leur nom, leur taille et leur
  empreinte SHA-256 ;
- `contenu-<numéro>.json` : le contenu de l'application ;
- `formateurs-<empreinte>.json` : la liste des codes formateur et des
  codes JSP des centres. Elle ne contient que des empreintes, jamais un
  code en clair.

L'application refuse tout fichier dont la signature ou l'empreinte ne
correspond pas. Une modification faite hors de l'éditeur est donc
ignorée par les téléphones.

Le contenu est une rédaction originale d'Ohara Via. Ce n'est pas le
référentiel officiel, et il ne le remplace pas : seul le document
officiel fait foi.

Éditeur : Ohara Via — contact@ohara-via.fr
