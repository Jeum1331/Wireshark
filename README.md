## Wireshark: Ultimate Hands-On Course Practice

# 🛠 About This Repository

This repository documents my hands-on practice with Wireshark. Based on the Wireshark Ultimate Hands-On Course, this project showcases my learning journey, packet analysis techniques, and practical applications of network forensics.

# 🔍 Skills Practiced

Packet Capturing & Filtering: Capturing live network traffic and applying display filters.

Protocol Analysis: Understanding and analyzing protocols like TCP, UDP, HTTP, DNS, ARP, ICMP, and TLS.

Security & Threat Detection: Identifying network anomalies, suspicious packets, and potential cybersecurity threats.

Performance Troubleshooting: Diagnosing network issues such as high latency, packet loss, and congestion.

Custom Filters & Expressions: Writing Wireshark display and capture filters for targeted analysis.

Exporting & Reporting: Extracting and interpreting packet data for documentation and reporting.

# 📂 Repository Contents

Packet Captures (.pcap files): Sample network traffic captures with annotations.

Filtering Cheat Sheet: Useful Wireshark filter expressions for efficient packet analysis.

Case Studies & Findings: Documented real-world network issues and security threats identified through Wireshark.

Custom Wireshark Profiles: Pre-configured color rules and display filters for different analysis scenarios.

Scripts & Automation: Python scripts leveraging pyshark for automated packet inspection.

# 🖥️ Using Special Filter Operators
<table border="1">
  <tr>
    <td>REQUEST</td>
    <td>QUERY</td>
    <td>PACKETS DISPLAYED</td>
    <td>DEMONSTRATION</td>
  </tr>
  <tr>
    <td>1.DNS Packets(no ICMP)</td>
    <td>dns and !icmp</td>
    <td>52</td>
    <td><img src="https://github.com/user-attachments/assets/2a1be0be-30f8-4793-9cda-ff3fdf7fea30" alt="DNS Packet Screenshot"></td>
  </tr>
  <tr>
    <td>2.DNS including the word "foundation"(Regardless of case)</td>
    <td>dns matches "foundation" and !icmp </td>
    <td>34</td>
    <td><img src="https://github.com/user-attachments/assets/18c7e066-05e9-46aa-a81a-a29eb5b39aa3" alt="DNS matches Screeshot"></td>
  </tr>
  <tr>
    <td>3.DNS requests for domains that do not have the word "foundation" </td>
    <td>dns and !dns matches "foundation" and !icmp</td>
    <td>18</td>
    <td><img src="https://github.com/user-attachments/assets/aff0a025-1215-494f-a275-1de52df7a235" ></td>
  </tr>
  <tr>
    <td>4.TCP port 443</td>
    <td>tcp.port in {443}</td>
    <td>885</td>
    <td><img src="https://github.com/user-attachments/assets/db2a63c1-f24d-42f3-9a82-0ac6263efc80"></td>
  </tr>
  <tr>
    <td>5.ICMP packets (What port was unreachable?)</td>
    <td>icmp</td>
    <td>1 port 49679</td>
    <td><img src="https://github.com/user-attachments/assets/29d0f02e-f4c5-4fb5-9165-6d5f9e0d6155"></td>
  </tr>
  <tr>
    <td>6.How many packets are in the top IP conversation?</td>
    <td>watch video</td>
    <td>481</td>
    <td> <video width="320" height="240" controls>
        <source src="https:https://drive.google.com/file/d/1N-5Zrhz6EB7dbwl-XOVTtDGToiAkncVL/view?usp=sharing" type="video/mp4">
      </video>
  </tr>
  <tr>
    <td>Row 8, Cell 1</td>
    <td>Row 8, Cell 2</td>
    <td>Row 8, Cell 3</td>
  </tr>
  <tr>
    <td>Row 9, Cell 1</td>
    <td>Row 9, Cell 2</td>
    <td>Row 9, Cell 3</td>
  </tr>
  <tr>
    <td>Row 10, Cell 1</td>
    <td>Row 10, Cell 2</td>
    <td>Row 10, Cell 3</td>
  </tr>
  <tr>
    <td>Row 11, Cell 1</td>
    <td>Row 11, Cell 2</td>
    <td>Row 11, Cell 3</td>
  </tr>
    <tr>
    <td>Row 12, Cell 1</td>
    <td>Row 12, Cell 2</td>
    <td>Row 12, Cell 3</td>
  </tr>
</table>








https://github.com/user-attachments/assets/


