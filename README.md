# [KiwiApkProtect](https://en.kiwisec.com/product/online-encrypt.html)  

KiwiApkProtect is an encryption service for mobile android applications that helps Internet companies and individual developers protect core technologies and intellectual property rights.Users only need to provide the packaged APK file, which can integrate DEX file encryption, SO file shell, anti-secondary packaging and other security functions.For different application security requirements, different levels of security protection functions can be provided, such as high-intensity security confrontation, you can choose to use Java2C, code confusion or KiwiVM .
 


## Features and Advantages
* **Dex Packer:** The Ultimate Packer for Dex file, prevent java code extraction by dex2jar.
* **Function Encryption:** Extracting java functions from Dex files for encryption protection.
* **Java2C Encryption:** Translate Java code into C code and implement the protection of the Native.
* **So Packer:** The Ultimate Packer for So file, to prevent reverse analysis by IDA tool.
* **Memory Protection:** Protect memory data from memory dump, tampering and other attacks.
* **Anti-debugging:** Prevent applications from being debugged by GDB and IDA tools
* **Anti-secondary Packaging:** Signature verification to prevent piracy applications.
* **Self Protection:** Protecting the program's own code with virtualization

## Introduction
Android app encryption is an encryption service for mobile android applications that helps Internet companies and individual developers protect core technologies and intellectual property rights.Users only need to provide the packaged APK file, which can integrate DEX file encryption, SO file shell, anti-secondary packaging and other security functions.For different application security requirements, different levels of security protection functions can be provided, such as high-intensity security confrontation, you can choose to use Java2C, code confusion or KiwiVM .

* **Risk summary:**
Decompilation DEX files, decompilation SO files, stealing core technologies, stealing sensitive data, implanting malicious viruses, tampering with copyright information, cracking authorization code, cracking communication protocols, secondary packaging and many other security risks.

* **Source of risk:**

| level | describe | distribution | advice |
| - | :- | :-: | :- |
| 1 | Use apktool, dex2jar, jd-gui, baksmali and other tools to directly obtain Java code | 99% |crypt the DEX file, or encapsulate the core code in the SO file |
| 2 | DexExtractor and other automatic extractor tools are used to extract Java code dynamically from memory data | 10% | Integrated memory protection, anti-debugging function, and use Java2c technology to convert Java code into C code, and SO shell protection |
| 3 | Repair ELF files, decompile the restored SO files using IDA tools, and analyze the core code logic | 2% | Protect SO files with code obfuscation encryption |
| 4 | Eliminate the obfuscation code in SO file and restore the original code automatically | 0.5% | Virtualization encryption protection for core code |
| 5 | Custom CPU instructions can be analyzed and the original CPU instructions can be automatically restored | 0.001% | Customize upgrade virtualization solutions |

* **Function introduction:**

| name | describe | Whether free |
| - | :-: | -: |
| DEX function encryption | The dynamic function of DEX file is extracted and encrypted, and the dynamic decryption is executed at runtime to protect Java code<br/>__［The free version encrypts only 20% of the functions randomly, while the enterprise version encrypts all dynamic functions］__ | Free/Paid |
| SO with shell protection |SO file for shell protection，Prevent reverse analysis| Paid |
| DLL whole shell | ［Unity mobile game］DLL file overall shell protection, prevent.net Reflector and other tools to decompile extraction C# code | Paid |
| DLL function encryption | ［Unity mobile game］Extract and encrypt functions of DLL files and perform dynamic decryption at runtime to prevent complete C# code from being dumped in memory | Paid |
| Anti-secondary packing | When the application runs, the signature file is dynamically verified. If the verification fails, it will exit to avoid the generation of pirated applications | Free |
| Memory protection | Prevents an attacker from tampering with or dumping sensitive data in memory | Paid |
| anti-debug  | Prevent an attacker from attaching a debugger to the running APP and maliciously analyzing the execution process of the code | Paid |
| Anti-system acceleration hook | ［Mobile game］Prevent malicious plug-ins from tampering with the time of the mobile phone system to make the accelerators and ensure the fairness of mobile game | Paid |
| SO confounding encryption | C, C++ code in SO file for confusing encryption protection<br/>  | Paid |
| Java2C - confusion | Convert Java code into C code through Java 2c technology, and implement code obfuscation protection for Native layer | Paid |



## Documentation
You can find the KiwiApkProtect documentation [on the website](https://document.kiwisec.com/en/kiwiVM).  



## Introduce
Relying on the technical advantages of the team, KiwiSec focuses on next-generation technology and product development in mobile safety. After 8 years of accumulation in compiler security technology, and 3 years’ continuous research and development, the original KiwiVM virtual machine product has completely solved the problems of weak protection and poor compatibility inherent in traditional technologies such as hardening and obfuscation, providing a convenient and effective security solution.

[Learn more](https://en.kiwisec.com)

