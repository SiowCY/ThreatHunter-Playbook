# APT12
## Description
[[Group/G0005|APT12]] is a threat group that has been attributed to China.[[CiteRef::Meyers Numbered Panda]] It is also known as DynCalc, IXESHE, and Numbered Panda.[[CiteRef::Moran 2014]][[CiteRef::Meyers Numbered Panda]]
## Attribution
| Tactic | Technique | Tool | Description |
|--------|---------|-------|---------|
| Command and Control | Commonly Used Port                   |   RIPTIDE | [[Software/S0003 RIPTIDE]] is a RAT that communicates with HTTP.[[CiteRef::Moran 2014]] |                                                                                             
| Command and Control | Standard Application Layer Protocol  |   RIPTIDE | [[Group/G0005 APT12]] has used [[Software/S0003 RIPTIDE]], a RAT that uses HTTP to communicate.[[CiteRef::Moran 2014]] |                                                              
| Command and Control | Data Obfuscation                     |   Ixeshe |  The [[Software/S0015 Ixeshe]] malware uses custom Base64 encoding schemes to obfuscate data command and control traffic in the message body of HTTP requests.[[CiteRef::Moran 2013]] |
| Command and Control | Standard Cryptographic Protocol      |   RIPTIDE | [[Group/G0005 APT12]] has used the [[Software/S0003 RIPTIDE]] RAT, which communicates over HTTP with a payload encrypted with RC4.[[CiteRef::Moran 2014]] |                           



