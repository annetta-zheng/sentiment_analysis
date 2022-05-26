# Automatical Reviews Analyzer 
### Objective
1. Implement and compare three types of linear classifiers: the perceptron algorithm, the average perceptron algorithm, and the Pegasos algorithm.
2. Use your classifiers on the food review dataset, using some simple text features.
3. Experiment with additional features and explore their impact on classifier performance.

### Documents
* project1.py - various functions for algorithms.
* main.py - a script where these functions are called.
* utils.py - contains utility functions.
* test.py - a script which runs tests.


![Figure_1](https://user-images.githubusercontent.com/67286396/170518149-3466c443-28c8-4d92-9143-e035f0b80693.png)
![Figure_2](https://user-images.githubusercontent.com/67286396/170518161-982e851b-029d-4f62-9bcf-063d13d28678.png)
![Figure_3](https://user-images.githubusercontent.com/67286396/170518177-7e79f480-c7b1-4b71-a1fa-80f274d6c501.png)

### Results
Accuracy on the test set using the original dictionary: 80.20%
Accuracy on the test set using the dictionary with stop words removed: 80.80%

For the perceptron algorithm: best combination of T = 25, with validation accuracy = 79.40%
![Figure_4](https://user-images.githubusercontent.com/67286396/170519190-2d1c8fb1-4c49-4dd1-a3b9-6c594bce2842.png)

For the average perceptron algorithm: best combination of T = 25, with validation accuracy = 80.00%
![Figure_5](https://user-images.githubusercontent.com/67286396/170519252-46f6b01b-04f5-49e2-ae0c-9fe2f4b33f7f.png)

For the pegasos algorithm: best combination of T = 25 \lambda = 0.01, with validation accuracy = 80.60%
![Figure_6](https://user-images.githubusercontent.com/67286396/170519444-18c2d7d5-2fbd-47d2-a296-e35c39b1bf3d.png)
![Figure_7](https://user-images.githubusercontent.com/67286396/170519453-ef692e96-dd75-4c04-a340-a28d0762a820.png)
