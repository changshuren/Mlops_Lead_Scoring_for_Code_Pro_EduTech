# Project Name
>Mlops Assignment

CodePro is an EdTech startup that had a phenomenal seed A funding round. 
It used the money to increase its brand awareness. As the marketing spend increased, it got several leads from different sources. Although it had spent significant money on acquiring customers, it had to be profitable in the long run to sustain the business. <br /> The main objectives of lead scoring are as follows:

Remove Junk by categorising leads on the basis of propensity to purchase
Gain insights to streamline lead conversion and address improper targeting
We have chosen L2AC (Leads to Application Completion) as our business metric, as choosing L2P (Leads to Payment) will aggressively drop the leads.
A lead is generated when any person visits CodePro’s website and enters their contact details on the platform. A junk lead is generated when a person who shares their contact details has no interest in the product/service.
Having junk leads in the pipeline creates significant inefficiency in the sales process. Thus, the goal of the data science team is to build a system that categorises leads based on the likelihood of their purchasing CodePro’s course. This system will help remove the inefficiency caused by junk leads in the sales process. <br /> We have seen that we are creating three different pipelines for our use case.<br />

Data Pipeline<br />
Training Pipeline<br />
Inference Pipeline<br />
Our system metrics for the ML model are :<br />
AUC score > 82.1%<br />
Precision > 70.5%<br />
Recall > 82.5%<br />
 

Since this is the first iteration of the model we are not aiming for high performance from the model but we are aiming to get value from the model as soon as possible by deploying the model into production, and then continuously improving our model once our baseline is deployed. Thus we will not focus much on developing the best possible model but we will make do with a simple model and focus more on deploying it into production.
## Table of Contents

* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Airflow,Mlflow,Pycaret
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
IITB




<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->