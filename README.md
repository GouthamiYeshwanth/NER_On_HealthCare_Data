# NER_On_HealthCare_Data
 
Companies like BeHealthy generate large volumes of data by providing medical services, prescriptions, and online consultations. Let’s take a look at the following snippet of medical data that may be generated when a doctor writes notes to their patient or prepares reviews of their patient.


“The patient was a 62-year-old man with squamous cell lung cancer, which was first successfully treated by a combination of radiation therapy and chemotherapy.”

 

As you can observe, a person with a non-medical background may not understand the various medical terms used in the text. We have taken a simple sentence from a medical data set to understand the problem. Here, you can understand the meaning of the terms “cancer” and “chemotherapy.” 


Suppose you have been asked to identify a disease name and its possible treatment from a given data set and list it out in a table or a dictionary like this.

![Alt text](image-1.png)
After analyzing the problem given above, you must build a custom NER to get the list of diseases and their treatment from the data set