# Scilab_Interactive_Interface
 
[French] Projet de traitement d'image interactif  
[English] Interactive Image Processing Project  

![Scilab](https://img.shields.io/badge/Scilab-Image_Processing-blue)
![Image Processing](https://img.shields.io/badge/Processing-Filters-green)
![GUI](https://img.shields.io/badge/GUI-Interactive-orange)
![Mathematics](https://img.shields.io/badge/Mathematics-Signal_Processing-red)
![Status](https://img.shields.io/badge/Status-Complete-success)

<div align="center">
  <img width="650" height="300" alt="image" src="https://github.com/user-attachments/assets/e650c748-edb7-4b8f-a3f1-7dc0a300899a">
</div>



(First it will be the French README then the English README After)  
---
#### SOMMAIRE / SUMMARY
- [Présentation en français / Presentation in French](#presentation-en-français)
- [Présentation en anglais / Presentation in English](#english-presentation)
- [Guide d'utilisation / User Guide](#guide-dutilisation--user-guide)

---

## [PRESENTATION EN FRANÇAIS]
Projet interactif permettant d'appliquer divers traitements d'image à l'aide d'une interface intuitive.  
Les utilisateurs peuvent naviguer entre plusieurs menus et choisir différents filtres et transformations à appliquer aux images chargées.

### Fonctionnalités principales :
- **Téléchargement des images traitées** : possibilité d'enregistrer chaque image après traitement.
- **Affichage dynamique** : les images affichées sont annotées avec des informations spécifiques (exemple : "Image agrandie à 512x512").
- **Gestion des traitements lourds** : un message "Traitement en cours..." s'affiche pour prévenir que le calcul est en cours.
- **Traitements en temps réel** : certains filtres s'appliquent immédiatement via des sliders ou menus déroulants.

### Menus principaux :
1. **Menu 1 : Transformations de base**  
   - Affichage, agrandissement, seuillage, histogramme, multiplication d’image.  
2. **Menu 2 : Opérations sur images**  
   - Addition, soustraction, rotation, inversion des couleurs, symétrie.  
3. **Menu 3 : Filtres avancés**  
   - Filtres passe-bas (moyenneur, médian, gaussien), passe-haut (Laplacien, Sobel), couleur personnalisée.  
4. **Menu Aide**  
   - Explications et guide d’utilisation.  

> [!NOTE]  
> Lors du premier lancement, le chemin vers le dossier 'image_menu' doit être défini manuellement.  



### ❓ **Menu Aide | Help (Aide) Menu**
- Disponible en permanence pour guider l'utilisateur.  

> [!TIP]  
> Si une opération prend du temps, laissez l’application travailler sans relancer une action.  

📌 **Note importante** :  
- Toutes les images sont affichées avec un titre décrivant l’opération appliquée.  
- Pour éviter des erreurs d'affichage, assurez-vous que Scilab supporte les boutons colorés.  
- Si un problème survient, contactez-moi.  

---



## [ENGLISH PRESENTATION]
Interactive project for applying various image processing techniques through an intuitive interface.  
Users can navigate through different menus and select filters and transformations to apply to loaded images.

### Key Features:
- **Download processed images**: Users can save each processed image.  
- **Dynamic display**: Processed images are labeled with specific information (e.g., "Image resized to 512x512").  
- **Heavy computation handling**: A "Processing in progress..." message appears to indicate ongoing calculations.  
- **Real-time processing**: Some filters apply instantly using sliders or dropdown menus.  

### Main Menus:
1. **Menu 1: Basic Transformations**  
   - Display, resizing, thresholding, histogram, image multiplication.  
2. **Menu 2: Image Operations**  
   - Addition, subtraction, rotation, color inversion, symmetry.  
3. **Menu 3: Advanced Filters**  
   - Low-pass filters (averaging, median, Gaussian), high-pass filters (Laplacian, Sobel), custom color filters.  
4. **Help Menu**  
   - Explanations and user guide.  

> [!NOTE]  
> On first launch, the path to the 'image_menu' folder must be manually set.  


### ❓ **Help Menu | Help Menu**
- Permanently available to guide the user.  

> [!TIP]  
> If an operation takes time, let the application work without restarting an action.  

📌 **Important note**:  
- All images are displayed with a title describing the operation applied.  
- To avoid display errors, make sure that Scilab supports colored buttons.  
- If a problem arises, contact me.  


---

## [GUIDE D’UTILISATION / USER GUIDE]
> [!NOTE]  
> Vous pouvez enregistrer chaque image avec le bouton nommé 'Enregistrer'
> You can save each image with the button named 'Enregistrer'

### **Menu 1 : Transformations de base** | Displaying an image  
#### 1. Affichage d’une image  
- Sélectionnez une image puis cliquez sur **"Montrer Image"**.
- Select an image then click on **"Montrer Image"**

#### 2. Agrandissement d’image  | Image enlargement 
- Ajustez la valeur avec le slider, puis cliquez sur **"Agrandir Image"**.
- Adjust the value with the slider, then click on **"Agrandir Image"**.
<div align="center">
  <img width="500" alt="image" src="https://github.com/user-attachments/assets/7acfd8ea-fa36-4f4b-8381-b4326ead0044">
</div>

#### 3. Histogramme | Histogram
- Cliquez sur **"Lancer"**, et attendez le calcul de l'histogramme (vous pouvez enregistrer chaque image avec le bouton nommé 'Enregistrer').
- Click on **"Lancer"**, and wait for the histogram to calculate (you can save each image with the button named 'Enregistrer ...')
<div align="center">
  <img width="500" alt="image" src="https://github.com/user-attachments/assets/e50dff4d-4f2a-487a-9d71-9f6f79e9be5a">
</div>

#### 4. Seuillage  | Threshold  
- Ajustez le seuil avec le slider, puis cliquez sur **"Seuillage Image"**.
- Adjust the threshold with the slider, then click on **"Seuillage Image"**
<div align="center">
  <img width="500" alt="image" src="https://github.com/user-attachments/assets/1dcbcfee-4557-4712-b046-f8d0d4f7c69d">
</div>

#### 5. Multiplication d’image | Image multiplication   
- Ajustez la valeur avec le slider, l'image est mise à jour automatiquement.
- Adjust the value with the slider, the image is updated automatically.
<div align="center">
  <img width="500" alt="image" src="https://github.com/user-attachments/assets/1cb0d1ee-a650-4ef8-bedb-1e7f2bae10bd">
</div>

---

### **Menu 2 : Opérations sur images**
#### 6-7. Addition & Soustraction d’images | Addition & Subtraction of images   
- Sélectionnez deux images puis cliquez sur **"Lancer"**
- Select two images then click on **"Lancer"**
<div align="center">
  <img width="500" alt="image" src="https://github.com/user-attachments/assets/f567b5d3-b377-4ee7-92bb-6c072509c784">
</div>

#### 8. Rotation  
- Ajustez l’angle avec le slider, puis cliquez sur **"Rotation Image"**.
- Adjust the angle with the slider, then click on **"Image Rotation"**.
<div align="center">
  <img width="500" alt="image" src="https://github.com/user-attachments/assets/2e72881f-e3ae-4fa9-bcf8-84a543b05bdd">
</div>

#### 9. Inversion des couleurs | Color Inversion    
- Cliquez sur **"Inverser Couleurs"**.
- Click on **"Inverser Couleurs"**. 
<div align="center">
  <img width="500" alt="image" src="https://github.com/user-attachments/assets/2aa7b986-b0ec-4ba9-92a8-ccbe5d4f9949">
</div>

#### 10. Symétrie  | Symmetry
- Choisissez le mode dans le menu déroulant, puis cliquez sur **"Symétrie Image"**.
- Choose the mode from the drop-down menu, then click on **"Symétrie Image"**. 
<div align="center">
  <img width="500" alt="image" src="https://github.com/user-attachments/assets/0b740832-9cd5-4a18-8004-a3944d917e44">
</div>

---

### **Menu 3 : Filtres avancés**
#### 11. Filtre Passe-Bas  | Low Pass Filter   
- Sélectionnez un filtre dans le menu déroulant, puis cliquez sur **"Lancer"**.
- Select a filter from the drop-down menu, then click  **"Lancer"**
  - **Options disponibles** | **Options available:**   
    - Bruit Gaussien | - Bruit Sel & Poivre | - Filtre Moyenneur | - Filtre Médian  | - Filtre Gaussien
    - Gaussian Noise | - Salt & Pepper Noise | - Filter Averager | - Median Filter | - Gaussian filter 
<div align="center">
  <img width="400" alt="image" src="https://github.com/user-attachments/assets/fa9f0b93-e11f-407b-8df4-5349d97fbd8f">
  <img width="300" alt="image" src="https://github.com/user-attachments/assets/d965fc93-26ba-4ba6-acdd-a435e0c33a88">
</div>

#### 12. Filtre Passe-Haut  
- Sélectionnez un filtre dans le menu déroulant, puis cliquez sur **"Lancer"**.  
  - **Options disponibles :**  
    - Filtre Laplacien-4 | - Filtre Laplacien-8 | - Filtre Sobel Vertical | - Filtre Sobel Horizontal | - Module du Gradient Sobel  
<div align="center">
  <img width="500" alt="image" src="https://github.com/user-attachments/assets/7acfd8ea-fa36-4f4b-8381-b4326ead0044">
</div>

#### 13. Filtre Couleur Personnalisé  | Custom Color Filter
- Sélectionnez un type de filtre et cochez les canaux à modifier.
- Select a filter type and check the channels to modify
  - **Options disponibles** | **Options available:**   
    - Monochrome | - Teinte Couleur | - Amplification  | - Suppression | - Normalisation
    - Monochrome | - Tint Color | - Amplification | - Deletion | - Standardization
<div align="center">
  <img width="500" alt="image" src="https://github.com/user-attachments/assets/02b4c59b-027a-4830-bffe-6ee0f6bbea25">
</div>
