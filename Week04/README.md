## A basic Transfer Learning Application for X-RAY Images using Google's `InceptionV3` Model

- aim was to train a custom model on the `InceptionV3` model for X-RAY Images of patients having pneumonia
- secondary aim was to evaluate the trained model and provide a few test inferences

## Model Evaluation (`sklearn.metrics.classification_report`)

`
				   precision    recall  f1-score   support

   PNEUMONIA       0.77      	0.67      0.72       390
      NORMAL       0.55      	0.67      0.61       234

    accuracy                           	  0.67       624
   macro avg       0.66      	0.67      0.66       624
weighted avg       0.69      	0.67      0.68       624
`

## Test Inference from the custom trained model

[]("./Sample_Test_Run.png")

## Dataset Download

- For obtaining the original publication of the dataset, follow the accompanying paper DOI at Mendeley: [link](https://data.mendeley.com/datasets/rscbjbr9sj/2)
- If you are just require the dataset, you can directly download the 1.2 GB dataset from here: [link](https://data.mendeley.com/datasets/rscbjbr9sj/2/files/41d542e7-7f91-47f6-9ff2-dd8e5a5a7861/ChestXRay2017.zip)


## Background of the dataset source

[ _...In this study, we sought to develop an effective transfer learning algorithm to process medical images to provide an accurate and timely diagnosis of key pathology in each image..._ ](https://data.mendeley.com/datasets/rscbjbr9sj/2)


## References

- [Anjana Tiha's Project](https://nbviewer.jupyter.org/github/anjanatiha/Pneumonia-Detection-from-Chest-X-Ray-Images-with-Deep-Learning/blob/master/code/Detection%20of%20Pneumonia%20from%20Chest%20X-Ray%20Images%201.0.0.3.ipynb)
- [Unit8's Medium BlogPost](https://medium.com/unit8-machine-learning-publication/detecting-pneumonia-on-x-ray-images-covnets-and-transfer-learning-6d94b58c6657)