# <p align="center"> SA-C-GENDER-CLASSIFIER </p>
# Algorithm
1. Install the DeepFace library using the command pip install deepface
2. To Predict the gender of a person use this DeepFace library
3. Import the deepface class from DeepFace library, cv2 class from openCv2 library and Matplot library according to the requirements.
4. Load and display the image which we have imported. 
5. Pass the image to DeepFace library and analyze the image to predict gender of a person.
6. This prediction is stored in result variable and print the prediction using this algorithm.

## Program:
```

Developed by   : J .RITHANIEPRIYANKA
RegisterNumber :  212220230039

```

```
!pip install deepface
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt
img1=cv2.imread('anirudh.jpg')
plt.imshow(img1[:,:,::-1])
plt.show()
result=DeepFace.analyze(img1,actions=['gender'])
print("Gender : ",result['gender'])
img2=cv2.imread('n.webp')
plt.imshow(img1[:,:,::-1])
plt.show()
result=DeepFace.analyze(img2,actions=['gender'])
print("Gender : ",result['gender'])
```

## OUTPUT:
![nn-asses-a](https://user-images.githubusercontent.com/75235132/174469357-d856f354-20ab-44fc-bccd-77ededba8d0f.png)

![nn-asses-b](https://user-images.githubusercontent.com/75235132/174469364-1921572d-086d-481c-8d58-8cc6fad92068.png)

DEMO VIDEO YOUTUBE LINK:

https://youtu.be/1-WZr8_JtOE
