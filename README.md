🧠 CT Image Segmentation for Intracranial Hemorrhage (ICH) using Transformer-based U-Net
This project presents a deep learning-based approach for accurate segmentation of Intracranial Hemorrhage (ICH) using Computed Tomography (CT) scans. It combines advanced image pre-processing techniques with a SegFormer-based U-Net architecture, significantly improving segmentation performance over conventional models.

---

📌 Background  
Traumatic Brain Injury (TBI) is a leading cause of mortality and disability. In the U.S. alone, around 30% of all injury-related deaths in 2013 were caused by TBI.

When trauma or disease leads to bleeding within the skull, it results in an Intracranial Hemorrhage (ICH)—a condition that demands immediate medical and surgical intervention due to:  
* High mortality rate
* Potential for long-term neurological impairment
* Risk of life-threatening complications

Challenges in ICH Detection:  
* High morphological and size variation
* Varying severity levels
* Smaller hemorrhages often go undetected in fast-paced healthcare settings

Despite the availability of advanced neuroimaging modalities, CT remains the gold standard for ICH diagnosis because of:  
* Wide availability
* Speed and efficiency in emergency settings
* Capability for time-sensitive decision-making and surgical planning

---

🎯 Project Objective  
The goal of this project is to automatically segment different types of ICH using a deep learning-based model trained on CT scans. This enables faster and more accurate diagnosis, especially in high-throughput clinical environments.

---

✅ Pre-processing Techniques:  
* Brain windowing
* Skull-stripping
* Image inversion

These methods enhance the visibility of hemorrhages for better segmentation performance.


🧠 Model:

* A Transformer-based U-Net model based on SegFormer architecture
* Trained and tested on the PhysioNet dataset

---

🚀 Key Contributions

* Developed an advanced transformer based UNet model called SegFormer based UNet for ICH Segmentation using CT scans.
* Outperformed U-Net, U-Net++, and other UNet variants on the PhysioNet dataset.
* Achieved:
  * Dice Similarity Coefficient (DSC): 86.80%
  * Intersection over Union (IoU): 85.90%

---

🛠️ Dependencies

* Python
* PyTorch
* NumPy
* Matplotlib

---

## Dataset
[Physionet](https://physionet.org/content/ct-ich/1.3.1/)
