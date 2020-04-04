# AddPopInfoToODBPP
Adds the populated/not populated info to Altium Designer ODB++ Output

- ODB++ Data is generated by standard Altium Designer Outjob
- A reduced Bom with only the used component designators is created
- The Bom is read by the script and the populated/not populated information from the bom is written to the component files in the ODB++ Data. After that the ODB++ folder structure is stored in the original .tgz-file.

Usage:
Add both files (Output Job and Scipt file) to your Altium Designer Project.
In the Output job, set the Data Source to your PCB and select the desired variant.
Check that sure the script is executed last in the Output Job and click on generate content.
Now the ODB++ Data is genberated for the selected variant.