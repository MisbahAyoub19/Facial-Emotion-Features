Start with **Main** File

**Main: It is connected with frame2 and Roiv2_LDA.
      *roiv2 has a strategy to extract features, and frame2 processes these features into a file. This file also handles frame processing. If you want to apply any augmentation techniques, you can use this.

**After obtaining the results and feature extraction, including eyeblinking detection:
    **Apply delta processing to get delta values of features.
    **Use annotation to obtain the annotations.
    **Apply classification using CNN and gradient boosting.
    
*The feature extraction method not only extracts the features of eyebrows and eyes but also detects eyeblinking.

*You can add your own methodology and feature parameters to extract by editing the roi_v2 files.

******************************Cite *****************************************

Lightweight Eyebrow Movement Facial Expression Analysis Using Optimized Lacrimal Distance Analysis Features
Misbah Ayoub, Andrew Abel, Haiyang Zhang, Muhammad Saddam Khokhar


*** Continuous Valence-Arousal Space Prediction and Recognition Based on Feature Fusion. 
Ayoub, M., Zhang, H., & Abel, A. (2024, March), In 2024 IEEE International Conference on Industrial Technology (ICIT) (pp. 1-6). IEEE.

*** Optimization of Lacrimal Aspect Ratio for Explainable Eye Blinking. 
Ayoub, M., Abel, A., & Zhang, H. (2023, September). In Intelligent Systems Conference (pp. 175-192). Cham: Springer Nature Switzerland.

***  Efficient Face Re-Identification through PSO Based Adaptive Deep Learning Models. 
 Ayub, M. (2021).Journal of Independent Studies and Research Computing, 19(2).
  
*** A dynamic emotion recognition system based on convolutional feature extraction and recurrent neural network.  Yin, Y., Ayoub, M., Abel, A., & Zhang, H. (2022, September). In Proceedings of SAI Intelligent Systems Conference (pp. 134-154). Cham: Springer 
   International Publishing.
   Data Driven Processing Via Two-Dimensional Spearman Correlation Analysis (2D-SCA).
   Khokhar, M. S., Cheng, K., Ayoub, M., & Rub, N. E. (2019, December). . In 2019 13th International Conference on Mathematics, Actuarial Science, Computer Science and Statistics (MACS) (pp. 1-7). IEEE.

*** Nonlinear dimensionality reduction in robot vision for industrial monitoring process via deep three dimensional Spearman correlation analysis (D3D-SCA).
Cheng, K., Khokhar, M. S., Ayoub, M., & Jamali, Z. (2021). . Multimedia Tools and Applications, 80, 5997-6017.








**************************************Abstract********************************************************** 
Nowadays, facial expression identification often cannot rely on observing the full face due to limited visibility, particularly with the rise of facial masks post-Covid. Recent studies has pay attention to the identification of up-
per facial expressions, with more focus on analysis of eyes. Little work has been done based on eyebrows, which play a significant role in upper facial expressions. In this paper, we propose a new method to analyse
the eyebrow movement for upper facial expressions, called Lacrimal Distance Analysis (LDA). LDA is not only lightweight and easy to interpret but also effectively processes high-quality datasets efficiently and accurately.
Feature fusion has also been applied in conjunction with the Lacrimal as pect ratio approach for eye movement, resulting not only in enhanced accuracy but also in the inclusion of blink and partial blink counts. Two
widely used datasets, ADFES and OULU-CASIA-VIS and NIR, are utilized to extract features. We achieved an accuracy of 91% with Gradient Boost and 70% accuracy with feed forward network methods, demonstrat-
ing the interpretability, explainability and reliability of our proposed feature extraction method. Eyebrow analysis offers significant advantages in a wide range of fields, including human psychology, human behavior, digital
learning and the metaverse, and the future study of characters.TIn order to support future development and the replicability of results, the source code of the proposed model is available on the following GitHub repository:
https://github.com/MisbahAyoub19/Facial-Emotion-Features.


**Advantages of Eyebrow Movement **
Recognizing eyebrows has several advantages:
1. Recognizing eyebrows in emotion recognition significantly enhances the accuracy and context of interpreting emotions, as they convey critical subtleties and complement other facial features .
2. This improves real-time applications, such as human-computer inter action and robotics , making interactions more responsive and empathetic.
3. Eyebrow recognition also adds cultural sensitivity, as eyebrow expressions hold cultural significance , and aids in non-verbal communication where verbal cues are absent.
4. Additionally, it helps detect mixed emotions and ensures robustness in scenarios where parts of the face are occluded , such as when wearing masks.

 
 Further, eyebrow analysis offers significant benefits across multiple domains. In human psychology, it enhances our understanding of emotional expressions as eyebrows are the key indicators of emotions like surprise, anger, and
confusion. It helps helping psychologists to aid in more effective therapeutic approaches.
For human behavior, it provides insights into non-verbal communication, social interactions, and underlying emotions .This understanding can be  applied in various fields, such as marketing, where understanding consumer
emotions is crucial . In digital learning and the metaverse, eyebrow recognition improves user engagement and interaction by making avatars and virtual teachers more responsive and emotionally expressive, leading to better learning outcomes

Additionally, in the future study of characters in animation, gaming, and virtual reality, it allows for the creation of more realistic and relatable characters, enriching storytelling and audience engagement .



