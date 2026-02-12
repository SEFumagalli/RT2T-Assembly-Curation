# Ruminant Telomere-to-Telomere (RT2T) Genome Assembly and Curation Project

This repository contains **documentation**, **tutorials**, and **scripts** for performing **genome assembly** and **manual curation** using **[Verkko](https://github.com/marbl/verkko)** and **[Verkko-Fillet](https://github.com/jjuhyunkim/verkko-fillet/tree/main)**.   



--- 



### **RuminantT2T Project**
- **Assembly prep and data organization**
- Several species/breeds/crosses prepped for curation:

	- **Antilocapridae 	- Pronghorn**
	- **Bovidae	 	- Bison x Pied**
	- **Bovidae 	 	- Bison x Simmental**
	- **Bovidae 	 	- Chamois**
	- **Cervidae	 	- White Tailed Deer**
	- **Cervidae	 	- Red Deer x Wapiti**
	- **Cervidae	 	- Wapiti x Red Deer**
	- **Giraffidae	 	- Giraffe**
	- **Moschidae	 	- Siberian Musk Deer**
	- **Tragulidae	 	- Chevrotain**
	- **Outgroup	 	- Alpaca**
	


---



### **Contents**
- `helper-scripts`
	- read quality control
	- read statistics
	- assembly statistics

- `Verkko`
	- tips on how to use the flag for unitig abundance (UA)
	- how to update necessary files when scaffolding joins are not correctly listed

- `Verkko-Fillet`
	- modified to run on **[SCINet's HPC Ceres](https://scinet.usda.gov/)**
	- additional scripts extend file formatting for easier curation 
