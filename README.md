# Threat Hunting and Analysis of SSH

## Objective

The primary aim of the Threat Hunting and Analysis of SSH project was to scrutinize SSH login activities for abnormal patterns that could indicate security threats. My goal was to enhance my skill set in network security analysis, focusing on the detection and analysis of brute-force login attempts. This project was an exercise in applying theoretical knowledge to a practical scenario, providing me with critical insights into the nature of network-based attacks.

## Skills Learned

- Data Analysis and Pattern Recognition: Improved my ability to analyze large datasets and recognize patterns of malicious activities within network logs.
- Anomaly Detection: Developed a keen eye for spotting anomalies in SSH login attempts, particularly during specific time windows.
- Security Strategy Development: Gained insight into planning and executing effective security strategies based on data analysis findings.
- Incident Analysis: Sharpened my forensic skills by utilizing panda for post-attack analysis to correlate events and dissect the attack process.
- Critical Thinking: Enhanced my critical thinking abilities by correlating events and hypothesizing potential threat actors' intentions and methodologies.
- Incident Response Planning: Strengthened my approach to incident response by simulating real-time reactions to the detected anomalies.

## Tools Used
- Google Colab
- Pandas and Matplotlib: Utilized for data analysis and visualization of the SSH login attempt patterns.
- SSH Log Files: Served as the primary source of data for identifying failed login attempts.


## Steps

- Data Collection: Aggregated SSH log data for analysis.
- Anomaly Identification: Applied analytical techniques to identify IPs with multiple failed login attempts, indicative of potential brute-force attacks.
- Visualization: Created graphs to depict the frequency of failed login attempts, aiding in identifying peak attack times.
- Trend Analysis: Analyzed data for trends that could point to automated attack patterns.
- Security Recommendations: Formulated and proposed security measures based on insights gained from data analysis.

## Visual Representation of the Threat Hunting and Analysis of SSH Workflow

![Panda1](https://github.com/Falola-Uthman/Threat-Hunting-and-Analysis-of-SSH/assets/50869547/1a0bf84a-5fc0-485a-b07a-7267eb25a758)
Ref 1: Detailed analysis of SSH logs, focusing on failed login attempts.

![Panda2](https://github.com/Falola-Uthman/Threat-Hunting-and-Analysis-of-SSH/assets/50869547/32776308-daef-4005-9d11-d2a3598310b3)

Ref 2: Time Analysis Chart - Identifying Peak Times for Failed SSH Login Attempts.

![Panda3 recommendations](https://github.com/Falola-Uthman/Threat-Hunting-and-Analysis-of-SSH/assets/50869547/c4c475c1-5a60-4818-ab44-4bf1bf91ccc6)
Ref 3: Security Recommendations.

Through this project, I not only honed my technical skills but also reinforced the importance of vigilance and proactive threat hunting in maintaining network security. The insights gained from this endeavor are invaluable in my continuous development as a cybersecurity professional.
