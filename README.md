# DCD-HAMS: Decentralized Cross Device Learning for Hierarchical Aggregation of Medical Symptoms

Medical analysis has become an integral part of modern society. With the advent of modern transport and better locomotive capacity, the world was introduced to faster methods of travel, however, with it came the risk of widespread spread of disease, such as in the case of pandemics. Even outside of the global scale, smaller epidemics which are not studied and countered quickly cause massive damages to community health and progress. It becomes important to study the initial symptoms of such diseases and develop a better understanding of the disease itself. In the past year itself, we have seen the novel coronavirus (Covid-19) bring the whole world to a complete standstill, causing immense losses in both life and economy. In the initial stages, the world struggled at handling the influx of patients and controlling the spread of this disease. Confusion, unpreparedness and fake news further decayed efforts towards controlling the virus.

Symptom prognosis and analysis is an important part of pandemic management, as they allow people to be aware of their medical conditions. However, during Covid-19 appropriate symptoms and their exact affects were only reported after mass scale collection and analysis of data, which consumed immense amounts of manual efforts as well as precious time. DCD-HAMS could become a viable approach towards development of a government supported, public driven system for elementary symptom realization during a new epidemic or pandemic. DCD-HAMS offers to present a viable method for not only symptom collection, but also ensures a certain level of client privacy at the time of decentralized aggregation. Concepts of Input Privacy, Output Privacy as well as government aided Flow Governance. On the topic of Input and Output Verification, a possible methodology including Input Verification, may be applied however, reputation measurability may be difficult to manage and implement during times of pandemic, when time is of utmost importance. Nonetheless, a method including Input Verification is also discussed in the following document.

## Introduction:

Pandemic control and management have become highlighted issues, within the last couple of months. With the spread of the novel coronavirus, the world saw destruction of life and property. Various businesses, infrastructures, etc. were shutdown unemployment, reduced wages, and unpaid leave further ravaged livelihood, not to mention the loss of life and degradation of health caused by this pandemic. A total of 91 million people suffered from Covid-19 over the progression of 2020. However, it is still believed that if significant steps were taken at the beginning of the pandemic, the spread and the massive scale of Covid-19 could have been stalled or limited entirely. One direction to note, is that the symptoms of Covid-19 were discovered and brought to light after a significant time had passed, allowing first waves of the virus to spread. Limited to no actions were taken in the beginning to highlight such symptoms, until the spread had progressed to multiple countries.

During a pandemic, symptom prognosis as well as prominent symptom retreival become an important aspect research. However, common symptoms such as high temperatures, soar throat, fevers, etc. become easily discernable even by the likes of the avergae citizens. Taking a look at statistics presented by Statista over symptoms and their percentages in verious countries, one will come to find that these are common symtoms, easily discerable by the common man.


**Table 1**
*These are the 4 most prominent symptoms as well as the total number of participants from every country included in our dataset.*


Country | USA | Country | Kenya | Country | China | Country | Germany | Country | Italy
---|---|---|---|---|---|---|---|---|---
Total | 3,73,883 | Total | 14,616 | Total | 55924 | Total | 7,47,900 | Total | 34142
Fever, cough, or shortness of breath | 69.8% | Fever | 90.05% | Fever | 87.9% | Cough | 40% | Fever | 75%
Fever | 43.15% | Dry cough | 74% | Dry cough | 67.7% | Fever | 28% | Dyspnoea | 73%
Cough | 50% | Difficulty in breathing | 70% | Fatigue | 38.1% | Runny nose | 26% | Cough | 38%
Shortness of breath | 28% | Sneezing | 61.75% | Sputum production* | 33.4% | Sore throat | 21% | Diarrhea | 6%


The data presented is a statistical representation of the % of people exhibiting a the novel coronavirus. The total number of samples taken from the entire corpus makes up 1,226,465 people's data. The countries whose data has been presented are:

