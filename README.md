# PHTI-Dataset
The PHTI is a real dataset developed for the research community, considering the recognition systems' generalization. The overall process includes; the data collection process, image acquisition process, text-line segmentation process, annotation process and detailed statistics of the PHTI dataset. The PHTI dataset is developed to cover many Pashto language genres such as prose, poetry, short story, history, sports, BBC Pashto, and religion. In this context, data were collected from a diverse background of learners having different levels of educational background, including University, College, School, and Deeni Madaras.  Each collected handwritten sample is scanned with 600 DPI using an HP Scanjet scanner. The acquired image is named PHTI-XX-Y-ZZZZ.jpg; PHTI is a constant prefix that refers to our new dataset. The "XX" annotates the source name, and "Y" represents the gender, while "ZZZZ" describes the page number in the respective source. The PHTI images are further segmented into 36, 082 text-line images. After segmentation into text-line images, the notion used for image file names is extended with another number. 

However, each scanned image, as well as an image of a segmented text line, was manually checked and validated regarding its ground truth, and if there was a mismatch or an error, then the image, as well as its annotation, was corrected. However, there might be a ±4 % error in the validation process. The ground truth is stored in a text file with a UTF-8 codec. The file name is the same as the image file name, except the extension. The PHTI dataset consists of, Total of writers 400, Female writers 200, Male writers 200, Total pages 3, 970, Pages per writer 10, Average line per page 10, Total text-lines images 36, 082, Text-line written by females 18,069, Text-line was written by males 18,013, Total words 4, 20, 961, Unique words 33, 330, Total character 169, Minimum height of image 28, Maximum height of image 237, Minimum width of image 78, Maximum width of image 1, 263.

APPLICATIONS OF THE PHTI DATASET:
1.	Natural Language Processing
2.	Gender and Age Classification
3.	Skew and Line Segmentation
4.	OCR Application


The dataset is available under the terms and conditions covered within the license provided by (GNU General Public License v3.0).
