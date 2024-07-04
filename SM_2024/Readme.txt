Title "Stable polydisperse free-standing porous films made by mechanical deformation"
Authors: Hsiao-Ping Hsu and Kurt Kremer

Journal: Soft Matter

Simulations are done using the package ESPResSo++
https://espressopp.github.io/

The data presented in the article and SI are stored in the following two directory

********************
 MS_data: ./MS_data
********************

1) Data plotted in Figs.2-4, 6-12, 14-17 using gnuplot
   e.g. pl "MS-pdfig02a.txt" --> get Fig.2a

2) Data plotted fin Figs.5 and 13 using vmd

3) Data structure of chain configurations in *.gz files  (Data (large size) obtained from authors upon request)
   e.g. pdgbienw4_0.xyz3.gz
------------------------------------------------------------------------------------------------------
# total number of monomers: 2000000 (1000*1900+1000*100)
# simulation box size:      193.7057320000  134.1693792308  134.1693792308
# monomer k | coordinate x | y | z | velocity v_x | v_y | v_z  
0   40.6946107635    0.6202776026   66.3549634605   -0.6111896107    0.0473689942    1.3537297302

# monomers k=1900*0 ~ 1900*1-1      chain i=0 of chain size N=1900
# monomers k=1900*1 ~ 1900*2-1      chain i=1 of chain size N=1900
...
# monomers k=1900*999 ~ 1900*1000-1 chain i=999 of chain size N=1900
# monomers k=1900*1000+100*0 ~ 1900*1000+100*1-1 chain i=0 of chain size N=100
# monomers k=1900*1000+100*1 ~ 1900*1000+100*2-1 chain i=1 of chain size N=100
...
# monomers k=1900*1000+100*999 ~ 1900*1000+100*1000-1 chain i=999 of chain size N=100
------------------------------------------------------------------------------------------------------

======================================================================================================
Fig.1: chains i=41,56,57,63,65,69 in pdgbienw4_0.xyz3,gz, pdgbienw4_305.xyz3.gz, pdgbienw4_331.xyz3.gz
Fig.2: MS-pdfig02a.txt, MS-pdfig02b.txt, MS-pdfig02c.txt, MS-pdfig02d.txt
Fig.3: MS-pdfig03a.txt, MS-pdfig03b.txt, MS-pdfig03b-inset.txt 
Fig.4: MS-pdfig04.txt
Fig.5: pdbienw4_0.xyz3.gz, pdnvtn4_600.xyzt0.gz, pdnvtn4_1200.xyzt0.gz
Fig.6: MS-pdfig06a.txt, MS-pdfig06b.txt, MS-pdfig06c.txt
Fig.7: MS-pdfig07a.txt, MS-pdfig07b.txt
Fig.8: MS-pdfig08a.txt, MS-pdfig08b.txt
Fig.9: MS-pdfig09a.txt, MS-pdfig09b.txt, MS-pdfig09c.txt
Fig.10: MS-pdfig10a.txt, MS-pdfig10b.txt
Fig.11: MS-pdfig11a.txt, MS-pdfig11b.txt
Fig.12: MS-pdfig12.txt
Fig.13: pdnvtn4_60.xyzt0.gz, pdnvtn4_60.xyzt12.gz, pdnvtn4_60.xyzt20.gz
Fig.14: MS-pdfig14a.txt, MS-pdfig14b.txt
Fig.15: MS-pdfig15a.txt, MS-pdfig15b.txt
Fig.16: MS-pdfig16a.txt, MS-pdfig16b.txt, MS-pdfig16c.txt, MS-pdfig16d.txt
Fig.17: MS-pdfig17.txt
======================================================================================================

********************
 SI_data: ./SI_data
********************

1) data plotted in Figs.S1,S2,S4,S5,S8 using gnuplot

2) data plotted in Figs.S3,S6,S7 using VMD

======================================================================================================
Fig.S1: SI-pdfig01.txt
Fig.S2: SI-pdfig02a.txt, SI-pdfig02b.txt
Fig.S3: chains i=176,271,627,645,658,879 of N=100
        in ./MS_data/pdbienw4_0.xyz3.gz and ./MS_data/pdbienw4_331.xyz3.gz
Fig.S4: SI-pdfig04a.txt, SI-pdfig04b.txt, SI-pdfig04c.txt
Fig.S5: SI-pdfig05a.txt, SI-pdfig05b.txt
Fig.S6: ./MD_data/pdbienw4_0.xyz3.gz,pdnvtn4_100.xyzt0.gz,pdnvtn4_200.xyzt0.gz,
        pdnvtn4_400.xyzt0.gz,pdnvtn4_800.xyzt0.gz,pdnvtn4_1200.xyzt0,
        pdnvtn4_1800.xyzt0, pdnvtn4_2400.xyzt0
        at t[10^6\tau]=0,0.05,0.1,0.2,0.4,0.6,0.9,1.2
Fig.S7: ./MD_data/pdbienw4_0.xyz3.gz,pdnvtn4_1200.xyzt0.gz
        at t[10^7\tau]=0,1.2
under the directory SI_data
Fig.S8: SI-pdfig08a.txt, SI-pdfig08b.txt, SI-pdfig08c.txt
======================================================================================================


