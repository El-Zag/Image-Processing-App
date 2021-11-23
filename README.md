### **Image Processing Application in JavaFX**

**Autors :** Eloïse Zaghrini, Amandine Bouguessa, Armelle Coutaux

This application can modify an image .png or .jpg with different options, and export the result as a .png .
Each operation can be carried out successively

Note : Seam carving doesn't work on .png without backgrounds ! 

All the options available : 

- **Image Cropping**

In this feature, the user can crop the image left, right, top or bottom, using sliders.
The values ​​given to the left / top sliders are the number of pixels that will be cropped on the left / top of the image.
The size of the image (width / height) minus the values ​​given to the right / bottom sliders are the number of pixels to crop right / bottom.

Choose the desired size then press "Image processing".

- **Scaling**

In this feature, the image is scalled to the desired size while retaining its entirety.

Choose the desired width and height and press "Image processing".

- **Seam Carving**

In this feature, the user can resize his image using the Seam Carving feature, decreasing its dimensions or increasing them. SeamCarving is based on the calculation of the energies of the pixels of the image (in standard 1 or 2 at the choice of the user), and then on the removal / duplication of the pixel seams having the lowest energy. This processing makes it possible to resize the image while keeping as much information as possible!

Choose the desired width and height and press "Image processing".

- **Drawing Interface**

Allows you to draw on the image.
Choose the desired color using the three sliders Blue / Red / Green (dynamic visualization in the color rectangle) and choose the desired brush thickness.

- **Undo/Redo**

Made a mistake ? No problem ! Go back to your previous actions, you can also go back to the following action.
