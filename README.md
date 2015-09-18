# Umpire-MS1Quant
Umpire MS1 quantitation and feature detection analysis

The program does feature detection and assigns MS1 intensity to pep IDs from pepXML.

Command:
command : java -jar -Xmx8G MS1Quant.jar mzMXL_file ms1quant.params PepXML_file MinProb [Option]

Options
    -ID     Detect identified feature only
  
Ex: java -jar -Xmx15G Umpire-MS1Quant/Umpire-MS1Quant.jar test.mzXML ms1quant.params test.pep.xml 0.7 -ID

Once the job is done, you can find the following files at the same folder where the mzXML is located.
*_PepIonIDs.csv
*_PSMs.csv
