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
![Image 1](https://github.com/Manny-D/Security-Risk-Assessment/assets/99146530/b219dc18-405b-47d7-b3cc-b3c2cbe5ff2e) <br>


## Step 2: Identifying Mitigating Factors 
While the lack of a formal Media Protection Policy (MP-1) creates a risk of unauthorized access, evidence from the interview suggests a mitigating factor: employees may share unwritten knowledge (or "tribal knowledge") about media protection practices. However, relying on tribal knowledge can be risky, as it's not documented and can be easily lost with employee turnover. <br>
![Image 2](https://github.com/Manny-D/Security-Risk-Assessment/assets/99146530/2ba7def6-cc38-4039-9bcc-dae8c5be5650) <br>


## Step 3: Quantitative Risk Assessment
I then used [NIST SP 800-30](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-30r1.pdf) assessment scales for quantitative determination of impact and likelihood of this risk. Understanding these values allows me to consistently determine the risk for each control.  
<img src="https://i.imgur.com/GgFlIRM.png" height="50%" width="50%" /> <br/>
Using these values, I can objectively determine that the likelihood of unauthorized access would be a 5 (low), and the impact if it were to happen would also be a 5 (low); the overall impact for this risk is 25/100 (low).  
<img src="https://i.imgur.com/XTFfHp4.jpg" />

## Step 4: Objective Risk Explanation 
My objective, defensible explanation for this risk: "Staff do not know what expectations or standards are, and no process around media protection, storage, or sanitization is documented, so may not be done properly. Without standards and policy, no process can be repeated consistently, and staff will develop their own individual processes."  
<img src="https://i.imgur.com/i5c0MYk.jpg" />

## Step 5: Repetition for Each Control
After completing the risk assessment for Media Access control MP-1, I repeated steps 1-4 for controls MP-2 through MP-8.  
<img src="https://i.imgur.com/ImcETjV.png" height="50%" width="50%" /> <br/>
(reference image for evidence gathering as seen in [Practical Auditing](https://github.com/michaelmccuin/PracticalAuditing) project)  
<img src="https://i.imgur.com/J5Gd4OG.png" height="50%" width="50%" /> <br/>

## Step 6: Prioritizing Risks
I then sorted the spreadsheet by overall risk to prioritize the controls that have the highest risk.  
<img src="https://i.imgur.com/FzZVLZO.png" height="50%" width="50%" /> <br/>
Now that I had an organized list of the risks, I created an executive report to effectively communicate the risks with the organization.  
<img src="https://i.imgur.com/kKK1s9r.png" height="50%" width="50%" /> <br/>

<br>

<p align="center">
  <span style="font-size: 2em;">Click <a href="https://docs.google.com/spreadsheets/d/17433iyECdZrIzeGKufFavIlnTmdRoH_V/edit?usp=sharing&ouid=112896329836241270049&rtpof=true&sd=true" target="_blank"> here</a> to view the Risk Assessment Spreadsheet.</span>
</p>

<br>

## Optional Step: Mitigation Recommendations 
The risk assessment can be further enhanced by incorporating mitigation strategies for identified risks.  If the organization offers relevant solutions, I can recommend their inclusion, adding practical value to the assessment.
