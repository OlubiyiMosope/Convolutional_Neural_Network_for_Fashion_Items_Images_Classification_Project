# Convolutional_Neural_Network_for_Fashion_Items_Images_Classification_Project
This is a project where CNNs are employed to automatically identify and categorize fashion item products on an online fashion store by attaching labels and sub-labels to each of the images of the products uploaded to the site.

---
General Dataset Description:

- The dataset consists of images of only the fashion items, against a consistent background.
- The images are all coloured. (Will have 3 dimensions when converted to tensors).
- Each image has a dimension of 300x400 pixels, but scaled down to 90x120.
- There are approximately 16,000 images in total.
- The images are split into 3 main categories: Glasses and Sunglasses, Trousers and Jeans, and Shoes.
- Every category has additional subclasses based on gender and product type:
	1. Glasses and Sunglasses (2): 'optical glasses', 'sunglasses'.
	2. Trousers and Jeans (4): 'Trousers Male', 'Jeans Male', 'Trousers Female', 'Jeans Female'.
	3. Shoes (11): 'Boots  Male', 'Trainers/Sneakers Male', 'Sandals/Flip flops/Slippers Male', 'Formal Shoes Male', 'Others Male'.
		    'Boots Female', 'Trainers/Sneakers Female', 'Ballerina shoes Female', 'High heels Female', 'Sandals/Flip flops/Slippers Female', 'Others Female'.

The objective is to return all labels associated with a given image i.e its main category and its respective sub-category.
