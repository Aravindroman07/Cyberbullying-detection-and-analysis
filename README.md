# Cyberbullying-detection-and-analysis

<!--Title of the Project-->
"Developing a cyberbullying detection and analysis system using a Random Forest classifier and deploying it as a web application."
## About
<!--Detailed Description about the project-->
The project revolves around the development of a cyberbullying detection and analysis system. The core methodology involves utilizing a Random Forest classifier, a machine learning algorithm known for its adaptability to high-dimensional data. The primary objective is to deploy this system on the web, facilitating real-time monitoring and analysis of online interactions on platforms like Twitter. The process begins with data preprocessing, where textual content, such as tweets, undergoes cleaning and transformation to extract relevant features. These features are then fed into the Random Forest classifier, which has been trained on a meticulously labeled dataset to recognize patterns indicative of cyberbullying behavior. The system's architecture includes provisions for continuous monitoring of incoming data streams, enabling swift identification and classification of potential cyberbullying instances. Additionally, ethical considerations are paramount throughout the project, with measures in place to address bias and ensure responsible AI practices. Overall, the project aims to provide a proactive and adaptive solution to address the pervasive issue of cyberbullying in online communication platforms.

## Features
<!--List the features of the project as shown below-->
1. Text Preprocessing: Involves cleaning and transforming textual data, such as tweets, to remove noise, punctuation, and special characters, ensuring uniformity and consistency in the dataset.
   
2. Profanity Detection: Identifies and flags offensive language and swear words commonly associated with cyberbullying, enhancing the model's ability to detect explicit instances of harassment.
   
3. Context Analysis: Analyzes the context surrounding the text to understand the subtleties and nuances of language, helping the model differentiate between sarcastic remarks, jokes, and genuine threats.

4. TF-IDF (Term Frequency-Inverse Document Frequency): Calculates the importance of words in a document relative to their occurrence in the entire corpus, allowing the model to prioritize significant keywords and phrases in cyberbullying detection.

5. Random Forest Classifier: Utilizes an ensemble learning technique to build multiple decision trees and aggregate their predictions, providing robustness and adaptability to high-dimensional data, making it suitable for cyberbullying detection.

6. Real-time Monitoring: Incorporates features to continuously assess newly posted content on social media platforms, enabling swift identification and classification of potential cyberbullying instances as they occur.

7. Twitter API Integration: Utilizes the Twitter API to access and retrieve data from the platform, facilitating data collection, monitoring, and analysis in real-time.

8. Ethical Considerations: Incorporates measures to address bias, fairness, and transparency in the model's decision-making process, ensuring responsible AI practices and mitigating potential harm.

## Requirements
<!--List the requirements of the project as shown below-->
* **Operating System:** The product will be operating in both Windows and Linux environments, requiring compatibility with Windows 10 and Windows 11 for optimal performance.
* **Web Browser Compatibility:** Most of the features will be compatible with the latest version of Mozilla Firefox and Google Chrome web browsers.
* **Stable Internet Connection:** A stable internet connection is required for this product to run effectively, ensuring seamless access to online resources and real-time data processing.

### Design and Implementation Constraints

* The System needs a minimum of 8 GB RAM with Windows 10 Operating System.
  
### Hardware Requirements

* **RAM:** A minimum of 8 GB RAM is required to ensure smooth operation of the system.
* **CPU:** The system supports processors clocked at 2 GHz or faster for efficient processing of data and tasks.
* **Architecture:** Both 32-bit and 64-bit architectures are supported for hardware configuration flexibility.

### System Requirements

* **Operating System:** Windows 10 / Windows 11.
* **Coding Language:** Python.
* **IDE:** Google Colab.
## System Architecture
<!--Embed the system architecture diagram as shown below-->

![image](https://github.com/Aravindroman07/Cyberbullying-detection-and-analysis/assets/112415113/0f291dcf-9368-4025-9812-379f9eba1574)


## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 -Sentiment level Chart

![image](https://github.com/Aravindroman07/Cyberbullying-detection-and-analysis/assets/112415113/be49f375-4fbd-426a-a324-7606ff8f4ac7)

#### Output2 - Word Classification charts
![image](https://github.com/Aravindroman07/Cyberbullying-detection-and-analysis/assets/112415113/00cc7ca8-4211-49a9-8724-1ed3fc88b416)

#### Output3 - Pie Chart
![image](https://github.com/Aravindroman07/Cyberbullying-detection-and-analysis/assets/112415113/cf33095d-8e30-487b-a289-12239d3900f6)

#### Output4- Output Screen of website using Steamlit
![image](https://github.com/Aravindroman07/Cyberbullying-detection-and-analysis/assets/112415113/0ebc8260-183f-4a25-80c5-c25dfa3290df)



Detection Accuracy: 96.713%


## Results and Impact
## Results and Impact
<!--Give the results and impact as shown below-->
The Cyberbullying Detection and Analysis System significantly contributes to the proactive identification and mitigation of online harassment, fostering a safer and more supportive online environment. By leveraging the Random Forest classifier, the system achieves high accuracy in detecting instances of cyberbullying on Twitter, empowering users and moderators to take timely action against abusive behavior.

This project's implementation of the Random Forest classifier offers several advantages, including robustness against noise and flexibility in handling high-dimensional data. Additionally, the system's deployment as a web application ensures accessibility and ease of use for both individuals and organizations seeking to address cyberbullying effectively.

The Cyberbullying Detection and Analysis System represents a crucial step towards combating online harassment and promoting digital well-being. Its impact extends beyond the realm of social media, contributing to broader conversations about online safety and responsible digital citizenship. Through ongoing evaluation and refinement, this project sets the stage for continued advancements in cyberbullying prevention and intervention strategies.

## Articles published
1.	Fortuna P, Nunes S. A survey on automatic detection of hate speech in text. ACM Comput Surv. 2018;51:7. https://doi.org/10.1145/3232676.
2.	Finogeev E, Kaprielova M, Chashchin A, Grashchenkov K, Gorbachev G, Bakhteev O. Hate speech spreader detection using contextualized word embeddings. CLEF; 2021.
3.	Hüsünbeyi Z, Akar D, Özgür A. Identifying Hate Speech Using Neural Networks and Discourse Analysis Techniques. In: Proceedings of the first workshop on language technology and resources for a fair, inclusive, and safe society within the 13th language resources and evaluation conference; 2022. p. 32–41.
4.	Nockleby J, Levy L, Karst K, Mahoney D. Encyclopedia of the American constitution. Detroit: Macmillan Reference; 2000.
5.	Ababu T, Woldeyohannis M. Afaan Oromo hate speech detection and classification on social media. In: Proceedings of the thirteenth language resources and evaluation con-ference; 2022. p. 6612–9.



