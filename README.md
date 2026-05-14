# VGIchan: Prediction and Classification of Voltage-Gated Ion Channels

VGIchan is a computational web server developed for predicting and classifying voltage-gated ion channels from protein sequences.

Voltage-gated ion channels are membrane proteins that control the movement of ions across cell membranes in response to changes in membrane voltage. These channels are essential for electrical signaling in excitable cells such as neurons and play important roles in nervous system function, drug targeting, and disease mechanisms.

Web Server: http://www.imtech.res.in/raghava/vgichan/



## Citation

Saha, S., Zack, J., Singh, B., and Raghava, G. P. S. VGIchan: Prediction and classification of voltage-gated ion channels. Genomics, Proteomics & Bioinformatics, 4(4), 253-258, 2006.
https://doi.org/10.1016/S1672-0229(07)60002-4

This tool and dataset is also available on Zenodo at 


## About the Research

Voltage-gated ion channels are integral membrane proteins that allow the selective passage of inorganic ions across cell membranes. They open and close in response to changes in transmembrane voltage and are important for electrical signaling in cells.

These ion channels are involved in several physiological processes, especially in neurons, where they help generate and conduct nerve impulses. They are also important drug targets for conditions such as epilepsy, hypertension, anesthesia response, schizophrenia, manic-depressive illness, and other neurological or psychiatric disorders.

VGIchan was developed to predict whether a protein sequence belongs to a voltage-gated ion channel and to further classify it into specific ion channel types.

Data Compilation: Voltage-gated ion channel sequences were collected from the Swiss-Prot database. The final dataset included 473 annotated ion channel proteins, including potassium, sodium, calcium, and chloride ion channels. A non-redundant dataset of 236 ion channels was prepared for model development.

Methodology: VGIchan uses support vector machine models, PSI-BLAST similarity search, hidden Markov models, and hybrid approaches to predict and classify voltage-gated ion channels.



## Key Features

### 1. Voltage-Gated Ion Channel Prediction

Predictive Modeling: Allows users to submit protein sequences and predict whether they are voltage-gated ion channels or non-ion channels.

Amino Acid Composition Model: The amino acid composition-based SVM model achieved 82.89% accuracy.

Dipeptide Composition Model: The dipeptide composition-based SVM model achieved 85.56% accuracy.

Hybrid Prediction: A hybrid model combining dipeptide-based SVM and PSI-BLAST similarity search improved the prediction accuracy to 89.11%.



### 2. Ion Channel Classification

Sub-Class Prediction: VGIchan classifies voltage-gated ion channels into major channel types.

The tool classifies sequences into:

- Potassium ion channels
- Sodium ion channels
- Calcium ion channels
- Chloride ion channels

Dipeptide-Based Classification: The dipeptide-based SVM model achieved 96.89% overall classification accuracy.

Hybrid Classification: A hybrid method combining dipeptide-based SVM and hidden Markov models achieved 97.78% overall classification accuracy.



### 3. Integrated Web-Bench

Sequence Submission: Users can submit protein sequences by copy-paste or by uploading a sequence file.

Supported Formats: The server accepts raw sequence format as well as standard formats such as EMBL, FASTA, and GCG.

Prediction Options: Users can choose SVM, PSI-BLAST, or HMM-based prediction methods.

Reliability Index: VGIchan provides a reliability index to indicate confidence in the classification prediction.

User-Friendly Interface: The server provides results in a simple interface for automated annotation and preliminary analysis of ion channel proteins.



## Applications

Ion Channel Annotation: VGIchan can help annotate voltage-gated ion channels from newly sequenced proteins.

Functional Genomics: The tool can support genome-scale identification of ion channel proteins.

Drug Discovery: Since voltage-gated ion channels are important drug targets, VGIchan can support early-stage target identification.

Neuroscience Research: The tool can help identify proteins involved in electrical signaling and neuronal excitability.

Disease Biology: VGIchan can assist in studying ion channels associated with epilepsy, hypertension, psychiatric disorders, and other channel-related diseases.

Protein Classification: The tool provides a computational framework for classifying ion channel proteins into potassium, sodium, calcium, and chloride channel types.



## Contact and Authors

Prof. Gajendra P. S. Raghava  
Corresponding Author  

Email: raghava@imtech.res.in  

Institute of Microbial Technology  
Chandigarh-160036, India  



## Support

This work was supported by the Council of Scientific and Industrial Research and the Department of Biotechnology, Government of India.
