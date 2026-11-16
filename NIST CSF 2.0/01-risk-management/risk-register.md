# Risk Register

## 1. Project Disclaimer

> \[!IMPORTANT\] **This is a fictional, educational portfolio project.**
> The company, business processes, systems, risks, threat scenarios, and
> proposed mitigations described in this repository are hypothetical and
> were created for learning and demonstration purposes.

## 2. Overview

This risk register documents selected hypothetical risks for a fictional
business operating warehouse and fulfillment services. It organizes each
risk by its related NIST Cybersecurity Framework (CSF) 2.0 Function,
describes a possible threat scenario and business impact, assigns
likelihood and impact scores, and records a proposed mitigation and
accountable risk owner.

### Risk assessment approach

-   **Likelihood:** Rates how probable the risk scenario is.
-   **Impact:** Rates the potential effect on the business if the
    scenario occurs.
-   **Risk Score:** Calculated by multiplying likelihood by impact.

`Risk Score = Likelihood × Impact`

The scores below are reproduced from the accompanying learning workbook.
No risk acceptance decisions, residual risk scores, control-testing
results, or implementation evidence are provided in that source.

## 3. Risk Scoring Method

    Rating Likelihood    Impact
  -------- ------------- --------------
         1 Rare          Minimal
         2 Unlikely      Low
         3 Possible      Moderate
         4 Likely        High
         5 Very likely   Catastrophic

**Scoring scale:** Likelihood and Impact are each rated from 1 to 5. The
Risk Score is the product of the two ratings, with a possible range of 1
to 25.

> \[!NOTE\] The source workbook defines the likelihood and impact scales
> but does not define formal score bands (for example, Low, Medium,
> High, or Critical). This file therefore does not assign severity
> labels that are not present in the register.

## 4. Risk Register

  ------------------------------------------------------------------------------------------------------------------
  Risk ID NIST CSF   Gap /           Threat Scenario    Likelihood    Impact      Risk Proposed        Risk Owner
          Function   Vulnerability   & Potential                                 Score Mitigation      
                                     Impact                                                            
  ------- ---------- --------------- ---------------- ------------ --------- --------- --------------- -------------
  R-01    Govern     Third-Party &   Dual-warehouse              3         5    **15** Enforce vendor  IT Manager /
                     Supply Chain    fulfillment halt                                  risk            Legal
                     Governance      and client data                                   assessments and 
                                     exposure via                                      security SLAs.  
                                     Inventory SaaS                                                    
                                     outage/breach.                                                    

  R-02    Identify   Warehouse       Unpatched                   4         3    **12** Deploy          Warehouse IT
                     Hardware Asset  warehouse                                         automated       Ops
                     Inventory       devices                                           network         
                                     (scanners,                                        discovery and   
                                     printers,                                         centralize      
                                     terminals)                                        asset inventory 
                                     create network                                    across 3 sites. 
                                     entry points.                                                     

  R-03    Protect    Access Control  Unauthorized                4         5    **20** Enforce MFA on  IT Security /
                     & Mandatory MFA account access                                    all logins and  Admin
                                     enabling fraud                                    implement       
                                     and data theft.                                   strict RBAC.    

  R-04    Detect     Web Application Unauthorized                3         5    **15** Deploy a Web    App
                     Monitoring      data extraction                                   Application     Development
                                     via automated                                     Firewall (WAF)  Lead
                                     web portal                                        with active     
                                     attacks.                                          alerting and    
                                                                                       rate-limiting   
                                                                                       on the client   
                                                                                       web portal.     

  R-05    Respond    Incident        Uncoordinated               3         5    **15** Draft a formal  IT Manager /
                     Response Plan   ransomware                                        Incident        Leadership
                     (IRP)           responses                                         Response Plan   
                                     prolong                                           (IRP) with      
                                     warehouse                                         clear roles and 
                                     downtime, delay                                   run annual      
                                     last-mile                                         tabletop        
                                     deliveries, and                                   exercises.      
                                     increase costs.                                                   

  R-06    Recover    Warehouse       Extended                    3         5    **15** Deploy dual-ISP Operations /
                     Business        Wi-Fi/ISP outage                                  cellular        Network
                     Continuity      halts warehouse                                   failover and    
                                     operations                                        offline         
                                     (scanning,                                        dispatch        
                                     printing,                                         procedures at   
                                     dispatching).                                     both            
                                                                                       warehouses.     
  ------------------------------------------------------------------------------------------------------------------

## 5. Risk Register Summary

  Metric                               Result
  ------------------------------- -----------
  Total risks documented                    6
  Highest risk score                20 (R-03)
  Lowest risk score                 12 (R-02)
  Average risk score                    15.33
  Risks with likelihood rated 4             2
  Risks with impact rated 5                 5

### Initial observations

1.  **R-03 --- Access Control & Mandatory MFA** has the highest recorded
    score (20). The proposed treatment is to enforce MFA on all logins
    and implement role-based access control (RBAC).
2.  **R-02 --- Warehouse Hardware Asset Inventory** has the lowest
    recorded score (12). Its proposed treatment focuses on automated
    network discovery and centralized asset inventory.
3.  The remaining four risks have a recorded score of 15.
4.  The register includes risks across all six NIST CSF 2.0 Functions:
    Govern, Identify, Protect, Detect, Respond, and Recover.

These observations are based only on the scores and descriptions in this
fictional register. They are not evidence that any mitigation has been
implemented or that any risk has been reduced.

## 6. How to Use This Register

1.  **Identify the risk:** Describe the gap, vulnerability, or condition
    that could create risk.
2.  **Describe the scenario:** Explain what could happen and the
    possible business impact.
3.  **Select the NIST CSF Function:** Use the Function that best aligns
    with the risk-management activity represented.
4.  **Rate likelihood and impact:** Use the 1--5 scales consistently and
    document the rationale when expanding the assessment.
5.  **Calculate the score:** Multiply likelihood by impact.
6.  **Propose a treatment:** Identify a practical control or action that
    could reduce likelihood, impact, or both.
7.  **Assign an owner:** Identify the role accountable for managing the
    risk.
8.  **Track progress:** Record treatment status, evidence, due dates,
    and residual risk as those details become available.
9.  **Review regularly:** Revisit the risk when systems, suppliers,
    business processes, or threat conditions change.

## 8. Learning Notes

This exercise demonstrates the following introductory GRC activities:

-   Identifying and documenting information-security risks.
-   Connecting risks to NIST CSF 2.0 Functions.
-   Applying a simple likelihood-and-impact scoring method.
-   Prioritizing risks based on calculated scores.
-   Proposing risk treatments.
-   Assigning risk ownership.

**Important distinction:** A risk register is a living management
document. It should be reviewed and updated as the organization's
environment, threats, controls, and business priorities change.

## 9. References

-   [NIST Cybersecurity Framework (CSF)
    2.0](https://www.nist.gov/cyberframework)
-   [NIST CSF 2.0 Resource
    Center](https://www.nist.gov/cyberframework/csf-20)

------------------------------------------------------------------------

*Created as part of a personal GRC learning portfolio. All company
details and risk scenarios in this exercise are fictional.*
