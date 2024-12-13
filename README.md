# Capstone_Project
Fall 2024 Capstone
Introduction 

The 2015 South Carolina floods, caused by days of rainfall leading to dam failures, exposed vulnerabilities in dam infrastructure, emergency preparedness, and the disparities in community recovery. With 19 lives lost and $1.4 billion in damages, the incident highlighted the critical need for effective disaster prevention strategies as extreme weather events become increasingly frequent. This project investigates the relationship between dam safety and socioeconomic factors in South Carolina, to uncover systemic inequities and guide equitable policy interventions.  

Purpose:   

The primary purpose of this study was to analyze the disparities in dam safety conditions across South Carolina, focusing on socioeconomic and racial inequities. By merging dam information with demographic analysis, I sought uncover systemic risks, evaluate emergency preparedness, and provide actionable recommendations for equitable disaster mitigation policies.  

Methodology  

Data Sources:  

The National Inventory of Dams (NID): Provided information on dam hazard levels, inspection frequencies, and structural conditions.  

2020 Census Data: Used Python and Census API to request Demographic details of race at tract and block level.   

Climate and Economic Justice Screening Tool (CEJST): Identified "disadvantaged" census tracts based on environmental and socioeconomic burdens.  

Data Preparation:   

Datasets were combined into a single dataset using excel and python.	  

New data points created were:  

Majority race of tract/blocks 

Percentages of race in tracts/blocks  

Binned Percentages  

Risk levels of Dams (Risk_Ord) - created by combining the hazard and condition variables.  

Analytical Techniques:  

Chi-squared and correlation analyses to explore relationships between dam safety and demographic factors.  

Random Forest and XGBoost Machine learning model to identify predictors of dam risk.  

Analysis 

Key Findings: 

Dam Conditions: Many dams in South Carolina are in substandard states, with numerous structures classified as "Poor" or "Fair." These conditions increase the risk of failure during extreme weather events.  

High Risk Clusters: High hazard dams, which could cause loss of life in the event of failure, are concentrated in metro areas, amplifying the potential impact of emergencies on densely populated regions.  

Emergency Action Plan (EAP) Deficiencies: A significant number of high and significant hazard dams lack the required EAPs, delaying critical community responses in emergencies.  

Socioeconomic Vulnerability: Disadvantaged communities are disproportionately exposed to dam related risks.  

Inspection Frequency: Regular inspections were strongly correlated with improved dam safety, highlighting systemic gaps in oversight and maintenance.  

Race vs. Economic Disparities: While race alone was not a strong predictor of dam risk, socioeconomic disadvantages (which disproportionately impact Black communities in South Carolina) emerged as a significant factor in assessing vulnerability.    

Recommendations  

  

 Increase Inspection Rigor: Implement stricter and more frequent inspections for high risk dams, especially in areas with disadvantaged populations.  

Mandate Comprehensive EAPs: Enforce the development and maintenance of Emergency Action Plans for all high and significant hazard dams.  

Targeted Investments: Allocate funding to improve dam infrastructure in disadvantaged areas, addressing gaps in resource distribution and maintenance.  

Community Outreach: Establish educational programs to increase awareness of dam safety risks and train local communities in disaster preparedness.  

Statewide Policy Reform: Advocate for consistent statewide standards for dam safety and equitable allocation of disaster mitigation resources.  

 Implementation  

Timeline:  

Immediate: Prioritize inspections of high hazard dams and enforce compliance with EAP requirements within 1 year.  

Mid Term: Launch targeted repair initiatives for at risk dams, focusing on areas with the greatest socioeconomic vulnerabilities.  

Long Term: Standardize statewide policies and complete infrastructure upgrades for most dangerous at risk dams. Ensure that conditions and plans are consistently kept up. 

Resources Needed 

Additional funding for inspections and repair grants.  

Expansion of state disaster management teams and training programs.  

Improved data tracking systems for monitoring dam conditions and compliance.  

Stakeholders:   

South Carolina Department of Environmental Services  

Local governments  

Community organizations  

Environmental advocacy groups. 

Risks:   

Inadequate funding to complete goals 

Inequitable resource distribution 

Legal challenges from dam owners  

 Conclusion  

South Carolina’s 2015 floods demonstrated the devastating consequences of neglected infrastructure and inequitable disaster response systems. By addressing the systemic disparities identified in this study, through improved dam safety, enhanced preparedness, and equitable investments, the state can build resilience against future extreme weather disasters. These steps will not only save lives but also create a foundation for long term socioeconomic and environmental stability.  
