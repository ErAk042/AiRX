# AiRX
AiRX is a modularized fully-analog superheterodyne AM radio receiver for the aviation band (117-140MHz). The system consists of an input filter + LNA, a LNA + mixer stege for converting the band to 7-30MHz range, a Xtal oscillator at 110MHz as the first LO, and a LA1267 based AM radio to demodulate the signal with an additional LM386 amp for driving speakers.

## Input Stage
The input stage is a 9th order bandpass filter (117-40MHz passband) made using high-q aircore inductors. Right after the filter, there is a LNA block made using the BFP196W RF transistor. Bias network is made using a BC807 PNP transistor. The circuit aims to provide a 15mA current flow over the RF transistor. The overall gain of the LNA block here is around 15dB. 
