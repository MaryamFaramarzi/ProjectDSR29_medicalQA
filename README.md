###

# ProjectDSR29_medicalQA

### Team Members

- Sina Rampe
- Maryam Faramarzi
- Manali Manajrekar

## SUMMARY
Our goal is to built a Q&A engine that gives a detailed answer to simple health questions, like those asked every day in primary care. 

## SCOPE
• Circumstances in which physicians or pharmacists are not available.

• Circumstances in which social anxiety, shame or other barriers make communication with medical professionals impossible / difficult.

• Online pharmacies or online stores of local pharmacies that offer an additional service to their customers.

• Show healthcare professionals what AI can (and cannot).

## Usage

Here we describe how you can fine-tune GPT2 on a list of QAs.
### Setup

First, clone and repository and enter it

```bash
git clone git@github.com:MaryamFaramarzi/ProjectDSR29_medicalQA.git
cd ProjectDSR29_medicalQA
```

Create a virtual environment using Python 3 and then activate it

```bash
virtualenv qa -p python3 
source qa/bin/activate
```
Install ipython inside your virtual environment 
```bash
ipython kernel install --user --name=qa
```
Then install the required packages using
```bash
pip install -r requirements.txt
```
