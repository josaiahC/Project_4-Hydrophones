# <div align=center> Project 4: Hydrophones </div>

Josaiah Clark<br>
BME 450, Abadi<br>
3/11/20<br>

CODE: https://colab.research.google.com/drive/161-dOmloFs4CqVRI5MB-9r4blUs_owjX

## Introduction <br>


Power spectral density is a measurement of how power from a signal or ambient noise is distributed amongst a range of frequencies. In part 1, Power Spectral Density versus Frequency graphs were constructed to examine the effects of the following weather conditions on underwater noise: windy and rainy, rainy but not windy, windy but not windy, and neither windy nor rainy. 

Spectrograms use color maps to visualize the most intense frequency components of a noise over time. In part 2, spectrograms were used to compare bandwidth, intensity, and duration for marine mammal vocalization, airgun noise, and seismic activity due to a volcanic eruption.


## <div align=center> Part 1: Wind and Rain Noise </div>

### Oregon Shelf Surface Mooring
| | |
| --- | --- |
|Windy and Rainy|<img size=70% alt="hello" src=oregon_shelf_surface_mooring/WR.png><br>Figure 1|
|Rainy, but not windy|<img size=70% alt="hello" src=oregon_shelf_surface_mooring/RNW.png><br>Figure 2|
|Windy, but not rainy|<img size=70% alt="hello" src=oregon_shelf_surface_mooring/WNR.png><br>Figure 3|
|Not windy and not rainy|<img size=70% alt="hello" src=oregon_shelf_surface_mooring/NWNR.png><br>Figure 4|


### Oregon Offshore Surface Mooring
| | |
| --- | --- |
|Windy and Rainy|<img size=70% alt="hello" src=oregon_offshore_surface_mooring/WR.png><br>Figure 5|
|Rainy, but not windy|<img size=70% alt="hello" src=oregon_offshore_surface_mooring/RNW.png><br>Figure 6|
|Windy, but not rainy|<img size=70% alt="hello" src=oregon_offshore_surface_mooring/WNR.png><br>Figure 7|
|Not windy and not rainy|<img size=70% alt="hello" src=oregon_offshore_surface_mooring/NWNR.png><br>Figure 8|

## Spectral Level Comparison
At the Oregon Shelf Surface Mooring site, the  sound intensities for each weather condition are:
  1.  Windy and Rainy: Peak 74 dB/Hz, average 45.5 dB/Hz (Figure 1)
  2.  Rainy, but not windy: Peak 82 dB/Hz, average 55 dB/Hz (Figure 2)
  3.  Windy, but not rainy: Peak 71 dB/Hz, 52 dB/Hz (Figure 3)
  4.  Not windy and not rainy: Peak 60 dB/Hz, average 47 dB/Hz (Figure 4)
  
At the Oregon Offshore Surface Mooring site, the peak sound intensities for each weather condition are:
  1.  Windy and Rainy: Peak 92 dB/Hz, average 42 dB/Hz (Figure 5)
  2.  Rainy, but not windy: Peak 72 dB/Hz, average 38 dB/Hz (Figure 6)
  3.  Windy, but not rainy: Peak 72 dB/Hz, average 44 dB/Hz (Figure 7)
  4.  Not windy and not rainy: Peak 70 dB/Hz, average 50 dB/Hz (Figure 8)
  
At both locations, peak PSD levels were lowest in the absence of wind and rain. The average PSD levels, shown in each plot by a red line, still remained comparable to that of the other three weather conditions. Notably, in figure 4 there is a peak PSD of 82 dB/Hz at ~13,800 Hz, but it is unclear whether this is due to the weather or not. At the Oregon Shelf Surface Mooring site, rainy but not windy conditions clearly had the greatest effect on underwater noise, with peak and average levels exceeding all other conditions. At the Oregon Offshore Surface Mooring site, the highest peak was achieved during both windy and rainy conditions, withg the highest average level occuring during not windy and not rainy conditions. Thus, at this site both windy and rainy conditions had the greatest effect on underwater noise. 

In all cases, wind and rain increased PSD levels at very low frequencies, with decreasing influence on PSD levels at higher ones. The Oregon Shelf Surface Mooring site recorded peak PSD levels 10 dB/Hz higher than equivalent conditions at the Oregon Offshore Surface Mooring site, while the peak PSD level at the offshore site during windy and rainy conditions was 18 dB/Hz higher than the shelf site. Windy but not rainy PSD levels were nearly equal at both sites, and the offshore surface mooring site recorded peak PSD levels 10 dB/Hz higher than the shelf surface mooring site.

## <div align=center> Part 2: Airgun, Marine Mammals, Earthquake/Volcano Noise </div>

| | |
| --- | --- |
|Marine Mammal Vocalization|<img width=1900 alt="hello" src=spectrograms/mammals.png><br>Figure 9|
|Airgun Noise|<img alt="hello" src=spectrograms/airgun2.png><br>Figure 10|
|Axial Seamount Earthquake after volcanic eruption|<img alt="hello" src=spectrograms/earthquake.png><br>Figure 11|

In figure 9, the marine mammal vocalization signal appears to be composed of a wide range of sinusoidal frequency components ranging from 750-4500 Hertz; this is in agreement with the Wentz curve's 10- >100,000 Hz. The signal's duration is about four seconds, and its maximum intensity is around 80 dB. 

Figure 10 shows a series of three airgun shots, all within 0-1200 Hz. Airgun noises are created by bubbles, and the Wenz curve states that bubble noises are in the frequency range of 100 to approximately 20,000 Hz, which encapsulates the frequency range of this signal. The airgun signals are periodic, occuring about eighteen seconds apart and lasting 5-10 seconds. Each airgun noise has a maximum intensity of around 105 dB.

The seismic activity shown in figure 11 has a max frequency of ~130 Hz, which is close to the Wenz curve's range of 0-100 Hz. The primary signal has an intensity of around 150 dB, lasting almost 70 seconds.


