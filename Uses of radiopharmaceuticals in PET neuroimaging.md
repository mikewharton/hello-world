# Uses of radiopharmaceuticals and particle physics in PET imaging and neuroscience

## Mike Wharton

#### Abstract

Detailed three-dimensional tomography of the brain can be obtained from the use of positron emission tomography, and this method is used to help determine how effectively your body is working.  This paper aims to enlighten those who read it on the processes involved with the use of this type of neuroimaging, and how radiopharmaceuticals are involved with this procedure. Attempt will be made to simplify the procedure to basic principles in order to explain it more easily to readers. PET scans produce cross sections of the body in order to construct a three-dimensional computational model. A radiopharmaceutical (medical tracer) with a short half life is injected into the patient, where it accumulates in tissues or binds to haemoglobin molecules. The emitted positron from the decaying radioactive nuclei annihilates upon collisions with nearby electrons (of equal and opposite charge) and this process results in the release of two, high energy, gamma photons at equal velocities in opposite directions, which are absorbed by a ring of detectors surrounding the patient's head.

------

#### Introduction

It is particularly useful to investigate the spread of cancer in patients using PET scans as it allows doctors to determine the best course of action or to investigate how well the disease is responding to treatment^[4]^. In the UK alone there were 164,901 deaths from cancer between 2015 and 2017,  and the percentage of people who survive for 10 or more years after contracting cancer is around 50%^[4]^. PET enables clinicians to assess the status of patients more easily and has therefore been a very positive influence on the treatment and regulating of cancer cases across the world. The process is also non-invasive, usually taking between 30 to 60 minutes^[12]^, however it can be very expensive due to the facilities required to produce the medical tracers and the expense of the equipment and computation required. The main focus of this paper is the particle physics involved 'behind the scenes' in this process however the decisions behind the compounds used, safety precautions, history of the process and future developments will also be covered.

#### History of PET Imaging and Neuroimaging

In 1878 Angelo Mosso discovered the relationship between blood flow and brain function, through the measurement of brain pulsations during an arithmetic task.  This framework was expanded on in later years^[10]^ however this field of science later allowed for the use of PET imaging to observe how the brain responds to tasks.

Radioactive tracers were came about following the Second World War, when nuclear research shifted in focus from the Manhattan Project to other particle physics, leading to the fruition of safe radioisotopes. Irene and Frederic Joliot-Curie (daughter and son-in-law of Marie Curie) managed to create the first artificial isotope in 1934 which suggested that more elements could be formed, safe for humans.^[5]^

It wasn't until 1950 when Benedict Cassen developed the first radioactive isotope imaging system, using the Geiger counter, the only available detector at the time along with the *photomultiplier tube* which allowed for gamma rays to be amplified and detected. ^[6]^, using radioluminescence to produce a greyscale image in more definition than ever before. Further developments were made in the 1980s when hexagonal and cylindrical detectors started to be produced.

<center><figure><img src="./fig/Photomultiplier tube.png" width="500"></img><figcaption>Fig. 1 - Photomultiplier tube</figcaption></fig></figure></center>
###### *Photomultiplier Tubes*

Due to the photoelectric effect a photon hitting the photocathode will produce a photoelectron. This electron will be accelerated through the vacuum into dynodes which are held at increasing  potentials (for example starting at +100V and increasing by 100V on each subsequent dynode) . The rapid electron colliding with the first dynode produces an average of four secondary electrons which are then accelerated towards the next dynode at a higher speed. Through this exponential growth in the number of electrons travelling along the path, the number of electrons arriving at the anode from one photon can be as many as a million. The electrons collected at the anode pass through a resistor and produce a small pulse of voltage which can be recorded. The dynode of a photomultiplier tube can be discrete (as in the above diagram) or continuous where a single voltage gradient is used instead of multiple plates. Photomultiplier tubes are a key part of the gamma cameras which line the detector ring of a PET scanner.

#### Choosing Radiopharmaceuticals and Fluorine-18

When choosing a compound to use as a tracer lots of factors have to be taken into account such as the half life and the type of radioactivity predominantly present  in the substance. Isotopes of an element differ only in their masses - with generally higher masses being associated with a higher likelihood of radioactivity.  When a nucleus is deemed unstable then compounds containing this isotope will also be radioactive, which means that compounds can be engineered to be able to reach parts of the body which need to be scanned. In radioactive tracers often specific atoms in compounds already commonly found in the body can be replaced with radioisotopes, in a process called radioactive labelling. The most commonly used medical tracer is fluorine-18, this is mainly due to the fact that it has a reasonable half life of 109.771 minutes and it is a positron emitter (another useful trait specifically relevant to PET scanners). This decay process produces a nucleus of oxygen-18, a positron, a neutrino, and a gamma photon.
$$
_{9}^{18}\textrm{F} \rightarrow _{8}^{18}\textrm{O} + _{+1}^{0}\textrm{e}+v_{e}+\gamma
$$
Positron emission however is particularly useful for the PET imaging as they will collide with nearby electrons. At low energies like this, the collision results in annihilation of the electron and positron, creating two energetic antiparallel gamma photons (in order to conserve momentum), which can then be used to determine the point of annihilation from the difference in arrival times of these photons at the two opposite detectors. 
$$
^{0}_{-1}e + ^{0}_{+1}e \rightarrow \gamma + \gamma
$$

