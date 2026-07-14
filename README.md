# Toyota Logo CAD Keychain Project

This repository contains the CAD design files, dimensions, and documentation for the **Toyota Logo Keychain Project** created using **Onshape**. The project demonstrates the application of geometric design principles, sketching, dimensioning, constraint mapping, and 3D extrusion to create a 3D-printable keychain.

---

## 🔗 Project Links
* **Onshape CAD Design:** [Toyota Logo CAD Document](https://cad.onshape.com/documents/52780d6407956d0433a75062/w/13a7d1fc871c38a3ac38b50a/e/3bbc24773589ce6604c84f00?renderMode=0&uiState=6a564e12702405fa0315bf2c)
* **Design File Format:** `.STL` (Ready for 3D Printing)

---

## 📐 Dimensions & CAD Sketch Reference

The model was created with a series of proportional, concentric ellipses representing the classic Toyota emblem. To make the emblem functional as a keychain, a keyring attachment hole was integrated at the top.

### 1. Main Emblem Sketch Dimensions
* **Outer Horizontal Ellipse:** 70 mm x 42 mm
* **Inner Horizontal Ellipse:** 58 mm x 35 mm
* **Outer Vertical Ellipse:** 27 mm x 42 mm
* **Inner Vertical Ellipse:** 20 mm x 30 mm
* **Outer Upper Ellipse:** 50 mm x 20 mm
* **Inner Upper Ellipse:** 39 mm x 13 mm

### 2. Keyring Hole Attachment Dimensions
* **Hole Diameter:** 2.912 mm
* **Hole Center Offset from Origin:** 19.814 mm (Aligned vertically using vertical constraints)

---

## 🛠️ Design Steps (How it was made)

### Step 1: Base Ellipses Sketching
1. Started a new sketch on the **Top Plane**.
2. Placed the central horizontal and vertical ellipses at the coordinate origin (0,0) using the **Ellipse tool**.
3. Fully defined all major and minor axes using the **Dimension tool** (D) to ensure no floating geometry.

### Step 2: Upper Ellipses & Vertical Constraints
1. Created the upper horizontal ellipses slightly offset vertically from the center coordinate.
2. Aligned the center points of the ellipses using a **Vertical Constraint** with the origin to keep the emblem symmetric.
3. Defined their respective dimensions to complete the core emblem.

### Step 3: Integrating the Keychain Hole
1. Sketched a small circle near the top edge of the outer horizontal ellipse.
2. Tied its center point to the vertical axis of the emblem using a **Vertical Constraint**.
3. Set the hole diameter to 2.912 mm and the distance from the origin to 19.814 mm.

### Step 4: Trimming and Merging Geometry
1. Utilized the **Trim tool** (M) to cut intersecting overlapping lines between the internal ellipses.
2. This merged the overlapping paths into a single, continuous unified area, preventing floating unconnected segments during 3D printing.

### Step 5: Extrusion (Extrude)
1. Ended the sketch and opened the **Extrude tool** (Shift + E).
2. Selected the unified closed loop of the Toyota logo.
3. Set the extrusion depth to **2 mm** to create a slim, lightweight, yet sturdy physical keychain.
4. Exported the final model as an **STL** file with a **Millimeter** unit scale.

---

## 📂 Project Assets

*Below are the design stages captured during development:*

| Stage 1: Initial Base Ellipses Dimensions | Stage 2: Full Emblem Dimensions & Alignment |
| :---: | :---: |
| ![Stage 1](https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPO_NAME/main/images/image_a4d1e9.png) | ![Stage 2](https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPO_NAME/main/images/image_a4d243.png) |

| Stage 3: Keychain Hole Coordinates | Stage 4: Completed 3D Design Profile |
| :---: | :---: |
| ![Stage 3](https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPO_NAME/main/images/image_a4d551.png) | ![Stage 4](https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPO_NAME/main/images/image_a4d5c5.png) |
