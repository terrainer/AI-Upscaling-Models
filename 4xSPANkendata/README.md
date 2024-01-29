**Name:** 4xSPANkendata   
**License:** CC BY-SA  
**Link:** [Github[(https://github.com/terrainer/AI-Upscaling-Models/tree/main/4xSPANkendata)    
**Model Architecture:** SPAN
**Scale:** 4x  
**Purpose:** Intended as a pretrain model, can be used to upscale undegraded photos.  

**Iterations:** 500k, fine-tuned with 120k, then 110k, then 75k  
**batch_size:** 32, 16, 12, 10  
**HR_size:** 192, 256, 320, 192  
**Epoch:** Unknown, 32, 20, 12  
**Dataset:** My own custom dataset, made from an amalgamation of other datasets, as well as images I sourced myself.  
**Dataset_size:** 58,420 512x512 tiles, downscaled with a variety of traditional algorithms and [CAR](https://github.com/sunwj/CAR)  
**OTF Training:** No  
**Pretrained_Model_G:** N/A  

**Description:** 4x realistic upscaler that may also work for general purpose usage. Trained on Bicubic downscaled tiles from very high quality images.  
