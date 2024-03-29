# DCD-HAMS: Decentralized Cross Device Learning for Hierarchical Aggregation of Medical Symptoms

Medical analysis has become an integral part of modern society. With the advent of modern transport and better locomotive capacity, the world was introduced to faster methods of travel, however, with it came the risk of widespread spread of disease, such as in the case of pandemics. Even outside of the global scale, smaller epidemics which are not studied and countered quickly cause massive damages to community health and progress. It becomes important to study the initial symptoms of such diseases and develop a better understanding of the disease itself. In the past year itself, we have seen the novel coronavirus (Covid-19) bring the whole world to a complete standstill, causing immense losses in both life and economy. In the initial stages, the world struggled at handling the influx of patients and controlling the spread of this disease. Confusion, unpreparedness and fake news further decayed efforts towards controlling the virus.

Symptom prognosis and analysis is an important part of pandemic management, as they allow people to be aware of their medical conditions. However, during Covid-19 appropriate symptoms and their exact effects were only reported after mass scale collection and analysis of data, which consumed immense amounts of manual effort as well as precious time. DCD-HAMS could become a viable approach towards development of a government supported, public driven system for elementary symptom realization during a new epidemic or pandemic. DCD-HAMS offers a viable method for not only symptom collection, but also ensures a certain level of client privacy at the time of decentralized aggregation. Concepts of Input Privacy, Output Privacy as well as government aided Flow Governance. On the topic of Input and Output Verification, a possible methodology including Input Verification, may be applied however, reputation measurability may be difficult to manage and implement during times of pandemic, when time is of utmost importance. Nonetheless, a method including Input Verification is also discussed in the following document.

## Introduction:

Pandemic control and management have become highlighted issues, within the last couple of months. With the spread of the novel coronavirus, the world saw destruction of life and property. Various businesses, infrastructures, etc. were shut down, unemployment, reduced wages, and unpaid leave further ravaged livelihood, not to mention the loss of life and degradation of health caused by this pandemic. A total of 91 million people suffered from Covid-19 over the progression of 2020. However, it is still believed that if significant steps were taken at the beginning of the pandemic, the spread and the massive scale of Covid-19 could have been stalled or limited entirely. One direction to note is that the symptoms of Covid-19 were discovered and brought to light after a significant time had passed, allowing first waves of the virus to spread. Limited to no actions were taken in the beginning to highlight such symptoms, until the spread had progressed to multiple countries.

During a pandemic, symptom prognosis as well as prominent symptom retrieval become an important aspect research. However, common symptoms such as high temperatures, sore throat, fevers, etc. become easily discernible even by the likes of the average citizens. Taking a look at statistics presented by Statista over symptoms and their percentages in various countries, one will come to find that these are common symptoms, easily discernible by the common man.


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

1.2 million, makes up a large sample space and therefore gives a certain amount of guarantee that the most common symptoms exhibited by infected individuals include the above. Even for elementary checkups at airports and places of public transport, governments have set up thermometer checks, these key checks play an important role as they allow for easier discretion and thereby allowing for further medical investigation. This allows contact tracing, thereby limiting the spread of the disease. At the same time, if citizens were made aware of these symptoms, people would not only be wary of others who exhibited such symptoms but also themselves, allowing for faster medical inspections. This is the keynote to be highlighted in this project that symptom prognosis is an important part of pandemic management and control. The above thoughts are put forth while keeping in mind the value it will have on individual people and society as a whole.

DCD-HAMS is a method meant to overcome this shortcoming. During Covid-19, it took a couple of months to set up an international body for data aggregation and assessment before common symptoms were deliberated and publicly put forth. In the meantime, fake news, rumors and superstitious beliefs sabotaged any work put forth by formal medical bodies. These couple of weeks at the beginning of 2020, were essential and a faster method for prominent symptom retrieval would have greatly benefitted medical institutes, as localized learning in places of interest/infection, would have highlighted certain symptoms, which could be considered for concrete medical proofs allowing a faster and statically robust method of detecting the disease.

## Need for Above Technology (Value Proposition):

As mentioned above, prominent symptom detection during pandemics can become a powerful tool at combating outbreaks. Prominent symptoms can allow for faster detection, easier localization as well as individual awareness in the community. However, with these analyses comes its various issues. For example, taking the case of Covid-19 in its early stages, patients were discovered slowly by the mode of trial-and-error or their own initiative to approach healthcare centers. This was followed by governments and public bodies, setting up infrastructure for collection and aggregation of these patient data. This itself becomes a point of potential security risk, medical data however, much anonymized may still lead to large scale leakage if attacked suitably. At the same time, the amount of manual effort required to anonymize such a large corpus of continuously growing data is also a point of concern. Simultaneously, the time and effort taken to develop such an infrastructure for analysis, may have consumed lots of valuable time. These points are excluding all logistical, manual and computational costs which would plague such a project.

Now looking at distributed research by smaller bodies for the same, one can understand that the sample space may be considerably smaller, regionally restricted and therefore, biased. Citing one of the examples mentioned in the OpenMined course this would be similar to the "People from Western, educated, industrialized, rich and democratic (WEIRD) societies — who represent as much as 80 percent of study participants, but only 12 percent of the world’s population — are not only unrepresentative of humans as a species, but on many measures they’re outliers." Therefore, this too is not a viable solution for pandemics. Local bias may cause further confusion in the general public leading to much more disinformation. This can only be solved by making a more centralized system.

The problems presented above can be summarized in the following 5 points:

* Time Consumption in centralized aggregation by a single institute.
* Data Security of clients participating in such statistics.
* Manual and Logistical Costs for data anonymization of above data to protect client privacy.
* Logistical, Manual and Infrastructural costs for over heading such a project.
* Local Bias for smaller aggregators and analysers.

