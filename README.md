# Cybersecurity_Internship_WK2_Batch-B084
# Cybersecurity Internship - Week 2 | Networkwalks (Batch B084)

This repository contains my practical lab work, command outputs, and final penetration testing report for **Week 2** of the Cybersecurity Internship with **Networkwalks** (Batch B084).

---

## 📋 Week 2 Modules Summary

During Week 2, I successfully completed the footprinting, reconnaissance, and network scanning modules (W2-PM1 to W2-PM5) along with the final penetration testing report on authorized targets (`networkwalks.com` and local subnet).

---

### 1. W2-PM1: Footprinting & Reconnaissance with Multiple Kali Tools
Performed passive and active information gathering on `networkwalks.com` using multiple Kali Linux command-line tools (`whois`, `nslookup`, `whatweb`, `curl`, `wafw00f`, and `dnsrecon`) to analyze domain details and server configurations.

* **Key Execution & Findings:**
  * Retrieved domain registration and ownership details via `whois`.
  * Queried DNS nameservers and records using `nslookup` and `dnsrecon`.
  * Identified web server headers, technologies, and WAF protections using `whatweb`, `curl`, and `wafw00f`.
W2-PM1 Output
<img width="1215" height="687" alt="06b281d2-48bc-4709-aead-ec0848f6539a" src="https://github.com/user-attachments/assets/65231078-054e-4bae-b6b9-9efbf66c5273" />
<img width="1306" height="706" alt="cc30d068-abca-4a3d-b5b5-67bf85be25c2" src="https://github.com/user-attachments/assets/f98d0a8f-88a9-400c-a37c-7c5d7c42ad70" />
<img width="1322" height="678" alt="ba69a3f3-7e7d-41ee-8227-615285118963" src="https://github.com/user-attachments/assets/ab0f6e16-cdf3-4ce6-9056-f87208123fde" />
<img width="1303" height="699" alt="d5b32b7b-3483-4976-ba42-730d8cd70cd1" src="https://github.com/user-attachments/assets/c22dbd1c-fa99-402d-b1bd-c2fce52221c6" />
<img width="1329" height="669" alt="c8231baf-a2c1-4582-8af2-bdd5a49c5de3" src="https://github.com/user-attachments/assets/9cd10f05-a33c-4924-83a1-e57e2cfb69cb" />
<img width="1329" height="691" alt="9ded90e5-3006-4efe-b374-fb201ffcb9aa" src="https://github.com/user-attachments/assets/10dd5b03-0f7e-400d-baac-b715de322fe2" />



---

### 2. W2-PM2: GHDB Based Footprinting Attacks
Exploited **Google Hacking Database (GHDB)** advanced operators (`site:`, `inurl:`, `intitle:`, `filetype:`) to discover publicly indexed sensitive files and directories without direct interaction with the target server.

* **Key Execution & Findings:**
  * Executed targeted search dorks to map public documents and subdomains.

## W2-PM2 GHDB Search
<img width="1342" height="712" alt="6831d51c-3573-4e28-8fb2-43748b7fed86" src="https://github.com/user-attachments/assets/1875ba4b-ea5a-454a-a623-814058c89340" />
<img width="1347" height="706" alt="e3dd6885-aa6e-41f2-9176-7691cb2b8232" src="https://github.com/user-attachments/assets/5d9827f5-025b-4e22-bff3-051f20d04fdf" />
<img width="1366" height="758" alt="a4f1f54c-aaa7-4a16-9734-526418d66d2e" src="https://github.com/user-attachments/assets/1037628d-2b98-4b12-ab5a-d00947a9fee2" />
<img width="1362" height="768" alt="63f76ab9-ce42-4eee-a1ad-e381893321c8" src="https://github.com/user-attachments/assets/9eb6be93-1b18-47bb-b8c1-1e11210467e9" />


---

### 3. W2-PM3: Maltego Based Footprinting Attacks
Employed **Maltego** for visual Open Source Intelligence (OSINT) gathering and infrastructure profiling on `networkwalks.com`.

* **Key Execution & Findings:**
  * Added domain entities and executed standard transforms to visually map DNS records, email accounts, and related infrastructure.

## W2-PM3 Maltego Graph 
<img width="1359" height="760" alt="adbc41a7-c81d-48ad-896a-31f51d651d92" src="https://github.com/user-attachments/assets/1699c68b-8da7-4fd3-99bd-d404c07a80fd" />
<img width="1358" height="758" alt="f3948ba9-ec50-4060-a78b-21c5669e332a" src="https://github.com/user-attachments/assets/53e9f9ef-af1f-4a2a-8174-37702d65eb42" />
<img width="1366" height="765" alt="3c4721f0-713d-44c1-89d9-3ce1ab30afc0" src="https://github.com/user-attachments/assets/74aef65d-d841-4986-a378-4307c4907d9d" />

---

### 4. W2-PM4: theHarvester Based Footprinting Attacks
Ran **theHarvester** in Kali Linux to harvest emails, subdomains, and hostnames from multiple public search engines and data sources.

* **Key Execution & Findings:**
  * Gathered external intelligence targeting `networkwalks.com`.

## W2-PM4 theHarvester Output 
<img width="1352" height="704" alt="74b5c2f5-6956-4ae4-a36b-14e687c78905" src="https://github.com/user-attachments/assets/c5edcde6-8abe-4d05-82b9-390d7485f022" />
<img width="1350" height="737" alt="441337fc-2777-4a46-aeb8-6ddeee5f2688" src="https://github.com/user-attachments/assets/2aad85d7-9552-4499-8700-bef41854f76c" />
<img width="1349" height="760" alt="de0be7b7-03c0-4d50-9610-6a1d28113f5f" src="https://github.com/user-attachments/assets/dfef06ba-5564-45c7-ad9d-06902c58ce68" />

---

### 5. W2-PM5: Zenmap Based Network Scanning
Conducted local network host discovery, port scanning, and topology mapping using **Zenmap / Nmap**.

* **Key Execution & Findings:**
  * Verified local IP configuration and subnet mask (`192.168.100.0/24`) via Command Prompt (`ipconfig /all`).
  *

  * Executed network scans to discover active hosts (`192.168.100.1`, `192.168.100.9`, `192.168.100.42`, `192.168.100.44`) and analyzed open ports/services.
  * Generated and captured the network topology map.

 W2-PM5 IP Configuration 
 <img width="1355" height="760" alt="2ea405ef-4091-4727-ac49-0233e2891f7a" src="https://github.com/user-attachments/assets/ab6ac23f-07b5-41ee-ae53-50e2c3301be1" />
 W2-PM5 Zenmap Scan Result 
 <img width="1353" height="768" alt="8c4c7138-1e43-477c-85fc-a7a47e7b3e81" src="https://github.com/user-attachments/assets/d9faa8be-414f-470f-955f-99de080e18d6" />
 W2-PM5 Topology Map
 <img width="1352" height="763" alt="6abcc8be-1255-4fc8-ba5a-72b335da818b" src="https://github.com/user-attachments/assets/63b39f1b-b3f5-492b-aa48-ed719857512e" />

---

## 🛠️ Tools & Environment
* **OS:** Windows 10 & Kali Linux (VirtualBox)
* **Reconnaissance Tools:** `whois`, `nslookup`, `whatweb`, `curl`, `wafw00f`, `dnsrecon`, GHDB, Maltego, theHarvester
* **Scanning Tools:** Zenmap / Nmap