<center><figure><img src="./fig/Annihilation.png" width="400"></img><figcaption>Fig. 2 - Electron positron annihilation due to beta plus decay</figcaption></fig></figure></center>
Fluorine-18 is an important positron source however it is not a naturally occurring isotope and for this reason it has to be made in a laboratory. A particle accelerator is used to bring protons to a high speed in order for them to collide with oxygen-18 nuclei and produce fluorine-18 by 'replacing' a neutron in the nucleus.
$$
_{1}^{1}p+_{8}^{18}O \rightarrow _{9}^{18}F+_{0}^{1}n
$$
Fluorodeoxyglucose (^18^F-FDG or FDG) is very similar naturally occurring glucose however contains the radioactive fluorine-18 atom instead of an oxygen atom. This means that the compound is treated by the body as normal glucose, causing it to accumulate in tissues with a high rate of respiration where the glucose is usually broken down into carbon dioxide, water and adenosine triphosphate (ATP). This is a good example of radioactive labelling. 

Other tracers could however involve the use of carbon-11 monoxide. This isotope of carbon also undergoes positron emission decay and has a half life of 20 minutes making it similarly suitable for use in PET scanning. The benefit of using this type of tracer instead of an FDG tracer is the fact that carbon monoxide forms carboxyhaemoglobin upon making contact with red blood cells, causing the carbon-11 isotopes to be chemically bound to red blood cells as they travel around the body - allowing for these circulatory systems to be monitored.

<center><figure><img src=".\fig\D5gETaZ.png" width="200px" /> <figcaption> Fig. 3 - Whole body PET scan using <sup>18</sup>F-FDG </figcaption></figure></center>
#### The Mechanisms that allow PET Scanners to Function

The PET scanner is made up of a horizontal bed surrounded by a gamma detector ring. Each detector is made up of  a lead collimator, a scintillator, a light guide and a honeycomb array of photomultiplier tubes (the workings of which were explained in an earlier section of this paper). This gamma 'camera' detects the gamma photons emitted from the electron-positron annihilation and an image can therefore be constructed detailing the concentration of the tracer in different parts of the patient's body. Often colour coded (see *Fig. 3*). 

<center><figure><img src=".\fig\1.png" width="500" /> <figcaption> Fig. 4 - A typical PET scanner unit </figcaption></figure></center>
Antiparallel gamma photons travel through the patient towards the collimator which is made up of lead tubes. These ensure that gamma photons are travelling at the correct angle, as lead will absorb the stray photons. This requirement is mitigated however by the cylindrical shape of the PET scanner, provided the source of photons is near the centre.

Photons which pass the collimator then release the scintillator which is often made of sodium iodide. An incoming gamma photon striking the scintillator produces many scintillation photons of visible light through the excitation of an electron level or a vibrational level^[8]^. Only about 10% of incident gamma photons interact with the scintillator. These photons of visible light then travel through light guides into photomultiplier tubes which convert them to small pulses of voltage that can be recorded. The positions of these incoming gamma photons can then be computed using complex software which takes into account the uncertainties involved in the quantum process (for example the emitted gamma photons from electron-positron annihilation pair production can be ±0.5° from being antiparallel^[7]^). The computer can determine the exact point at which pair production took place using these uncertainties along with the small differences in arrival times of these photons at the two opposite gamma detectors, and a tomography model can be produced using colour and brightness to display the concentrations of radiotracer in different areas of the patient.

#### Safety Considerations and Disadvantages Associated with PET Scan Usage

During positron emission tomography body tissue is exposed to radiation due to the inserting of a radiotracer into the patient. Exposure to radiation can be carcinogenic in the longer term, however it is almost universally agreed that the benefits of PET scans far outweigh the negative consequences of this exposure to radiation for the patient^[9]^.  The typical radiation dosage from a PET scan of about 25mSv^[3]^ is roughly ten times the average UK yearly dose however this is seen as a small issue compared with the many uses of these scans including autopsy confirmation, tumour/infection identification, Alzheimer's and dementia treatment.

