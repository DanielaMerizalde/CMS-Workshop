# **Particles Discovery Lab**

The goal of this exercise is to reconstruct decays of an unknown particle X (initial state) to 2 muons (final state). To achieve this goal, participants need to display histograms for the calculated mass of particle X and learn about fitting and subtracting background distributions from data.

Uncertainty propagation concepts are included at each step of the analysis. After isolating the signal distribution, participants will determine which particle they have discovered and compare its properties (mass and width) to known properties.
![Alt Muon](MuonLab_JpsiSigBkg.png)


## **Get Ready**

* Have the **my_python** container ready. The steps to install Docker and create this container were mentioned on the pre-exercises.
  
## **Excecute the following commands**
```
docker start -i my_python
mkdir Particle_Discovery_Lab
cd Particle_Discovery_Lab
git clone https://github.com/DanielaMerizalde/CMS-Workshop.git
cd ..
jupyter-lab --ip = 0.0.0.0 --no-browser
```
After running the last command open the link in the message on your browser. Ensure that after clonning the repository the following files have been created: **pollsf.py**, **Particle_Discovery_Lab.ipynb**, and **DoubleMuParked_100K.pkl**. 
