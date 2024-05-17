# Computer Vision & Image Processing Desktop Application

## Description

Welcome to our Image Processing Desktop Application! This application offers a comprehensive set of tools and features for performing various image processing tasks, making it an indispensable tool for professionals and enthusiasts alike. Whether you're a seasoned image processing expert or just getting started, our app provides an intuitive interface and powerful functionality to meet your needs.

With our desktop application, users can effortlessly load images, apply a wide range of image processing techniques, visualize the results in real-time, and save the processed images with ease. From basic operations like converting images to grayscale and binary formats to advanced features such as edge detection and object recognition, our app empowers users to explore and manipulate images in creative and innovative ways.

## Features


- **Noise Generation:**
  - Generate and apply different types of noise, including Gaussian, Uniform, and Salt & Pepper noise, to images.

   |         Uniform Noise          |         Guassian Noise          |        Salt & Pepper Noise         |
   | :----------------------------: | :-----------------------------: | :--------------------------------: |
   | ![image](https://github.com/AliBadran716/Image-Processing-Kit/assets/102072821/edc4b200-7661-44d5-9a39-9093dd790be9) | ![image](https://github.com/AliBadran716/Image-Processing-Kit/assets/102072821/06186323-5356-449c-90a1-6b2654608569) | ![image](https://github.com/AliBadran716/Image-Processing-Kit/assets/102072821/1b7c4065-fa39-476e-9eb7-a7b471c71df4) |

- **Image Filtering:**
  - Apply various filters including Average, Gaussian, and Median filters to enhance image quality and reduce noise.
    
   |         Average Filter          |         Gaussian Filter          |         Median Filter          |
   | :-----------------------------: | :------------------------------: | :----------------------------: |
   |![image](https://github.com/AliBadran716/Image-Processing-Kit/assets/102072821/628bfe27-0a13-481f-8c66-cb6691f95ab2) | ![image](https://github.com/AliBadran716/Image-Processing-Kit/assets/102072821/aac63a83-8945-4a3a-968d-0a4b142b503f) | ![image](https://github.com/AliBadran716/Image-Processing-Kit/assets/102072821/e84e2022-6643-43f7-999d-d48840e691e7) |

- **Histogram Visualization and Equalization:**
  - Visualize histograms and distribution curves of images to understand their pixel intensity distribution.
  - Perform histogram equalization and normalization to enhance image contrast and improve overall appearance.

   | Histogram | Normalization | Equalization |  
   | :----------------------------: | :-----------------------------: | :-----------------------------: |
   | ![image](https://github.com/AliBadran716/Image-Processing-Kit/assets/102072821/e8d448b1-568b-45da-8f08-10e3e6227c95) | ![image](https://github.com/AliBadran716/Image-Processing-Kit/assets/102072821/2e65594b-dbbd-49e2-a39d-d1c8b7ba399e) | ![image](https://github.com/AliBadran716/Image-Processing-Kit/assets/102072821/56b805a4-a3f1-4c2b-8541-560d7b74eacd) |

- **Thresholding Techniques:**
  - Apply various thresholding techniques, including Global and Local Thresholding, to segment images and extract important features.
 
   | Local | Global |  
   | :----------------------------: | :-----------------------------: |
   | ![image](https://github.com/AliBadran716/Image-Processing-Kit/assets/102072821/6dfbd4b6-fd28-4283-8225-2994f72b5c22) | ![image](https://github.com/AliBadran716/Image-Processing-Kit/assets/102072821/6fd38aeb-7e1e-48c5-807c-73335d4d2241) |

- **Frequency Domain Filters:**
  - Apply frequency domain filters such as Low Pass and High Pass filters to manipulate image frequency components for image enhancement and noise reduction.
  - Create hybrid images by combining two images in the frequency domain to create visually appealing compositions.
    
   | High pass | Low pass |  
   | :----------------------------: | :-----------------------------: |
   | ![image](https://github.com/AliBadran716/Image-Processing-Kit/assets/102072821/1c1f3014-25f1-4404-8417-86c475d6f219) ![image](https://github.com/AliBadran716/Image-Processing-Kit/assets/102072821/42069143-8af4-41a1-bbd2-9793ec1d119c) | ![image](https://github.com/AliBadran716/Image-Processing-Kit/assets/102072821/3ca9baf9-19e1-42ea-a427-975f5bfd435d) ![image](https://github.com/AliBadran716/Image-Processing-Kit/assets/102072821/abe2cfb2-aebd-4aa3-a2c1-14a119fa46c0) |

    
 
  
- **Edge Detection:**
  - Utilize edge detection algorithms such as Sobel, Perwitt, Robert, and Canny for detecting edges and contours in images.
    
   | Sobel | Roberts | Perwitt | Canny |
   | :----------------------------: | :-----------------------------: | :--------------------------------: | :--------------------------------: |
   |  |  | |  |


- **Hough Transform:**
  - Detect lines, circles, and ellipses in images using the Hough Transform method for robust shape detection and recognition.
 
   | Line | Circle | Ellipse |  
   | :----------------------------: | :-----------------------------: | :-----------------------------: |
   |  |  |  |

- **Active Contour:**
  - Use active contour models (also known as snakes) to detect and track object boundaries in images.
  - Allow users to select an initial contour or region of interest (ROI) in the image.
  - Tune parameters such as alpha, beta, gamma, and iterations to control the behavior and convergence of the active contour algorithm.
  - Enable real-time visualization of the active contour evolution and final segmentation result.

   | Example 1 | Example 2 |  
   | :----------------------------: | :-----------------------------: |
   | | |

- **Feature Detection:**
  - Detect image features using methods like Harris Corner Detector and Lambda Corner Detector for point feature extraction.
  - Perform image matching and template matching to identify similarities and patterns in images.
    
   | Harris | Lambda |  
   | :----------------------------: | :-----------------------------: |
   |  | |

- **Feature Matching:**
  
   | Square Sum of Differences method | Cross-Correlation Method |  
   | :----------------------------: | :-----------------------------: |
   | | |

  
- **SIFT Descriptors:**
  - Utilize Scale-Invariant Feature Transform (SIFT) descriptors to detect and describe key points in images.
  - Compute keypoint matching between images for image registration and alignment tasks.

    <p align="center">
     <img src="img" />
   </p>

- **Thresholding Segmentation:**
  - Apply advanced thresholding segmentation techniques, including Otsu, Spectral, Optimum local, and global thresholding, to segment images into distinct regions and objects.
    
   | Local Otsu | Local Spectral | Local Optimum |  
   | :----------------------------: | :-----------------------------: | :-----------------------------: |
   |  |  |  |

   | Global Otsu | Global Spectral | Global Optimum |  
   | :----------------------------: | :-----------------------------: | :-----------------------------: |
   |  |  |  |

- **RGB Image Segmentation:**
  - Segment RGB images using K-means clustering, mean shift clustering, Agglomerative Segmentation, and Region Growing methods for semantic segmentation and object detection tasks.

    | K-Means Segmentation | Mean Shift Segmentation |
    | :----------------------------: | :-----------------------------: |
    | img |img |

    | Agglomerative Segmentation |         Region Growing          |
    | :------------------------: | :-----------------------------: |
    |  img  | img |

## Summary

Our Image Processing Desktop Application offers a comprehensive suite of features and tools for image manipulation, analysis, and enhancement. With its intuitive interface and powerful functionality, users can explore the world of digital imagery with ease and efficiency. Whether you're a professional photographer, researcher, or hobbyist, our app provides the tools you need to unleash your creativity and achieve stunning results.

## How to Run the Program

To run the Image Processing Desktop Application, follow these simple steps:

1. Clone or download the repository to your local machine.
2. Install the necessary dependencies using `pip install -r requirements.txt`.
3. Launch the application by running `python main.py` from the terminal or command prompt.
4. Explore the various features and tools available in the application's graphical user interface (GUI).
5. Load images, apply image processing techniques, visualize the results, and save the processed images as needed.
6. Enjoy the power and versatility of our Image Processing Desktop Application!

   ## Contributors <a name = "Contributors"></a>

<table>
  <tr>
    <td align="center">
    <a href="https://github.com/Muhannad159" target="_black">
    <img src="https://avatars.githubusercontent.com/u/104541242?v=4" width="150px;" alt="Muhannad Abdallah"/>
    <br />
    <sub><b>Muhannad Abdallah</b></sub></a>
    </td>
  <td align="center">
    <a href="https://github.com/AliBadran716" target="_black">
    <img src="https://avatars.githubusercontent.com/u/102072821?v=4" width="150px;" alt="Ali Badran"/>
    <br />
    <sub><b>Ali Badran</b></sub></a>
    </td>
     <td align="center">
    <a href="https://github.com/ahmedalii3" target="_black">
    <img src="https://avatars.githubusercontent.com/u/110257687?v=4" width="150px;" alt="Ahmed Ali"/>
    <br />
    <sub><b>Ahmed Ali</b></sub></a>
    </td>
<td align="center">
    <a href="https://github.com/ossama971" target="_black">
    <img src="https://avatars.githubusercontent.com/u/40814982?v=4" width="150px;" alt="Hassan Hussein"/>
    <br />
    <sub><b>Osama Badawi</b></sub></a>
    </td>
      </tr>
 </table>



