# Security Risk Assessment

## Description
For this project, I leveraging insights from the completed [Audit Lab](https://github.com/Manny-D/Audit-Lab). I conducted a comprehensive risk assessment to identify vulnerabilities and strengthen an organization's data security posture.


 ### Key Points
 - <b>Risk Mitigation</b>: Develop documented strategies to address risks identified during audits, aligning with NIST SP 800-53 controls MP-1 through MP-8 (Media Protection).
 - <b>Risk Prioritization</b>: Objectively assess and prioritize risks based on a quantifiable framework (e.g., NIST SP 800-30), ensuring clear communication to stakeholders for proactive risk management.
 - <b>Frameworks</b>: Leverage assessment scales from NIST SP 800-30 to establish a quantifiable approach for risk identification and prioritization.


### Objectives
  - <b>Analyze Risks</b>: Integrate threat modeling results with existing Standard Operating Procedures (SOPs) and System Security Plan (SSPs) to comprehensively assess organizational risks.
  - <b>Communicate Risks Effectively</b>: Tailor risk explanations to be understandable by non-technical audiences.
  - <b>Mitigate Risks Proactively</b>: Develop and implement strategies to address identified risks.

<br>


## Step 1: Understanding Control Status  
My review of NIST SP 800-53 identified a missing control: Media Protection Policy and Procedures (MP-1). Interviews with Director of IT, John Connor, a review of SOPs and SSPs, and prior threat modeling all point to unauthorized access as the most significant risk associated with this gap. <br>
<br>
![Image 1](https://github.com/Manny-D/Security-Risk-Assessment/assets/99146530/b219dc18-405b-47d7-b3cc-b3c2cbe5ff2e) <br>

<br>

## Step 2: Identifying Mitigating Factors 
While the lack of a formal Media Protection Policy (MP-1) creates a risk of unauthorized access, evidence from the interview suggests a mitigating factor: employees may share unwritten knowledge (or "tribal knowledge") about media protection practices. However, relying on tribal knowledge can be risky, as it's not documented and can be easily lost with employee turnover. <br>
<br>
![Image 2](https://github.com/Manny-D/Security-Risk-Assessment/assets/99146530/2ba7def6-cc38-4039-9bcc-dae8c5be5650) <br>

<br>

## Step 3: Quantitative Risk Assessment
Using the [NIST SP 800-30](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-30r1.pdf) risk assessment framework scales, quantitative values were assigned for both the impact and likelihood of unauthorized access due to the missing media protection policy. This standardized approach ensures consistent risk evaluation across all controls. <br>
<br>
<img src="https://i.imgur.com/GgFlIRM.png" height="50%" width="50%" /> <br>
<br>
Based on this, the risk of unauthorized access appears relatively low.  I assigned a score of "5" (low) for both the likelihood of occurrence and the potential impact.  This translates to an overall risk score of 25 (low) on a scale of 100. <br>
<br>
![Image 3](https://github.com/Manny-D/Security-Risk-Assessment/assets/99146530/68779ad8-ccf0-44a1-821a-99fffae34cb8)

<br>

## Step 4: Objective Risk Explanation 
The Risk explanation is as follows: "Staff do not know what expectations or standards are and no process around media protection, storage, sanitization is documented so may not be done properly
Without standards and policy no process can be repeated consistently and staff will develop their own individual processes." <br>
<br> 
![Image 4](https://github.com/Manny-D/Security-Risk-Assessment/assets/99146530/8ae12421-0a64-4d32-87b8-06a6a22848b2)


<br>

## Step 5: Rinse and Repeat for the remaining Controls
After completing the risk assessment for Media Access control MP-1, steps 1-4 were repeated for controls MP-2 through MP-8.

<br>

## Step 6: Prioritizing Risks
The spreadsheet was then sorted by overall risk in order to prioritize the controls that have the highest risk. <br>
<br>
By prioritizing and organizing identified risks, an executive report can be writted to effectively communicate vulnerabilities to the organization. <br>
<br>
<img src="https://i.imgur.com/kKK1s9r.png" height="50%" width="50%" /> <br>
<br>

Click <a href="https://docs.google.com/spreadsheets/d/17433iyECdZrIzeGKufFavIlnTmdRoH_V/edit?usp=sharing&ouid=112896329836241270049&rtpof=true&sd=true" target="_blank"> here</a> to view the Risk Assessment Spreadsheet.

<br>

## Optional Step: Mitigation Recommendations 
The risk assessment can be further enhanced by incorporating mitigation strategies for identified risks.  If the organization offers relevant solutions, I can recommend their inclusion, adding practical value to the assessment.
