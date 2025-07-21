
<p align="center">
<img src="https://github.com/user-attachments/assets/18ad3af8-10a8-4c7b-af96-976d3cb8694f", width="300", height="300">
</p>

<h1 align="center">DEDSEC_TIKTOKVB</h1>
<h4 align="center">DEDSEC_TIKTOKVB is a TikTok Phishing Attack Simulation Tool designed for ethical hacking, security awareness, and educational purposes. It focuses on spear-phishing scenarios by leveraging automation for realistic attack simulations, including email delivery and profile cloning.</h4>

### DESCRIPTION
DEDSEC_TIKTOKVB is purpose-built to simulate spear-phishing attacks targeting TikTok users. This tool automates key components of a phishing campaign to demonstrate how attackers might operate. It highlights the importance of understanding phishing methods and strengthens awareness of social engineering threats. 

### Key Features:

- **Username & Target Email-Based Phishing:** Only the target's username and email are required. The tool automates the creation and delivery of phishing materials.
- **Automated Profile Picture Cloning:** Automatically downloads the target's TikTok profile picture to craft a convincing spear-phishing page.
- **Custom Spear-Phishing Page Creation:** Generates realistic phishing pages using the harvested profile picture and user information to enhance credibility.
- **Automated Email Delivery:** Includes a built-in emailer to automatically send the phishing page to the target's email address, simulating a real spear-phishing attack.
- **OTP Simulation:** Supports scenarios where the phishing page prompts for OTP (One-Time Password), capturing both credentials and OTP codes for educational simulation.
- **Realistic Phishing Pages:** Accurately replicates TikTok's login interface to increase the realism of the phishing simulation.
- **Verified Badge Social Engineering:** Uses the bait of offering a TikTok "verified badge" to lure users into providing their login details, making the phishing attempt appear as part of an official verification process.

This tool emphasizes how attackers can leverage publicly available information to craft convincing phishing attempts. It is strictly for ethical and educational use only.

### TECHNIQUE
When a victim enters their credentials, you should access the original website and use those credentials to generate and send a legitimate OTP to the victim. Once the victim enters that OTP, you will also have it, giving you the ability to access the account before they do.

### SCREENSHOT 
<p align="center">
<img src="https://github.com/user-attachments/assets/1d3429d6-b4c0-4db4-b6ce-5a53fac2ed08", width="500", height="500">
<img src="https://github.com/user-attachments/assets/d664c6c2-c4a5-4ae5-8169-5587aea55c27", width="500", height="500">
<img src="https://github.com/user-attachments/assets/a7284588-065f-4e4e-8d0d-7ba45329eaee", width="500", height="500">
<img src="https://github.com/user-attachments/assets/687f0ff9-1c58-4f1d-8415-77ed58fdf403", width="500", height="500">
</p>

### HOW TO GET YOUR GMAIL KEY
   1. goto this link: https://myaccount.google.com/u/0/apppasswords

<p align="center">
<img src="https://i.stack.imgur.com/Xe8Jt.gif", width="800", height="800">
</p>
   2. then copy your email and app_password

### INSTALLATION 
    * git clone https://github.com/0xbitx/DEDSEC_TIKTOKVB.git
    * cd DEDSEC_TIKTOKVB
    * pip3 install beautifulsoup4 tabulate tqdm
    * chmod +x dedsec-tiktokvb

    to run:
    * ./dedsec-tiktokvb
    
    or
    
    * sudo apt install ./dedsec-tiktokvb.deb
    * dedsec-tiktokvb
    
### TESTED ON FOLLOWING
* Kali Linux 
* Parrot OS
* Ubuntu
  
## Support

If you find my work helpful and want to support me, consider making a donation. Your contribution will help me continue working on open-source projects.

**Bitcoin Address: `36ALguYpTgFF3RztL4h2uFb3cRMzQALAcm`**
                         

### DISCLAIMER
                                       TO BE USED FOR EDUCATIONAL PURPOSES ONLY

The use of the DEDSEC_PHISH is COMPLETE RESPONSIBILITY of the END-USER. Developers assume NO liability and are NOT responsible for any misuse or damage caused by this program. 
