# A Hierarchical Factorized Bilinear Fusion based Dual-branch Deep Learning Model for Histopathology Image Classification

This is the official GitHub repository corresponding to the research paper entitled  
**A Hierarchical Factorized Bilinear Fusion based Dual-branch Deep Learning Model for Histopathology Image Classification**.  
The research work is conducted by the authors from the  
**_Department of Computer Science and Engineering, Jadavpur University, India_**.

The proposed framework introduces a dual-branch CNN architecture using  
**EfficientNet-B0** and **MobileNetV3-Large** to extract 
complementary multi-scale  
feature representations from histopathological images. **Hierarchical Factorized Bilinear Fusion (HFBF)** module is employed to model  
higher-order cross-branch feature interactions. The fused representations are further  
enhanced using **Squeeze-and-Excitation (SE) attention** for discriminative  
channel-wise feature recalibration, followed by a regularized fully-connected classifier  
for breast cancer classification.

The attachment below shows the detailed architecture of the proposed methodology.

<h3 align="center">Model Architecture</h3>

<p align="center">
  <img 
    src="https://github.com/user-attachments/assets/d57b11a2-ce54-486f-857e-bc244eb2efe0"
    width="300"
  />
</p>


<h3 align="center">Hierarchical Factorized Bilinear Fusion Module</h3>

<p align="center">
  <img 
    src="https://github.com/user-attachments/assets/501b5423-5d85-4759-a427-219b8f9806e5"
    width="250"
  />
</p>







