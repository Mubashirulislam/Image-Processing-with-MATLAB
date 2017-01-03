# Basic Image Processing Programs

1. #### **Program for reading image from directory/folder and displaying it in the Figure window.**

   ```matlab
   % imread(image path) is a function that reads image from specified URI or current directory.
   % Here the image and matlab source code are present in the same folder.
   a=imread('image1.jpg');
   % imshow() function displays the image stored in object a
   imshow(a);
   ```

   #### **Output:**

   ![Display an Image](E:\GitHub\Image Processing with MATLAB\Display an Image.png)

   ​

   ​


2. #### **Program for reading and displaying multiple images in the Figure window.**

   ```matlab
   % read first image
   a=imread('image1.jpg');
   % subplot(n,m,x) is a function that divides Figure window int nxm blocks.
   % the parameter x is the block number in the given window.
   subplot(1,2,1);
   % display the first image
   imshow(a);
   % itle() function provides a meaningfull name to image
   title('Flower Painting');
   b=imread('image2.jpg');
   subplot(1,2,2)
   imshow(b);
   title('Starry Night Painting');
   ```

   #### Output:

   ![Display Two Images](E:\GitHub\Image Processing with MATLAB\Display Two Images.png)