1. Kenya 
2. Germany
3. Italy
4. United States
5. China

1.2 million, makes up a large sample space and therefore gives a certain amount of guarantee that the most common symptoms exhibited by infected individuals include the above. Even for elementary checkups at airports and places of public transport, governments have set up thermometer checks, these key checks play an important role as they allow for easier discretion and thereby allowing for further medical investigation. This allows contact tracing, thereby limiting the spread of the disease. At the same time, if citizens were made aware of these symptoms, people would be not only be wary of others who exhibited such symptoms but also themselves, allowing for faster medical inspections. This is the key note to be highlighted in this project that, symptom prognosis is an important part of pandemic management and control. The above thoughts are put forth while keeping in mind the value it will have on individual people and society as a whole.

DCD-HAMS, is method meant to overcome this shortcoming. During Covid-19, it took a couple of months to set up an international body for data aggregation and assessment before common symptoms were deliberated and publicly put forth. In the mean time, fake news, rumors and superstitious beliefs sabotaged any work put forth by formal medical bodies. These couple of weeks at the beginning of 2020, were essential and a faster method for prominent symptom retrieval would have greatly benefitted medical institutes, as localized learning in places of interest/infection, would have highlighted certain symptoms, which could be considered for concrete medical proofs allowing a faster and statically robust method of detecting the disease.

## Need for Above Technology:

As mentioned above, prominent symptom detection during pandemics can become a powerful tool at combatting outbreaks. Prominent symptoms can allow for faster detection, easier localization as well as individual awareness in the community. However, with these analysis, comes its various issues. For example, taking the case of Covid-19 in its early stages, patients were discovered slowly by the mode of trial-and-error or their own initiative to approach healthcare centers. This was followed by governments and public bodies, setting up infrastructure for collection and aggregation of these patient data. This itself becomes a point of potential security risk, medical data however, much anonymized may still lead to large scale leakage if attacked suitably. At the same time, the amount of manual effort required to anonymize such a large corpus of continuously growing data is also a point of concern. Simultaneously,  the time and effort taken to develop such an infrastructure for analysis, may have consumed lots of valuable time. These, points are excluding all logistical, manual and computational costs which would plague such a project. 

Now looking at distributed research by smaller bodies for the same, one can understand that the sample space may be considerably smaller, regionally restricted and therefore, biased. Citing one of the examples mentioned in the OpenMined course this would be similar to the "People from Western, educated, industrialized, rich and democratic (WEIRD) societies — who represent as much as 80 percent of study participants, but only 12 percent of the world’s population — are not only unrepresentative of humans as a species, but on many measures they’re outliers." Therefore, this too is not a viable solution for pandemics. Local bias may cause further confusion in the general public leading to much more disinformation. This can only be solved by making a more centralized system.

The problems presented above can be summarized in the following 5 points:

* Time Consumption in centralized aggregation by a single institute.
* Data Security of clients participating in such statistics.
* Manual and Logistical Costs for data anonymization of above data to protect client privacy.
* Logistical, Manual and Infrastructural costs for over heading such a project.
* Local Bias for smaller aggregators and analysers.

DCD-HAMS uses decentralized cross-device federated learning to discern prominent symptoms from a corpus of popular medical symptoms. Thereby limiting the search but also making it considerably faster and accurate. The algorithm specifically utilizes, the decentralized approach of Ring Decentralized Federated Learning algorithm presented in "GFL: A Decentralized Federated Learning Framework Based On Blockchain" (Hu et al., 2020). The proposed methodology requires low network capability, and is robust against adversarial participants. One can introduce concepts of differential privacy for client privacy conservation. Thereby, increasing data security as well as giving a metric for privacy loss to different clients as well as an administration (in this case could be medical institutes or the local government). Hierarchical aggregation will reduce local bias and make the final model more generalized in nature. The implementation procedures have been detailed below and discuss the concepts of, Input and Output Privacy as well as, Flow Governance.
