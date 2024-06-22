
# SOFTWARE CODE OF SEIZURESAFEGUARD
## By
### Nilanjana Sarkar, Roll No. 10900121226
### Ankit Chowdhury, Roll No. 10900120145
### Aitijhya Sarkar, Roll No. 10900120121
### Rishmita Sen, Roll No. 10900121222

 ## **Under the guidance of Prof. Arnab Chakraborty**


### *Table Content:-*
 ## Abstruct
-  Introduction
    -  Background and Significance of Epilepsy Detection using EEG
    -  Objectives
     - Scope and Limitations
- Literature Survey
-  Proposed Work
     - Project Implementation
     -  Ethical Considerations
- Epileptic Case Study
- Symptoms of Epilepsy
-  Breif Description of Epilesy
-  Types of Epileptic Seiures
-  Epilepsy recent trends and data
-  Need of EEG
-  How EEG works in detecting epilepsy
-  Existing Devices
    -  SEIZALARM
    -  EMBRACE 2
- Our Differentiating Factor
-  Future Scope of Our Project
-  Conclusion

- ### Abstruct
This project aims to develop a wearable device that can detect seizures in epileptic patients through the real-time analysis of patient parameters such as EEG, heart rate, temperature, and involuntary jerking motions. The physiological data will be continuously monitored and recorded using sensors embedded in a wristband. Collected data will then be analysed using machine learning algorithms to detect abnormal patterns indicating the onset of a seizure. Once a seizure is detected, the device will alert caregivers or medical professionals on a connected mobile app. This project is expected to significantly improve the quality of life for epileptic patients by providing timely and accurate detection of seizures, allowing for prompt medical intervention. A log will be maintained enabling healthcare professionals to monitor patient progress and adjust treatment plans accordingly. The use of IoT technology in this project represents a promising advancement in the field of healthcare and has the potential to greatly benefit patients with epilepsy.

- ### Introduction
Epilepsy, a chronic noncommunicable neurodegenerative disorder, affects 50 million people of all ages worldwide. It is characterised by recurrent seizures caused by abnormal electrical discharges in the cerebral region of the brain. A person with epilepsy has two or more unprovoked seizures that happen more than twenty-four hours apart. Depending on which areas of the brain are affected, an excessive spike in electrical activity in the brain during a seizure can result in a wide range of symptoms. Seizures can be broadly classified into three categories: generalised, focal, and epileptic spasms.
  - **Background and Significance of Epilepsy Detection using EEG :**
Epilepsy detection using EEG is a valuable technique that involves recording and analysing the electrical activity in the brain. This method helps doctors diagnose epilepsy and understand the pattern and characteristics of seizures. By studying the EEG signals, healthcare professionals can identify abnormal brain activity and determine the type and severity of epilepsy. This information is crucial for prescribing appropriate medications, implementing treatment strategies, and improving the overall management of epilepsy. It allows for a more precise and personalised approach to care, ultimately enhancing the quality of life for individuals living with epilepsy. EEG allows detection of a large spectrum of seizure types, even those without motor and autonomic features. The EEG signal of an epileptic patient can be segmented into four sections, namely pre-ictal (before seizure), ictal (during seizure), post-ictal (after seizure) and inter-ictal (between seizure episodes). The pre-ictal and inter-ictal stages are key sections in predicting seizure onset.
  -  **Objectives :**
In our project, we aim to create an automated system for seizure detection using IoT. The objective is to develop a device that can continuously monitor and analyse various physiological signals and movement patterns in individuals with epilepsy. By leveraging IoT technologies such as wearable devices or sensors, the system will collect real-time data from these individuals. This data will then be processed and analysed using advanced machine learning algorithms. The system will be trained to recognize specific patterns or changes in the collected data that indicate the occurrence of a seizure. Once a seizure is detected, the system will generate timely alerts to notify caregivers or medical professionals. This will allow for immediate intervention and assistance, potentially reducing the risk of injury or complications during a seizure. Seizure detection devices also allow objective tracking of frequency of seizures, allowing healthcare professionals to evaluate response to therapy and appropriately adjust medications.
  - **Scope and Limitations :**