DCD-HAMS uses decentralized cross-device federated learning to discern prominent symptoms from a corpus of popular medical symptoms. Thereby limiting the search but also making it considerably faster and accurate. The algorithm specifically utilizes the decentralized approach of the Ring Decentralized Federated Learning algorithm presented in "GFL: A Decentralized Federated Learning Framework Based On Blockchain" (Hu et al., 2020). The proposed methodology requires low network capability, and is robust against adversarial participants. One can introduce concepts of differential privacy for client privacy conservation. Thereby, increasing data security as well as giving a metric for privacy loss to different clients as well as an administration (in this case could be medical institutes or the local government). Hierarchical aggregation will reduce local bias and make the final model more generalized in nature. The implementation procedures have been detailed below and discuss the concepts of, Input and Output Privacy as well as, Flow Governance.

## Proposed Methodology:

Decentralized Cross Device Learning for Hierarchical Aggregation of Medical Symptoms, utilizes RDFL (Ring Decentralized Federated Learning algorithm), which allows us to train a decentralized model. This will allow further security and anonymization before central collection and hierarchical aggregation. Employing the large sample space for data collection, the algorithm utilizes differential privacy for further security. The use of differential privacy introduces privacy loss, a concept which can be used for Flow Governance and conservation of privacy of individuals who participate in multiple aggregation steps. Differential Privacy and Federated Learning allow us to introduce both Input Privacy and Output Privacy before any aggregation step.

Now at the time of decentralized aggregation, the algorithm aims for localized aggregation further reducing any over-head logistics required to maintain an international or large network system. These localized updates are independent until a certain number of local steps say `E`, while each model for every individual participating, executes for local epochs `e`. These localized updates are then hierarchically aggregated over larger and larger regions (say, Districts, States, Country, International). This will allow for bias reduction and improve the generalization of the model. Internationally aggregated models, can then be used for final detection on the initial medical corpus, for prominent symptom retrieval.

Federated Learning is employed in a Cross-Device decentralized system, as we wish to enable the general public as individual contributors. The RDFL algorithm is used for aggregation and faster learning. Word-embeddings are used for feature extraction on local devices, this allows us to use State-Of-The-Art encoders, such as BERT and ELMO, while also using computationally resourceful GloVe and Word2Vec embeddings. Word Embeddings, produce a vector of fixed length as extracted features of the symptoms given by the users. This output is then fed into a client model, which is trained for a limited number of epochs `e`, before beginning aggregation under the RDFL algorithm.

First and foremost a common word encoder is selected for universal implementation, a lightweight classifier is designed keeping in mind the encoder selected. This allows us to make a learnable model, while at the same time keeping computational costs low. The selected encoder and model architecture is then declared for client-wise training and aggregation. However, by only allowing training on client-symptoms, the model will receive an all positive learning dataset, making the classifier largely biased. That is, there will be a 100% positive sample space, we use random sampling of words from a given medical corpus, which are then learnt as negative samples by client-models. The algorithm is presented Figure 1-3.


![Figure 1: Client Model](/images/client_model.JPG)

**Figure 1**
*Client Model Update Algorithm, for solving data imbalance.*



![Figure 2: RDFL Algorithm](/images/rdfl_algorithm.JPG)

**Figure 2**
*RDFL Algorithm, for decentralized learning.*


![Figure 3: Hierarchical_Aggregation](/images/hierarchical_aggregation.jpeg)

**Figure 3**
*Hierarchical Aggregation Algorithm, for improving generalization.*

## Goals:

1. Input and Output Privacy: Federated Learning and Differential Privacy, give assurance to clients for the privacy of their data. Epsilon or privacy loss, is also introduced as a metric for further restriction and control of the individuals participating. Although homomorphic encryption hasn't been employed due to its high computational requirements, future updates may involve them up to certain degrees.

2. Flow Governance: The epsilon values can also be used for flow governance by an administrating body such as the local or central government of the region. Thereby, allowing for easier transaction of data without ever leaking too much privacy of an individual.

3. Decentralized Learning using RDFL, reduces risks posed by adversarial participants, as well as reduces overall logistical costs.

4. Manual costs for anonymization and/or preprocessing is completely cut down.

5. The general public can be included for the purposes of training, allowing generalization. 

The above methodology offers a faster and convenient method for symptom detection. It is easier to implement and offer great support privacy conservation while providing the desired results. From the 5 problems we discussed above, it is able to solve each of them, thereby giving us an appropriate means of symptom collection.

### Audience:

The target audience for this project are medical institutes and government bodies, which wish to understand pandemics quicker and in a more generalized manner, while maintaining individual privacy and lower logistical costs. The implementation, done for Covid-19, is one of the existing technologies/methodologies used, however, DCD-HAMS is able to give some significant improvements to it.

## Conclusion:

Decentralized Cross Device Learning for Hierarchical Aggregation of Medical Symptoms, provides an efficient methodology for prominent symptom retrieval during pandemics. With a prominent target audience of this being the central government, we look up to them to look after the Privacy Control/Flow Governance of individuals participating in this project. Even so, we employ differential privacy and decentralized federated learning, both which are great tools towards input and output privacy. As for input verification, a locally managed, reputation scale can be created by the base aggregating administrative bodies, which could be used to improve the pre-existing RDFL algorithm. In the end, this project offers a novel methodology for symptom retrieval in a pandemic setup, while requiring low overhead costs and privacy of clients.

### Furture Work:

* Homorphic Encryptions could be included to further improve privacy.
* Output Verification could be included in the given setup
