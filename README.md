# Face-Similarity-Detection

This project enables face verification by comparing two images to determine if they depict the same person. The system leverages advanced facial recognition techniques to deliver accurate results, even in challenging scenarios.

**Key Features:**
- **Identity Verification**: Accurately detects whether the faces in two images belong to the same individual.
- **Robust Edge Case Handling**: Performs reliably for complex cases, such as:
  - Faces with masks or partial occlusions.
  - Side profiles or angular views.
  - Variations in lighting and expressions.
  - Presence among multiple people

DeepFace parameters used for this task:
```Python
DeepFace.verify(img1_path=profilePic, 
                img2_path=myPic, 
                model_name="Facenet512",
                detector_backend="retinaface",
                enforce_detection=False, 
                align=True)
```
Explore the code to see how it tackles real-world face recognition challenges with precision!

![image](https://github.com/user-attachments/assets/294a00d8-52a8-4e37-a191-d245271eb951)


However, doesn't work for low-light setting :(


