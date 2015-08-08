# Umpire-MS1Quant
Umpire MS1 quantitation and feature detection analysis

The program does feature detection and assigns MS1 intensity to pep IDs from pepXML.

Command:
java -jar -Xmx10G Umpire-MS1Quant/Umpire-MS1Quant.jar mzXML parameterFile pepXML MinProb

Ex: java -jar -Xmx15G Umpire-MS1Quant/Umpire-MS1Quant.jar test.mzXML ms1quant.params test.pep.xml 0.7

Once the job is done, you can find the following files at the same folder where the mzXML is located.
*_PepIonIDs.csv
*_PSMs.csv
