# RetroTector
RetroTector 

2021-05-04

----
• Download and uncompress the RetroTector package:
  ReTe1.0.1.zip
  
• See the included html documentation for setup

----
Quick start:

• Update full path to working directory in:

  ReTe1.0.1/Database/Configuration.txt
  
• Start command (Mac/Unix) for RetroTector in the 'ReTe1.0.1/' directory:

  java -Xmx1024m -classpath "RetroTector101.jar:." retrotector/RetroTector
  
• See the included html documentation for details:

  ReTe1.0.1/Documentation/RetroTector.html


• Start analyzing: 
1. Place the fasta file(s) in ~/ReTe1.0.1/Workplace/NewDNA/
2. Run "SweepDNA" from the RetroTector GUI "Execute" dropdown menu to process the fasta file(s) and generate folder(s) with script files in ~/ReTe1.0.1/Workplace/
3. Process all scripts automatically by navigating to  ~/ReTe1.0.1//Workplace/ in RetroTector GUI and run "SweepScripts" from the dropdown menu.
     This will process LTRID, ORFID and RetroVID in turn to generate results files.
4. Navigate to the results folder(s) in RetroTector GUI and use "Choose script" to select the summarized results file "001SelectedChains.txt"
5. Then "Execute script" in RetroTector GUI to view the results graphics

  	
----
Please cite RetroTector in publications:

	Sperber GO, Airola T, Jern P, Blomberg J.
	Automated recognition of retroviral sequences in genomic data--RetroTector.
	Nucleic Acids Res. 2007;35(15):4964-76.
	doi: 10.1093/nar/gkm515
	
----
Correspondence:	Patric.Jern@imbim.uu.se



