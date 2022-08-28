Program and additional information for the article "Automation of Temperature Measurement in Induction Motors of Hermetic Compressors Based on the Method of Temperature Rise by Resistance".

## Abstract
>Recent studies have proposed the use of artificial neural networks to establish a correlation between the cooling capacity of refrigeration compressors and the results of quick production quality tests. However, the temperature measurement method used in the tests reflects a high uncertainty in the estimated performance parameters, primarily because the measurement is performed on the compressor shell, which has large thermal inertia and does not accurately reflect the temperature changes observed during the tests. This study proposes a set of modules that allow the application of the method of temperature rise by resistance to estimate the winding temperature of the single-phase induction motor of the compressor in quick quality tests. The winding temperature is a better estimate of the temperature at which the refrigerant fluid enters the compression cylinder and its use solves many of the problems associated with the traditional method. Validation tests show that the proposed solution is capable of automating the measurement in a safe, agile, and metrologically more reliable manner than the method currently used in quick quality tests in the industry.

## Video Abstract
The video abstract explaining the project can be accessed by clicking in the following image:

<a href="https://youtu.be/eIDkS5pDKTE">
<img src="youtube_thumbnail.png?raw=true" width="50%" height="auto">
</a>

## Developed Solution

The set of modules that allow the application of the method of temperature rise by resistance is presented in the following image:

<img src="circuit_board.png?raw=true" width="60%" height="auto">

being:

- A - decoupling primary circuit
- B - relay logic safety circuit
- C - measurement relays
- D - unloading check circuit

Further graphical information about the circuits developed can be found on folder "circuits". The circuits and the printed circuit board are available. The application developed in LabVIEW to control the system, as shown on the video abstract, can be found under the name "App.vi".
