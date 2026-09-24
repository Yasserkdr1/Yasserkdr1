<p><img src="assets/intro.svg" width="100%" alt="Yasser — Cybersecurity engineering student. I enjoy understanding how systems work, how they break, and how to defend them. I learn by building labs, investigating attacks and turning what I find into practical tools."></p>

<h2>Selected projects</h2>

<a href="https://github.com/Yasserkdr1/golden-image_factory"><img src="assets/golden.svg" width="100%" alt="Golden Image Factory: DevSecOps Golden Image Factory for automated Ubuntu 24.04 hardening, compliance validation and image builds with Packer, Ansible, Lynis, OpenSCAP, VirtualBox, GCP and GitHub Actions."></a>

<p><a href="https://github.com/Yasserkdr1/golden-image_factory">Explore project ↗</a> &nbsp; · &nbsp; <a href="https://github.com/Yasserkdr1/golden-image_factory/stargazers">☆ Stars</a></p>

<details>
<summary>View architecture — Golden Image Factory</summary>

```mermaid
flowchart TD
    SRC[Source Image] --> PACKER[Packer]
    PACKER --> VM[Temporary VM]
    VM --> ANSIBLE[Ansible]
    ANSIBLE --> HARDEN[Hardening]
    HARDEN --> REBOOT[Reboot]
    REBOOT --> VERIFY[Verification]

    VERIFY --> LYNIS[Lynis]
    VERIFY --> OSCAP[OpenSCAP]

    LYNIS --> GATE{Compliance Gate}
    OSCAP --> GATE

    GATE --> CLEAN[Image Cleanup]
    CLEAN --> IMAGE[(Golden Image)]
```

</details>

<br>

<a href="https://github.com/Yasserkdr1/Automated-soc-investigation-lab"><img src="assets/soc.svg" width="100%" alt="Automated SOC Investigation Lab: Automated SOC lab integrating Wazuh, Shuffle SOAR, VirusTotal, AbuseIPDB, LLM-assisted context analysis, and DFIR-IRIS for detection enrichment, risk scoring, and incident case management."></a>

<p><a href="https://github.com/Yasserkdr1/Automated-soc-investigation-lab">Explore project ↗</a> &nbsp; · &nbsp; <a href="https://github.com/Yasserkdr1/Automated-soc-investigation-lab/stargazers">☆ Stars</a></p>

<details>
<summary>View architecture — Automated SOC Investigation Lab</summary>

<img src="assets/soc-architecture.png" width="100%" alt="Original SOC lab architecture">

</details>

<br>

<table>
<tr>
<td width="50%" valign="top"><a href="https://github.com/Yasserkdr1/Wazuh-Multi-Signal-Web-Shell-Detection"><img src="assets/webshell.svg" width="100%" alt="Web Shell Detection: A comprehensive webshell detection system built with Wazuh SIEM,  leveraging multi-signal analysis to identify and track malicious web shells.  Includes detection rules, evidence collection, and forensic analysis workflows."></a>
<p><a href="https://github.com/Yasserkdr1/Wazuh-Multi-Signal-Web-Shell-Detection">Explore project ↗</a> &nbsp; · &nbsp; <a href="https://github.com/Yasserkdr1/Wazuh-Multi-Signal-Web-Shell-Detection/stargazers">☆ Stars</a></p>
<details><summary>View architecture</summary><p><img src="assets/webshell-architecture.png" width="100%" alt="Project architecture"></p></details>
</td>
<td width="50%" valign="top"><a href="https://github.com/Yasserkdr1/CyberThreat-Analytics-Pipeline"><img src="assets/pipeline.svg" width="100%" alt="CyberThreat Analytics: Real-time cybersecurity threat detection pipeline using Kafka, Spark, Cassandra, HDFS and HBase, with a live SOC monitoring dashboard."></a>
<p><a href="https://github.com/Yasserkdr1/CyberThreat-Analytics-Pipeline">Explore project ↗</a> &nbsp; · &nbsp; <a href="https://github.com/Yasserkdr1/CyberThreat-Analytics-Pipeline/stargazers">☆ Stars</a></p>
<details><summary>View architecture</summary><p><img src="assets/pipeline-architecture.svg" width="100%" alt="Project architecture"></p></details>
</td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://github.com/Yasserkdr1/Soc-Investigation-Writeups"><img src="assets/cases.svg" width="100%" alt="SOC Investigation Write-ups: Hands-on SOC investigation write-ups covering SIEM triage, EDR analysis, incident response, and MITRE ATT&amp;CK"></a>
<p><a href="https://github.com/Yasserkdr1/Soc-Investigation-Writeups">Explore project ↗</a> &nbsp; · &nbsp; <a href="https://github.com/Yasserkdr1/Soc-Investigation-Writeups/stargazers">☆ Stars</a></p>
</td>
<td width="50%" valign="top"><a href="https://github.com/Yasserkdr1/LeanMassCalculator"><img src="assets/android.svg" width="100%" alt="Lean Mass Calculator: Android Kotlin app for Lean Body Mass calculation with Firebase Authentication, Firestore, encrypted local storage, history tracking, user profile and MASVS security improvements."></a>
<p><a href="https://github.com/Yasserkdr1/LeanMassCalculator">Explore project ↗</a> &nbsp; · &nbsp; <a href="https://github.com/Yasserkdr1/LeanMassCalculator/stargazers">☆ Stars</a></p>
</td>
</tr>
</table>