The major disadvantage of the PET scan however is simply the cost.^[2]^ The particle accelerators required to produce the fluorine-18 FDG are uncommon and the scanners themselves are only found at larger hospitals. These factors combined with the high skill level required by the radiologists analysing the scan results mean the test is only recommended for patients with complex health problems or for research purposes. This is especially the case as these scans are often used in conjunction with CT and MRI scanning technology in order to get a full picture of the biomechanical processes in the patient.^[1]^

#### The Future of PET Scanning Technology

There are many current and potential future applications for PET scanning for medical uses however there are still limitations with the current availability of technology.  Since the start of technical developments in PET instruments in the late 20th century there have however been major improvements in the precision and fidelity of imaging. There is no reason to believe that these developments cannot continue however there will need to be a combined effort from intellectuals within the particle physics and medical engineering field, along with commercial incentives. The main improvements which aim to be made along with the improvements to imaging detail are as follows. ^[11]^

- The effective sensitivity of the detectors at higher count rates is lower than usual due to the level of random coincidences and detector dead time (the minimum time interval that two consecutive counts must be separated in order to be recorded as two different events). 
- There is still resistance to the use of PET scans for health-check screening due to the radiation doses still being too high for babies, children and pregnant women. If studies could be performed with lower doses of radiation then they could be seen as effectively harmless, similar to that used in screening at airport security.
- The increasing appreciation of the need to look at whole-body systems in order to diagnose patients, such as in physical-mental conditions. The use of tracers which underpins PET imaging could prove useful in the future of this field of 'systems biology'.

#### Conclusion

Since the 1970s positron emission tomography has been developed into the complex, precise computational system that it is now. ^18^F-FDG compounds are currently the most common form of radiopharmaceutical used in the PET imaging process  and manmade fluorine-18 from particle accelerators is an expensive ingredient in the process. Pair production from electron-positron annihilation is used to locate and calculate tracer concentrations in the patient's body, and this produces images which can be analysed by radiologists. Just as PET scanning technology has continued to develop to this day, and will likely continue in the future - with the current main focus for development being on systems biology. There is no doubt the impact of this field of study and process has been positive on the medical world in cancer research, but also in neurological conditions such as dementia.

#### References

1. Advisory.com. (2020). *The present and future of PET in imaging*.  [online] Available at:  https://www.advisory.com/research/imaging-performance-partnership/the-reading-room/2017/05/pet-imaging [Accessed 17 Feb. 2020]. 
2. Bone, G., Chadha, G. and Saunders, N. (2015). *A Level Physics for OCR A*. Oxford University Press, pp.476, 528, 531-2.
3. Cancer.org. (2020). *Understanding Radiation Risk from Imaging Tests*. [online] Available at:  https://www.cancer.org/treatment/understanding-your-diagnosis/tests/understanding-radiation-risk-from-imaging-tests.html [Accessed 17 Feb. 2020]. 
4. Cancer Research UK. (2020). *Cancer Statistics for the UK*.  [online] Available at:  https://www.cancerresearchuk.org/health-professional/cancer-statistics-for-the-uk [Accessed 18 Feb. 2020].
5. Joliot F, Curie I. *Artificial production of a new kind of radio-element.* Nature 1934;204 In: Brucer M, Harris CC, MacIntyre WJ, Taplin GV. The Heritage of Nuclear Medicine. Reston, VA: Society of Nuclear Medicine; 1979 
6. Kevles BH. *Naked to the Bone: Medical Imaging in the Twentieth Century.* New Brunswick, NJ: Rutgers University Press; 1997
7. K. J. Cohen, S. Homma, D. Luckey, and L. S. Osborne Phys. Rev. 173, 1339 *Wide-Angle Electron-Positron Pair Production* – Published 25 September 1968 doi: https://doi.org/10.1103/PhysRev.173.1339
8. Leo, William R. (1994). *Techniques for Nuclear and Particle Physics Experiments* (2nd ed.). Springer. doi:10.1007/978-3-642-57920-2. ISBN 978-3540572800.
9. Nicolaas I. Bohnen, David S.W. Djang, Karl Herholz, Yoshimi Anzai and Satoshi Minoshima  (2011) *Effectiveness and Safety of FDG PET in the Evaluation of Dementia* Doi: 10.2967/jnumed.111.096578Published online: December 15, 2011.2012;53:59-71.J Nucl Med.
10. Semin, Oncol. (2011) *Metabolic PET Imaging in Cancer Detection and Therapy Response* 38(1): 55–69. doi:10.1053/j.seminoncol.2010.11.012. 
11. Terry, Jones., David, Townsend., Terry, Jones., *History and future technical innovation in positron emission tomography* J. Med. Imag.4(1), 011013 (2017), doi: 10.1117/1.JMI.4.1.011013. 
12. Your.MD. (2017). *PET scan - Your.MD*. [online] Available at: https://www.your.md/condition/pet-scan#risks [Accessed 17 Feb. 2020]. 
