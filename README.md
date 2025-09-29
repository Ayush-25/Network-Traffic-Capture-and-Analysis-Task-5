# Network-Traffic-Capture-and-Analysis-Task-5
Capture live network packets and identify basic protocols and traffic types. This task helps develop awareness of network communication, protocol analysis, and traffic inspection using Wireshark.
## Tools Used
- **Wireshark (Free)**  
- **Web Browser** (for generating traffic)   
- Target: Local PC 

---

## Methodology and Steps

### Step 1: Install and Open Wireshark
Downloaded and installed Wireshark from the official website: [https://www.wireshark.org/download.html](https://www.wireshark.org/download.html)  
Verified installation and opened the application.

*Screenshot:*  

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/cc89c4a6-d6e0-4c91-a993-d916de81ae2a" />

---

### Step 2: Start Capturing Packets
Selected the active network interface (Wi-Fi / Ethernet).  
Clicked the blue shark fin icon to start capturing live network traffic.

*Screenshot:*  
<img width="1919" height="1022" alt="Screenshot 2025-09-29 162652" src="https://github.com/user-attachments/assets/2b1a6f2a-e36d-4d2a-8c35-f2babe9fa5de" />

---

### Step 3: Generate Network Traffic
While capture was running:

- Opened a browser and visited websites (e.g., `example.com`, `google.com`)  
- Pinged external servers via Command Prompt / Terminal:
ping google.com

### Step 4: Stop the Capture
After 30–60 seconds, clicked the red square (Stop Capture) button to end the capture.

---

### Step 5: Apply Protocol Filters
Applied display filters to focus on individual protocols:

- DNS → `dns`  
- TCP → `tcp`  
- HTTP → `http`

---

### Step 6: Identify Protocols

**DNS (Domain Name System)**  
- Expanded DNS packet in bottom pane.  
- Observed: Standard query for `google.com` → Response with IP `142.250.xx.xx`.

*Screenshot:* 
<img width="1919" height="689" alt="Screenshot 2025-09-29 162951" src="https://github.com/user-attachments/assets/536080d9-9f31-44d8-bb5c-fcad11f80ba0" />


**TCP (Transmission Control Protocol)**  
- Expanded TCP packet to observe 3-way handshake (SYN → SYN, ACK → ACK).  

*Screenshot:* 
<img width="1903" height="657" alt="Screenshot 2025-09-29 163023" src="https://github.com/user-attachments/assets/09d9d257-62f1-4977-a3ae-66ffbd753158" />


**HTTP (HyperText Transfer Protocol)**  
- Expanded HTTP packet to observe GET request for `www.example.com`.  

*Screenshot:* 
<img width="1919" height="946" alt="Screenshot 2025-09-29 163048" src="https://github.com/user-attachments/assets/74cbfd03-b32b-4693-ad15-a433dbcde32f" />

---

### Step 7: Export Capture File
Saved captured packets as `.pcap` file:

- File → Save As → Name:" Elevatelabs_Wireshark_Task5 "

---

### Step 8: Summarize Findings
- File uploaded.

---

## Contact
**Ayush Singh**  
Email: ayushsinghfeb2502@gmail.com
