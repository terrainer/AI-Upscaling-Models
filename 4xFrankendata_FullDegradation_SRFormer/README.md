**_DUE TO GITHUB'S FILE SIZE LIMIT, PLEASE USE THE GOOGLE DRIVE LINK TO DOWNLOAD THE MODEL_G FILE_**

**Name:** 4xFrankendata_FullDegradation_SRFormer  
**License:** CC BY-SA  
**Link:** [Google Drive](https://drive.google.com/drive/folders/15oWLBn0RbO8jBRCr_jm4x8Cpb5LcARIE?usp=drive_link)  
**Model Architecture:** SRFormer  
**Scale:** 4x  
**Purpose:** A 4x upscaling model for upscaling of noisy, blurry, and artifacted realistic images (and possibly general purpose).  

**Iterations:** 460K  
**batch_size:** 4  
**HR_size:** 192  
**Epoch:** 10  
**Dataset:** My own custom dataset, made from an amalgamation of other datasets, as well as images I sourced myself.  
**Dataset_size:** 122,065 512x512 tiles  
**OTF Training:** Yes  
**Pretrained_Model_G:** 4xFrankendataPretrainer_SRFormer400K_g.pth  
**Pretrained_Model_D:** 4xFrankendataPretrainer_SRFormer400K_d.pth  

**Description:** 4x realistic upscaler that may also work for general purpose usage. It was trained with OTF random degradation with a very low to very high range of degradations, including blur, noise, and compression. Trained with the same Frankendata dataset that I used for the pretrain model.  
