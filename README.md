# DIGITAL-VIETNAMESE-ARTICLE-SUMMARIZATION-USING-TRANSFER-LEARNING
## Introduction
In this task, we collected the ViDN4ABS dataset from some digital Vietnamese newspapers, such as tuoitre.vn, thanhnien.vn, vnexpress.net, vtc.vn, after that we conducted experiments with some models that are said to be capable of abstractive summarizing texts, such as T5, ViT5, Pegasus, Prophetnet, Distilbart, BARTPho, then compared and evaluated the results between these models. Finally, we highlighted some challenges and set out the future development direction for the abstractive summarization task.

## Example of the ViDN4ABS dataset
<img width="850" alt="Example" src="https://github.com/duyngoc-adn/DIGITAL-VIETNAMESE-ARTICLE-SUMMARIZATION-USING-TRANSFER-LEARNING/assets/73750674/ea0e7888-4de1-42c6-b5e7-0d82f0c355b8">

## Some characteristics in the dataset.
<img width="776" alt="Characteristics" src="https://github.com/duyngoc-adn/DIGITAL-VIETNAMESE-ARTICLE-SUMMARIZATION-USING-TRANSFER-LEARNING/assets/73750674/031e8891-988c-41b3-9bb6-13329988bd17">

## Experimental process
![Thiết kế thí nghiệm](https://github.com/duyngoc-adn/DIGITAL-VIETNAMESE-ARTICLE-SUMMARIZATION-USING-TRANSFER-LEARNING/assets/73750674/d3d1ce30-ffd6-4f80-a960-28202392c83a)
In this part, we do it through five steps. First, we collect data from digital newspapers in a variety of fields. Then, processing the raw data because there are some articles that are not useful to the model, which can cause interference that makes the model inferior. After processing the collected raw data, we obtained a dataset of 37,367 rows and two columns, divided into three sets: training set, validation set, and test set in the ratio of 8:1:1. Once we have the datasets, we install models with different versions for the abstractive summarization tasks. 

## The best results of models
<img width="816" alt="Resutls" src="https://github.com/duyngoc-adn/DIGITAL-VIETNAMESE-ARTICLE-SUMMARIZATION-USING-TRANSFER-LEARNING/assets/73750674/c2e96b58-720a-4be9-ac32-bf6fc9cd9fdd">

## Contact
### Authors:
Cao Dinh Duy Ngoc, Do Pham Phuc Tinh, Nguyen Tran Gia The and Nguyen Huu Minh Tam

Faculty of Information Science and Engineering, University of Information Technology, Ho Chi Minh City, Vietnam

Vietnam National University, Ho Chi Minh City, Vietnam

{20521661, 20522020, 20521940, 20521871}@gm.uit.edu.vn
