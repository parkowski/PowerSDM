# PowerSDM

## Instructions
1. Download/extract to your powershell modules folder
C:\Users\__YOUR_USERNAME__\Documents\WindowsPowerShell\Modules\
2. Run this in your powershell session:

  import-module wsdm-commands
3. Run your wsdm commands. Enjoy!

## Overview
Personal feelings aside, SDM could use some updates.

Chief of those is an alternative Powershell interface to avoid interacting with the standard interface.
This is an attempt to bridge that gap.

Former names (still under consideration):
- WSDM (stands for "Wither SDM"; sounds like Wisdom)
- SDM-Y (meaning "like SDM", i.e. Chocolatey, gooey; sounds like...)

## The following commands are available
- list tickets
- open new tickets
  
## Feature requests
single/multi-ticket processing:
- update DESCRIPTION
- update PRIORITY
- add comments
- transfer tickets /change assignee,group
- close
  
## Future Releases
The current commands use the SOAP WSDL API.
The next release will use REST.
