# DeepLearning_FinalProject
FruitCategoryDetection


In case of running the model on external images(from google) please follow the below steps: 

- In the attached "test_manual" is having the folder structure the model reads with few google images. 

- Add additional images with respect to the catrgory/folder. 
- Upload folder on-to google colab 
- Once the model is trined and tested add the below commad in the last cell.                    

      "!unzip "/content/test_manual.zip" 
    
- Once unziped change the test folder path in cell [47]  
     
       tstimages, tst_lbls = data("/content/test_manual/*") 

- Reexecute steps from cell [47] till [52] for vizualizing the predicted images. 

- Correct ones are highlighted in BLUE and incorrect ones in RED.
