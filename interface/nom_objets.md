# Noms des variables des objets de l'interface

Les noms sont sous format *typeObj_nameObj*.

## Barre d'outil

- Bouton Switch 2D / 3D : *btn_switchMode2D3D*
- Bouton Zoom + : *btn_zoomIn*
- Bouton Zoom - : *btn_zoomOut*
- Bouton Zoom sur l'emprise totale : *btn_zoomFull*
- Bouton Rotation de la caméra : *btn_cameraRotation*

## Fenêtre principale

- Fenêtre switch (pour passer d'une vue à l'autre) : *stackedWidget*
- Vue 2D :  
  - Fenêtre où se dessine la carte : *graphicsView_window2D*
  - Zone de texte de l'Epsg : *lineEdit_epsg2D*
  - Zone de texte de l'Échelle : *lineEdit_scale2D*
- Vue 3D :
  - Fenêtre où se dessine la carte : *openGLWidget_window3D*
  - Zone de texte de l'Epsg : *lineEdit_epsg3D*
  - Zone de texte de l'Échelle : *lineEdit_scale3D*

## Gestion des couches

- Outils de gestion des couches:
  - Bouton Information : *btn_layerInformation*
  - Bouton Monter la couche dans la liste : *btn_moveLayerUp*
  - Bouton Descendre la couche dans la liste : *btn_moveLayerDown*
  - Bouton Zoom sur l'emprise de la couche : *btn_zoomOnLayer*
  - Bouton Supprimer la couche : *btn_deleteLayer*

- Fenêtre de gestion des couches : *listeWidget_layersList*

- Fenêtre des informations attributaires : *tableWidget_layerAttributeInformation*