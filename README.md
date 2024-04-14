## hashcat 6.2.6 fork with support for SCCM hashes (Mode 19580)
Based on this repo for adding support for SCCM hashes: https://github.com/MWR-CyberSec/configmgr-cryptderivekey-hashcat-module
Updated to include the following pull request: https://github.com/MWR-CyberSec/configmgr-cryptderivekey-hashcat-module/pull/3

Either download the pre-compiled released for Windows or Linux or compile from source
https://github.com/The-Viper-One/hashcat-6.2.6-SCCM/releases/tag/release

```
hashcat-6.2.6-SCCM.exe -m 19850 -a 0 $sccm$aes128$0000edec1400000010330000203300000e6600000000000008b5ea1dab29bdd0de62e6506b108b5c ignis-1M.txt rules\best66.rule
```

![image](https://github.com/The-Viper-One/hashcat-6.2.6-SCCM/assets/68926315/f409e945-a400-471d-ae46-385f88c2b85e)


### Happy Cracking!