The scope of this project involves developing an automated system for seizure detection using IoT technologies. This system will aim to continuously monitor and analyse various physiological signals and movement patterns in individuals with epilepsy. By leveraging IoT devices such as wearable sensors, the system will collect real-time data from these individuals. The focus will be on utilising advanced, power-efficient algorithms and machine learning techniques to analyse this data and accurately detect seizures. The system will then generate timely alerts to notify caregivers or medical professionals, enabling them to provide immediate support and intervention during seizure episodes. As for the limitations, the accuracy of seizure detection can vary based on individual differences in symptoms and seizure patterns. The system may not be able to detect all seizures accurately due to the complexity and variability of seizure episodes. Additionally, external factors such as environmental noise or interference may affect the system's performance. The performance of EEG-based seizure detection devices decreases with reduction in the number of electrodes. There is also the problem of false alarms. Building a generic method that would fit for every epileptic patient is a tedious task, owing to the fact that epileptic seizure pattern in one patient may be a normal EEG in another patient.

- ### Literature Survey
Traditionally, scalp EEG has been used in diagnosis, detection and classification of epileptic seizures. But this method is typically complex, and in some cases, prone to false alarms and limited sensitivity. Seizure detection devices make use of various sensors ranging from movement detectors like electromyography, accelerometers, gyroscope, autonomic change detectors like heart rate, body temperature, blood pressure, oxygen saturation, and EEG surface electrodes apart from Near Infrared Spectroscopy. Most commercially available in-home seizure detection devices rely on heart rate and/or bed movement. A lot of these devices have not received due regulatory approval from medical bodies. Almost all seizure detection devices are designed to detect only tonic-clonic seizures. Ongoing studies give hope on using heart rate variability as a reliable indicator. The pressing issue is that epileptic patients need fast and quality healthcare. Seizures can cause mild to serious injuries, concussions, or even Sudden Unexpected Death in Epilepsy (SUDEP) in case there is any delay in getting medical attention. Therefore, a Wearable IoT Device for Real-Time Epileptic Seizure Detection is required for timely medical attention and preventing life- threatening conditions like paralysis, permanent brain damage, or in rare cases, death.

- ### Proposed Work
Our proposed work centres around the development and implementation of a groundbreaking wearable device engineered for continuous monitoring and real-time detection of epileptic seizures. Each key feature of the device is meticulously designed to enhance user experience and provide a comprehensive solution to seizure management.
  - **Wearable EEG Monitoring**:
The device boasts the integration of a lightweight and comfortable EEG sensor in a compact form factor, ensuring uninterrupted monitoring of the user's brain activity. This design consideration prioritises user comfort, promoting prolonged and consistent usage of the device.
  - **Real-time Seizure Detection:** To enable swift intervention, advanced signal processing algorithms are employed for the real-time analysis of EEG signals. These algorithms have been fine-tuned to detect subtle patterns indicative of epileptic seizures, ensuring timely alerts to caregivers or medical professionals.
-- **Alerting Mechanism:** A robust alerting mechanism is integral to the device, featuring visual cues through a display, haptic feedback via vibration, and audible alerts through a small speaker upon seizure detection. This multi-sensory approach aims to promptly capture the attention of the user and those around them.
Automatic Message Sending: Our device is equipped with a communication module that automates the sending of pre- configured alert messages to a predefined list of emergency contacts or caregivers. This feature ensures that crucial information reaches the necessary individuals without delay.
  - **Location Services:** Enhancing emergency response, the device integrates GPS or other location services to include precise information about the user's location in the alert messages. This assists responders in reaching the user quickly, optimising the effectiveness of the emergency intervention.
  - **User-Friendly Interface:** The device prioritises an intuitive user interface, providing real-time EEG data, customizable alert settings, and battery status. This user-centric design aims to facilitate ease of use and seamless interaction with the device.
Mobile App Integration: A companion mobile application is developed to complement the device, allowing users to customise alert settings, visualise historical seizure data, and manage emergency contacts. This integration provides users with a comprehensive tool for monitoring and managing their epilepsy.
  - **Power Efficiency:** Efficient power management is at the forefront of the device's design, incorporating features such as automatic sleep modes during inactive monitoring periods. This ensures an extended battery life, minimising disruptions in monitoring due to frequent recharging.
