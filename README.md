# Computer-Vision
Several filters include Mean, Median, Gaussian, Laplacian, and Sobel.
Preprocess the dataset images using Median, Gaussian filter and Laplacian filters in spatial domain to obtain smooth images.

•	Convert the image from BGR to RGB.

 <img width="468" alt="image" src="https://user-images.githubusercontent.com/108179353/204139512-60220026-36a0-4833-a1ec-62506bac2a1b.png">


•	Apply the Mean filter on the image. The mean filter, the image has now been smoothed out and nuisance has been removed.

 <img width="468" alt="image" src="https://user-images.githubusercontent.com/108179353/204139516-0315fc2e-d1a4-479d-b46e-ded1f27f653c.png">


•	Apply the Gaussian filter on the image.

 <img width="468" alt="image" src="https://user-images.githubusercontent.com/108179353/204139528-f3a5af62-be8b-4101-9c26-258275aec773.png">

•	Apply the Average on the image. There is a significant improvement in the filtered image over the original image, but still, there is noise.

<img width="468" alt="image" src="https://user-images.githubusercontent.com/108179353/204139534-220a13d1-ef9f-4b17-a195-85a2490212fc.png">

 
         
•	The image is converted from RGB to grayscale in OpenCV, then Laplacian and Sobel's filters are applied to highlight edges.

<img width="474" alt="image" src="https://user-images.githubusercontent.com/108179353/204139549-54ec8cfa-d642-4b5f-8d2e-42976b9e9900.png">
