  <pre>

   ▄█    █▄       ▄████████  ▄█        ▄█               ▄████████    ▄█    █▄       ▄████████  ▄█        ▄█       
  ███    ███     ███    ███ ███       ███              ███    ███   ███    ███     ███    ███ ███       ███       
  ███    ███     ███    █▀  ███       ███              ███    █▀    ███    ███     ███    █▀  ███       ███       
 ▄███▄▄▄▄███▄▄  ▄███▄▄▄     ███       ███              ███         ▄███▄▄▄▄███▄▄  ▄███▄▄▄     ███       ███       
▀▀███▀▀▀▀███▀  ▀▀███▀▀▀     ███       ███            ▀███████████ ▀▀███▀▀▀▀███▀  ▀▀███▀▀▀     ███       ███       
  ███    ███     ███    █▄  ███       ███                     ███   ███    ███     ███    █▄  ███       ███       
  ███    ███     ███    ███ ███▌    ▄ ███▌    ▄         ▄█    ███   ███    ███     ███    ███ ███▌    ▄ ███▌    ▄ 
  ███    █▀      ██████████ █████▄▄██ █████▄▄██       ▄████████▀    ███    █▀      ██████████ █████▄▄██ █████▄▄██ 
 
 </pre>
 <br>

[![release](https://github.com/DJStompZone/HellShell/actions/workflows/msbuild.yml/badge.svg)](https://github.com/DJStompZone/HellShell/actions/workflows/msbuild.yml) ![GitHub License](https://img.shields.io/github/license/djstompzone/hellshell) ![GitHub last commit](https://img.shields.io/github/last-commit/djstompzone/hellshell) [![Discord](https://img.shields.io/discord/599808270655291403?logo=discord)](https://discord.stomp.zone)




# Usage:
### HellShell Supports 3 types of obfuscated shellcode output, all as arrays:
* `MacFuscation`: Output The Shellcode As A Array Of Mac Addresses [ Example: `FC-48-83-E4-F0-E8`]
* `Ipv4Fuscation`: Output The Shellcode As A Array Of ipv4 Addresses [Example: `252.72.131.228`]
* `Ipv6Fuscation`: Output The Shellcode As A Array Of ipv6 Addresses [Example: `FC48:83E4:F0E8:C000:0000:4151:4150:5251`]
* Running The binary as is, will output the help screen, from there it is so easy to use, i added 3 other projects, to demonstrate how to call the decoder function.
* HellShell will output the shellcode and the code needed for decryption into a cpp file, so importing it to any other project should be a simple task :)
* You can even download the release from [here](https://github.com/DJStompZone/hellshell/releases/latest) and enjoy using hellshell directly 

# Based On :
* [hive ransomware deploys novel ipfuscation technique](https://www.sentinelone.com/blog/hive-ransomware-deploys-novel-ipfuscation-technique/)
* [BypassAnti-Virus](https://github.com/midisec/BypassAnti-Virus)

