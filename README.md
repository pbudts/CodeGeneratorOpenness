# CodeGeneratorOpenness
Siemens TIA Portal Code Generator via Openness Interface

Based on the description found here:

https://support.industry.siemens.com/cs/attachments/109477163/TIAPortalOpennessenUS_en-US.pdf (English)
https://cache.industry.siemens.com/dl/files/163/109477163/att_926040/v1/TIAPortalOpennessdeDE_de-DE.pdf (Deutsch)


This version is based on TIA V16.
<br>
With some small changes this will also work with 14SP1,15 or 15.1 (work ongoing)
<br>
<br>
Functions added:<br>
<br>
-open TIA with interface (first instance or new instance)<br>
-open project file via file dialog<br>
-compile software<br>
-save project<br>
-close project<br>
-show folder structure software<br>
-show data types<br>
-add / delete groups in the treeview<br>
-imports PLC blocks (with rename if needed)<br>
-import data types<br>
-export blocks / types<br>
-export project text (de/en)<br>
-import project text (de/en)<br>
<br>
Test<br>
-add / change language for editing<br>
-for devolpment set the key in the registry to avoid firewall each time<br>
<br>
Limtitations:<br>
-no global search for block/types<br>
-import fails if language is not in the project<br>
-export projects text can not overwrite existing files
<br>
<br>
Screenshot:
<br>
<img src="https://raw.githubusercontent.com/mking2203/CodeGeneratorOpenness/master/CodeGenerator.png" alt="Code Generator">

<br>
<br>
Some code for the Graph generation is "reversed engineered" since there is no description.

