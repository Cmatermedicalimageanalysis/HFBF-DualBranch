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
![Model Architecture]<img width="1818" height="2253" alt="Model_diagram_updated_latest drawio(1)" src="https://github.com/user-attachments/assets/d57b11a2-ce54-486f-857e-bc244eb2efe0" />

