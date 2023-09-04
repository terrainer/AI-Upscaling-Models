DUE TO GITHUB'S FILE SIZE LIMIT, PLEASE USE THE GOOGLE DRIVE LINK TO DOWNLOAD THE MODEL_G FILE  

**Name:** 1xFrankenfixer_SRFormerLight  
**License:** CC BY-SA  
**Link:** [Google Drive](https://drive.google.com/drive/folders/1ZAcnZAVkgBitHzzwpGWBREpfm9hPznQJ?usp=drive_link)  
**Model Architecture:** SRFormer_light  
**Scale:** 1x  
**Purpose:** Upscaling Artifact Reduction, Tone & Detail Enhancement  

**Iterations:** 190K  
**batch_size:** 12  
**HR_size:** 64  
**Epoch:** 28  
**Dataset:** FrankendataV2 (Upscaled LR)  
**Dataset_size:** 78,951 512x512 tiles  
**OTF Training:** No  
**Pretrained_Model_G:** 4xFrankendataPretrainer_SRFormer400K_g.pth  
**Pretrained_Model_D:** 4xFrankendataPretrainer_SRFormer400K_d.pth  

**Description:** A 1x model designed to reduce artifacts and restore detail to images upscaled by 4xFrankendata_FullDegradation_SRFormer  
