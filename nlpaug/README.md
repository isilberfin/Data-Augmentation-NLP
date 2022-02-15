# NLPAUG library
 **nlpaug** is a library for textual augmentation in machine learning experiments. The goal is improving deep learning model performance by generating textual data. It also able to generate adversarial examples to prevent adversarial attacks.
### Augmentation in this folder will consist of 3 categories:
 * character based 
 * word based
 * sentence based
 
 *Character based augmentation* techniques can be categorized as : 
 - ocr augmentation
 - keyboard augmentation
 - random augmentation (insert,swap,substitute)
Character based augmentations in my project is implemented on 4 datasets which are reddit, sarcasm, food and a sentiment analysis data from kaggle. 
%0 represents the original model score with 0 augmentation, while %25-%50-%75-%100 represents number of augmentations that is implemented. 
Note that the model I used is just a spesific sentiment analysis model.

![image](https://user-images.githubusercontent.com/75527090/154101685-326fab2f-c0cf-4be0-8cf4-d308358708df.png)
