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

Final output:

![image](https://github.com/user-attachments/assets/5bf3a220-a0fe-4396-a97c-282378183295)

Presence among multiple people:

![image](https://github.com/user-attachments/assets/5e6a4619-b283-4705-adce-878b06d68152)


