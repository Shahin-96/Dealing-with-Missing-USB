# Missing USB attack vector analysis and risk mitigation techniques

## Project Overview

This project involves assessing the attack vectors of a USB drive. The assessment examines the risks posed by finding a USB drive in a public space, such as a parking lot, and how it can be used by threat actors to exploit an organization. The project emphasizes adopting both the attacker and target perspectives to identify potential vulnerabilities and suggest mitigation strategies.

## Objectives

- Identify Attack Vectors: Analyze how a USB drive can be a potential attack vector for delivering malicious software or compromising data.
- Assess Risk: Evaluate the security risks associated with a lost USB drive found in a public area.
- Develop Mitigation Strategies: Propose security controls to mitigate the risks of USB-based attacks, such as USB baiting.

### Skills Learned

- Gained experience in evaluating risks related to external devices like USB drives and their potential for delivering malware.
- Developed an understanding of how an attacker might leverage lost devices for malicious purposes.
- Learned strategies for mitigating risks posed by external media and protecting organizational data from potential breaches.

### Tools Used

- Virtualization Software
- <a href="https://www.cisa.gov/news-events/news/using-caution-usb-drives"> CISA USB Security Tips</a>

## Steps

### Step 1: Inspect the USB Contents
Created a virtual environment to safely inspect the contents of the USB drive without risking network infection.
Discovered files belonging to Jorge Bailey, including both personal and work-related files.
### Step 2: Apply the Attacker Mindset
Considered how an attacker might use the information stored on the USB drive, including personal identifiable information (PII) and work-related data.
Identified potential threats, such as targeted attacks or unauthorized access to company data.
### Step 3: Analyze the Risks
Conducted a risk analysis on the potential threats posed by USB baiting attacks, including the types of malicious software that could be hidden on the device.
Proposed technical, operational, and managerial controls, such as disabling Autorun, employing sandbox environments for USB analysis, and educating employees on the risks of plugging an unknown USB drive into their computer.
