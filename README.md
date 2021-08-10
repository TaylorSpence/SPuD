# SPuD
Stalk Puncture Device

**This Stalk Puncture Device and the puncture analysis method are patented: Method and Apparatus for Analyzing Stalk Strength. US patent 17/109,989. Issued June 3, 2021. Inventors are: Robertson D.J., Cook D., Seegmiller W., Spence T., Seegmiller K., Stucker A.**

**3D Print STLs.zip:** This .zip file contains .STL files for every 3D printed part needed for the construction of the SPuD. Files are named CAD01, CAD02, etc. Descriptions linked to these file names can be found in the SPuD BOM.xlsx file or in the bill of materials section of the thesis.

**Final SPuD Arduino Code.zip:** This .zip file contains folders with the full arduino code for the Arduino Mega (Main) and Arduino Uno (Slave). Some libraries may need to be downloaded to run the code. Needed Libraries and the version of them used (some may not be the lastest versions) can be found as comments in the first few rows of the Main Arduino code. 

**IPS Analysis.zip:** This .zip file contains everything needed to run the full IPS analysis of the SPuD and Instron data in Matlab and all of the outputs of the analysis. It includes the Matlab code, a copy of all the raw instron and SPuD data, and --------. To run the code open ---- in matlab and change the active folder to ----. Then open --- and ----. Then run the code. The outputs should be ---. You can see all these outputs without having to run the code yourself by looking at the --- folder.

**Inston and SPuD Naming Alignment.xlsx:** Due to the 8 character limitation of the SPuD's file naming capabilites the full barcode had to be condensed when naming the raw data files from the SPuD. While it is not difficult to figure out how these shortened names align with the full barcode, this excel file verifies which barcode relate to which SPuD file.

**Laser Cut DXFs.zip:** This .zip file contains the two .dxf files needed to laser cut the top (LASER01) and bottom (LASER02) covers of the SPuD.

**Mill Drawing PDFs.zip:** This .zip file contains engineering drawing PDFs for each machined component needed to build the SPuD. All machined components were machined on a manual mill or turned on a manual lathe. Files are named MILL01, MILL02, etc. Descriptions linked to these file names can be found in the SPuD BOM.xlsx file or in the bill of materials section of the thesis.  

**Minor Diameter Analysis.zip:** This .zip file contains everything needed to run the full minor diameter analysis...

**Raw Instron Data.zip:** This .zip file contains a .csv file for every puncture test run on the Instron that was used to compare against the SPuD tests. These .csv files contain the raw data from the test and include columns for time, position, and force.

**Raw SPuD Data.zip:** This .zip file contains a .csv file for every validation puncture test performed on the SPuD. These .csv files contain the raw data from the test and include columns for position, which is in millimeters, and force, in newtons.

**SPuD BOM.xlsx:** This excel file contains every component in the SPuD along with columns of useful information for each, such as the manufacturer, part number, a web link to the item, weights for 3D printed items, materials, prices, quantities, etc. 

**SPuD CAD 1-4:** Github's file size limitation required CAD files for the SPuD to be split between four .zip files. In order for the assemblies and main assembly (SPuD.sldasm) to open without errors all zip files must be opened and the contents should be combined into a single folder. Within these .zip files is every SolidWorks part and assembly to create the full SPuD model. The SolidWorks drawings for milled components are included as well.   

**SPuD CAD Renders.zip:** This .zip file contains several CAD renders of the SPuD.

**SPuD Wiring V3.pdf:** This .PDF contains the colored wiring schematic for the SPuD as guide for wiring the device. 
