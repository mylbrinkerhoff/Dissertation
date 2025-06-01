# Dissertation Defense Outline

## Introduction

- **Overview of my dissertation**
	- **Research Questions**
		1. Is residual H1 an effective acoustic measure?
		2. How is the acoustic landscape structured for SLZ?
		3. Which measures are the most important in capturing and classifying the contrasts?
		4. How do these measures help explain the behavior of SLZ's laryngeal complexity?
	- **Outline of presentation**
- **What is voice quality?**
- **Santiago Laxopa Zapotec Introduction**
  - Spoken in Santiago Laxopa Zapotec by approx. 1000
  - Four vowel system
  - Four phonations
  - 5 tones
  - Tone and Phonation are contrastive

## Previous Research

- **Measuring voice quality**
	- **Previous methods**
		- Fischer-Jørgensen (1968)
		- Gordon & Ladefoged (2001)
	- **Residual H1**
		- Chai & Garellek (2023)
		- Brinkerhoff & McGuire (2025)
    - **Too many measures**
      - Kreiman et al. Psychoacoustic Model of Voice Quality parameters
      - VoiceSauce
- **Models of voice quality**
	- **Ladefogedian**
		- One-dimensional model: breathy to creaky
	- **Garellek et al. (2016)**
		- At least five dimensions
		- Psychoacoustic Model expands this to eight
		- Primarily differences between individual speakers
	- **Garellek et al. (2013) on White Hmong**
		- Fewer dimensions needed to capture phonation contrasts than speaker differences
	- **Keating et al. (2023)**
		- Cross-linguistic patterns collapse into two dimensions
- **Laryngeal Complexity**
	- What is laryngeal complexity?
	- Phasing
	- Implicational hierarchy of patterns
	- Previous research into laryngeal complexity:
		- Blankenship (1997, 2002)
		- Garellek & Keating (2011) on Jalapa Mazatec
		- Frazier on Yucatec Mayan
		- Dicanio on Triqui
		- Chichimec

## My Results

- **Data**
	- Fieldwork conducted with Maya in Summer 2022
	- 10 Speakers (5 female)
- **Acoustic landscape**
	- **MDS**
		- Four dimensions used (based on scree plot)
		- Only three were informative
	- **MDS results**
		- 3D plot (consider as a GIF)
    		- What do we take away from this 3d plot
        		- We very clearly show the differences
		- Dimension 1 × 2 plot
		- Dimension 1 × 3 plot
		- Dimension 2 × 3 plot
	- **Summary of MDS**
		- Dimensionality of the data:
			- Dimension 1: Glottal-airflow continuum
			- Dimension 2: Nonmodal-to-modal continuum
			- Dimension 3: Glottal-airflow continuum
- **Random Forest**
	- What is Random Forest?
	- Most important measures:
		- Duration
		- A1
		- H1-A1
		- Residual H1
		- HNR < 1500 Hz
		- SoE
	- Summary of Random Forest
- **Laryngeal Complexity in SLZ**
	- GAMMs
	- Measures considered:
		- f0
		- HNR
		- SoE
	- Summary of Results

## Overall Summary and Conclusions

- **Summary of results**
	- Acoustic landscape is structured by glottal airflow and nonmodal-to-modal phonation
	- Duration, A1, H1-A1, residual H1, HNR < 1500 Hz, and SoE are the most important measures for capturing the contrasts
	- Laryngeal complexity in SLZ produces vq weakly but also shows phasing between modal and nonmodal
- **Implications of my research**
  - How to pair things down is one of the big things. 
- **What's next?**

## Acknowledgements

## Appendix

- **Random Forest hyper-grid parameter tuning**

# General Notes
- Overall gist is good
- Really focus on the big picture
- Good on making it clear that Keating et al congruent
  - Not unique to Zapotec
  - Converging on shared properties
- Unique contribution 
- Avoid saying I've thought about it (it is a tic)
  - Ok to say I don't know or that is a good point i need to look into that some more
- Timing like a colloquium but a little bit shorter
  - Try and aim for the 40-45 minute mark. 
- Don't go to much into the the particulars of what the methods are but go into why I chose them and why they are helpful (focus on the goal of the analysis)
  - MDS a general technique for dimensionality reduction avoides pitfalls of PCA or LDA and makes a better comparison based on the data
  - Random Forest avoides the problems of CART more robust 
  - GAMMs allow us to model non-linear data
- 