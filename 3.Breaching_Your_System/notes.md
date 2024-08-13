# Breaching Your System

## Table of Contents

1. [Stopping the Imposters 🛑](#stopping-the-imposters)

   - [What is a Trojan? 🤔](#what-is-a-trojan)
   - [Ransomware vs. Viruses vs. Worms 📊](#ransomware-vs-viruses-vs-worms)
   - [Trojan Variants 🧩](#trojan-variants)
   - [Best Ways to Protect from Trojans 🛡️](#best-ways-to-protect-from-trojans)

2. [Getting in the Backdoor 🚪](#getting-in-the-backdoor)

   - [What Does Rootkit Mean? 🔍](#what-does-rootkit-mean)
   - [Impact of a Rootkit ⚠️](#impact-of-a-rootkit)
   - [How to Get into Your System? 🕵️‍♂️](#how-to-get-into-your-system)
   - [How to Defend Against Rootkits 🛡️](#how-to-defend-against-rootkits)

3. [Exploiting the Unknown 🌐](#exploiting-the-unknown)

   - [What is a Zero-Day Attack? ⚠️](#what-is-a-zero-day-attack)
   - [Antimalware Protection 🦠](#antimalware-protection)
   - [How to Protect Your System 🔒](#how-to-protect-your-system)

4. [Challenge: Recognizing IoT Threats 📈](#challenge-recognizing-iot-threats)
   - [Securing IoT Devices 🔒](#securing-iot-devices)

---

## Content

### Stopping the Imposters 🛑

#### What is a Trojan? 🤔

- **Definition:** A Trojan is malicious software that disguises itself as legitimate software to perform harmful actions or create a backdoor for unauthorized access.
- **Characteristics:**
  - **Appearance:** Appears harmless or useful.
  - **Function:** Can steal information, cause damage, or provide unauthorized access.

#### Ransomware vs. Viruses vs. Worms 📊

| Feature           | Ransomware                                               | Virus                                      | Worm                                              |
| ----------------- | -------------------------------------------------------- | ------------------------------------------ | ------------------------------------------------- |
| **Primary Goal**  | Encrypts files and demands ransom for decryption         | Attaches to files and spreads through them | Self-replicates and spreads across networks       |
| **Spread Method** | Typically through phishing emails or malicious downloads | Requires user action to spread             | Spreads automatically through network connections |
| **Impact**        | Data loss and financial loss                             | Corruption of files and system instability | Network congestion and system degradation         |
| **Protection**    | Regular backups, updated security software               | Antivirus, user education                  | Network security, regular software updates        |

#### Trojan Variants 🧩

- **Multifunctional or Modular Trojans:**
  - **Functions:**
    - Stealing passwords
    - Embedding a rootkit
    - Launching ransomware attacks

#### Best Ways to Protect from Trojans 🛡️

- Avoid risky websites
- Do not download programs from untrusted sources
- Be cautious with email attachments and links
- Use robust antimalware protection

### Getting in the Backdoor 🚪

#### What Does Rootkit Mean? 🔍

- **Definition:** A rootkit is a type of malware that allows an attacker to gain and maintain unauthorized access to a system by creating a backdoor.

#### Impact of a Rootkit ⚠️

- **Drilling Deeper into the Network:**
  - **Logic Bomb:** A rootkit can include logic bombs that trigger attacks at a specific time or under certain conditions.

#### How to Get into Your System? 🕵️‍♂️

- **Lure:** Attract individuals to malicious websites.
- **Deliver:** Distribute a Trojan and convince the victim to execute it.
- **Obtain:** Capture login credentials.
- **Embed:** Install a rootkit via a compromised removable flash drive.

#### How to Defend Against Rootkits 🛡️

- Use strong, unique passwords
- Be cautious with email links and attachments
- Utilize strong spam filters
- Employ comprehensive antimalware protection
- Regularly patch and update software

### Exploiting the Unknown 🌐

#### What is a Zero-Day Attack? ⚠️

- **Definition:** A zero-day attack exploits a previously unknown vulnerability in software that has not yet been disclosed or patched by the vendor.

#### Antimalware Protection 🦠

- **Malware Signature Detection:**
  - **Function:** Identifies known malware by its signature or pattern.
  - **Disadvantage:** Ineffective against unknown or zero-day attacks.
- **Zero-Day Attack Risk:**
  - **Significance:** Represents a major threat due to the lack of prior detection.

#### How to Protect Your System 🔒

- Monitor for virus- and malware-like behaviors
- Detect new and previously unpublished attacks, including zero-day threats

### Challenge: Recognizing IoT Threats 📈

#### Securing IoT Devices 🔒

- **Map All Connected Devices:** Keep track of all devices connected to the network.
- **Change Default Passwords and Settings:** Replace default credentials and adjust settings for security.
- **Patch Vulnerabilities:** Regularly update and patch IoT devices to fix security flaws.
- **Apply Network Segmentation:** Isolate IoT devices on a separate network to reduce risk.
