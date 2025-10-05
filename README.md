# Smart India Hackathon Workshop
# Date:30.09.2025
## Register Number:25007184
## Name:sachin jm
## Problem Title
SIH 25010: Smart Crop Advisory System for Small and Marginal Farmers
## Problem Description
A majority of small and marginal farmers in India rely on traditional knowledge, local shopkeepers, or guesswork for crop selection, pest control, and fertilizer use. They lack access to personalized, real-time advisory services that account for soil type, weather conditions, and crop history. This often leads to poor yield, excessive input costs, and environmental degradation due to overuse of chemicals. Language barriers, low digital literacy, and absence of localized tools further limit their access to modern agri-tech resources.

Impact / Why this problem needs to be solved

Helping small farmers make informed decisions can significantly increase productivity, reduce costs, and improve livelihoods. It also contributes to sustainable farming practices, food security, and environmental conservation. A smart advisory solution can empower farmers with scientific insights in their native language and reduce dependency on unreliable third-party advice.

Expected Outcomes

• A multilingual, AI-based mobile app or chatbot that provides real-time, location-specific crop advisory.
• Soil health recommendations and fertilizer guidance.
• Weather-based alerts and predictive insights.
• Pest/disease detection via image uploads.
• Market price tracking.
• Voice support for low-literate users.
• Feedback and usage data collection for continuous improvement.

Relevant Stakeholders / Beneficiaries

• Small and marginal farmers
• Agricultural extension officers
• Government agriculture departments
• NGOs and cooperatives
• Agri-tech startups

Supporting Data

• 86% of Indian farmers are small or marginal (NABARD Report, 2022).
• Studies show ICT-based advisories can increase crop yield by 20–30%.

## Problem Creater's Organization
Government of Punjab

## Theme
Agriculture, FoodTech & Rural Development

## Proposed Solution
Soybean (Glycine max) is a legume crop with 25% contribution to the world's edible oil and two-thirds of the protein of global livestock feedings [1]. Soybean is of high nutritional quality in heart disease and diabetes. In sowing to harvesting, the Soybean crop is susceptible to infestation by different bugs and insects. These can hamper the proper development and growth of the plant crop, thereby impacting the quality of the produce. Therefore, the detection of the presence of insects on the plant is unavoidable. Conveniently, insects can be regulated by diagnosing diseases as soon as they develop on plants in order to reduce their impact on the crops. Insect detection is a time-consuming and labor-intensive task manually, and there is even a chance of human error. AI-based solutions for the identification, detection, and classification of crop diseases are specifically applicable to farmers because they can help detect plant disease early, prevent plant disease, offer accurate diagnosis, and be affordable. Even in rural areas where access to plant pathology experts might be limited, such solutions can provide access to professional advice and expertise. Computer vision has been able to provide an effective solution to this issue thanks to the development of the internet.
This work seeks to design an application that is able to forecast the insect type that attacks a plant given the similarity of how the insect looks like on the leaf. This research envisages deep learning-based solutions to insect identification. Previous attempts to design such solutions like in [2,3] are plagued by one or more reasons such as employing only rudimentary models, incompatible results, and not having high accuracy. The solution proposed here utilizes data with plant leaves and insects for training models. Detection of insects at an early stage can avert further damage to the plant, beneficial during the later crop production cycles. Contributions aspects of this paper are as follows:•Using Pre-processing methods on the Dataset such as resizing and augmentation


## Technical Approach
This paper designs a model for identifying crop disease and insect insects in split segments. An image-based system is developed using AI. The suggested solution will enable farmers to use insecticides effectively and on schedule. The proposed method will give accurate information to the farmer and minimize operating expenses, enhancing crop quality and quantity. The proposed system design is separated into sections: system background, dataset collection, data preprocessing, and training deep-learning models for classifying crops and insects. According to the results, it applies the learned model to detect insects and test the trained models.
The object detection algorithms proposed work to identify the different insect classes on the crop. This method can quickly identify insects, which may significantly increase crop yield. The literature focuses on training YoloV5, CNN, and InceptionV3 models for diagnosing the occurrence of insects in crop plants. These CNN-based models provide excellent image detection and classification outcomes.

## Feasibility and Viability
The viability and feasibility of the suggested solution are greatly ensured through breakthroughs in deep learning and mobile technology. With large amounts of datasets on plant leaves and insect images available, along with preprocessing techniques such as resizing and augmentation, the models can be trained to possess high accuracy and generalization. Current advanced deep learning models have already shown their effectiveness in object detection and image classification, rendering their utilization in insect identification realistic and feasible. In addition, deployment through integration into an Android application is simple and convenient to access for farmers, even in isolated regions. The system is cost-saving, scalable, and flexible across various crops, with high chances of real-world application and long-term viability in agricultural use.
Research and Reference
GOOGLE.COM
---

### Challenges
Farmers face diverse challenges including climate change, leading to erratic weathe

---

### Solutions
- Training sessions and awareness campaigns to help farmers become familiar with the app and USSD services.  
- Building partnerships with local agricultural officers to ensure reliable data collection.  
- Updating AI models regularly with field data provided by agricultural universities.  

## Impact and Benefits
The suggested work has vast impact and application in agriculture and crop protection. With the use of deep learning-based insect detection on soybean crops, farmers and scientists are able to identify pests early on, thus averting extensive damage and minimizing crop loss. Employing preprocessing methods like resizing and augmentation guarantees improved model accuracy and resilience, thus making the solution reliable under real-life conditions. Real-time detection of insects using a mobile app improves convenience for farmers, as they are able to easily detect damaging insects on the field without necessarily needing expert skills. This not only improves sustainable agriculture by curbing excessive use of pesticides but also enhances productivity in crops, improves food security, and reduces the financial constraints on farmers.

### Impact on Farmers
Farmers receive precise recommendations on when to sow, irrigate, and harvest, helping them avoid losses due to guesswork.  

### Social Benefits
Encourages rural communities to adopt digital tools, creating awareness and reducing their dependency on traditional word-of-mouth advice.  

### Economic Benefits
Farmers face major economic challenges including high input costs (like fertilizer and fuel), lack of access to credit and finance, poor infrastructure (transport, storage, and irrigation), and market inefficiencies caused by middlemen and volatile prices. Climate change, leading to unpredictable weather and crop failures, further exacerbates these financial strains, increasing debt and threatening long-term economic sustainability. 
 

### Environmental Benefits
- Promotes sustainable farming by preventing chemical overuse.  
- Conserves water by suggesting irrigation only when required.  

### Diagram
![alt text](images.jpg)

## Research and References
- [World Bank – Digital Agriculture](https://www.worldbank.org/en/topic/agriculture/brief/digital-agriculture)  
- [Indian Council of Agricultural Research (ICAR)](https://icar.org.in/)  
- [Food and Agriculture Organization (FAO)](https://www.fao.org/home/en)  
- [NITI Aayog – Technology in Agriculture](https://www.niti.gov.in/)