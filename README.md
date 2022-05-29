# helpers

*1) scancode_to_opossum_helper.sh* 

...is a short helper script which is supposed to ease the process of a) scanning for license information using scancode_toolkit, b) convert the results to a Opossum_UI readable format and c) input the result of the conversion into OpossumUI. 

The original idea was to also integrate ORT (Analyze, Download, Scan with ORT-Scancode, convert to OpossumUI, input to Opossum) - the code already contains the necessary commands, but for now, it is not recommended to use it. Also, in order to use the ORT tools, the tool will search for an ORT docker container. 

Prerequisites:

These tools need to be installed in one parent folder (eg. /home/scantools/)
- scancode_toolkit
- OpossumUI
- opossum.lib.sh 


Usage:

Download scancode_to_opossum_helper.sh and use it like 

  $ bash scancode_to_opossum_helper.sh 

The tool will then guide you through the process.
