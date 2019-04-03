# Dropbox Supplier Security Requirements

These Supplier Security Requirements apply to Supplier when it provides services to Dropbox. Terms used here but not
defined here are defined in the Agreement.

## 1. Third Party Testing and Validation.

### 1.1. General Testing.

**a. Periodic Tests.** Supplier shall allow Dropbox, or Dropbox’s delegate, to periodically test the security of the
Services. When testing Dropbox or its Delegate shall: (i) carefully conduct tests that are reasonably designed
to safely uncover possible vulnerabilities without undue risk; and (ii) make commercially reasonable efforts to
tailor the tests as needed to specifically achieve the purpose of the test.

**b. Timing.** Dropbox or its delegate may conduct the security tests in Section 1.1 at any time during the term of
the Agreement. Dropbox will: (i) provide Supplier with reasonable notice prior to conducting the tests, (ii)
promptly inform Supplier of any findings; and (iii) delay further disclosure until Supplier has had reasonable time
to resolve issues identified in the findings.

### 1.2. Vulnerability Disclosure Policy.

**a. Generally.** Supplier shall publish a Vulnerability Disclosure Policy (“VDP”) on its public website. This VDP
shall: (i) welcome arbitrary security research; (ii) include all internet facing assets in scope; (iii) provide safe
harbor from CFAA and DMCA actions for all good faith research; and (iv) not place restrictions on disclosure.

**b. Contact and Service Level Agreement.** Supplier shall: (i) post a method by which the public can contact
Supplier to report security vulnerabilities; and (ii) use best efforts to respond to these reported security
vulnerabilities within a commercially reasonable period of time based on the severity and impact of the
vulnerability.

**c. Bug Bounty Program.** Supplier agrees that Dropbox may make deliverables or results of the Services subject
to Dropbox’s Bug Bounty Program. Dropbox will notify Supplier of any material security-related vulnerabilities
in the Services or deliverables identified through its Bug Bounty Program. Supplier understands that research
and disclosures are governed by Dropbox's VDP, which requires good faith and responsible behavior by
participants.

### 1.3. Application and Network Penetration Testing.

**a. Annual Testing.** Supplier shall, at least once per year, perform a suite of independent third-party tests. These
tests will be performed upon: (i) the Services; (ii) all aspects of Supplier’s internet-facing perimeter; and (iii)
Supplier’s internal corporate network and internal systems. Supplier will supply Dropbox with details of all
third-party tests from the previous year, including names of third-party testers and number of person hours
used.

**b. Sharing Results.** Supplier shall, upon Dropbox’s request and under suitable non-disclosure obligations, share
with Dropbox: (i) confirmation that the tests required by this Section 1.3 were performed; and (ii) the third
party tests results from Sections 1.3(a)(i) and (ii) above.

### 1.4. Fixing Issues. 
Supplier will fix all critical and high severity vulnerabilities that could affect the security of Dropbox
Data, of which Supplier becomes aware, within sixty days of becoming aware of the vulnerability. If Supplier
cannot fix the vulnerability within sixty days, Supplier will promptly inform Dropbox, including all details of the risk
to Dropbox arising from Supplier’s inability to fix the vulnerability.

## 2. Technical Security Measures.

### 2.1. Transport Encryption. 
Supplier will maintain an SSL Labs rating (please see https://www.ssllabs.com) of at least
“A” for any external website used to store or access Dropbox data. If Supplier’s rating falls below “A,”
Supplier will: (a) notify Dropbox if this rating is below “A” for three months; and (b) have three months from the
date it notifies Dropbox within which to increase its rating back to an “A.”

### 2.2. Google G Suite Authentication Integration. 
If the Services include a SaaS service, Supplier will integrate the
Services with Google G Suite authentication for Dropbox’s login needs. This Google G Suite authentication
integration will be the only method by which Dropbox users log in to the Service.

### 2.3. Multifactor Authentication. 
Supplier will use a multifactor authentication (“MFA”) login solution for the Services,
provided that text or phone call are not acceptable factors. MFA must be used for: (a) any VPN connections into
the Supplier’s internal networks; (b) any connections into Supplier’s production environment; (c) Supplier’s e-mail,
if it can be accessed from the internet; and (d) any services Supplier uses that contain Dropbox Data.

### 2.4. Patching. 
Supplier will promptly apply any high or critical severity security patches to their production servers,
endpoints, and endpoint management systems.

### 2.5. Detection and Alerting. 
Supplier will proactively monitor, detect, and alert its internal security team regarding
suspicious or malicious activity within Supplier’s production and corporate environments.

### 2.6. Scanning. 
Supplier will run regular automated scans against their internet facing perimeter, production perimeter,
and internal network. Supplier will promptly fix high and critical severity findings.

### 2.7. Environment Separation and Access. 
Supplier will maintain a boundary between its corporate and production
environments. Supplier will maintain controls gating access into the production boundary, and Supplier will only
provide production environment access to employees or contractors who must maintain the production
environment.

## 3. Policy and Compliance.

### 3.1. Security Incidents.

**a. Notification and Timing.** Supplier will notify Dropbox in writing of any Security Incident within seventy-two
hours of Supplier becoming aware of the Security Incident. This notification is required even if Supplier has
not conclusively established the nature or extent of the Security Incident. Supplier will not communicate with
any third party regarding a Security Incident except as specified by Dropbox, or as required by law.

**b. Required Information.** Supplier’s Security Incident notification will describe the known details of the incident,
the status of Supplier’s investigation, and, if applicable, the potential number of persons affected. Supplier will
be solely responsible for all costs associated with any security breach; which includes, if applicable, for
notices to and credit monitoring for affected individuals.

### 3.2. Compliance Certification. 
Supplier shall: (a) maintain compliance with at least one of the following: (i) SSAE
16/SOC 1; (ii) SOC 2; or (iii) ISO 27001; (b) provide audit reports or evidence of these certifications to Dropbox
upon request; and (c) ensure that all Supplier subcontractors or third party delegates adhere to the same
standards.

### 3.3. Secure Development Lifecycle. 
Supplier shall maintain and follow a Secure Development Lifecycle (“SDL”) for
the development of its products and services. Supplier’s SDL will be supported by at least one full time security
engineer. Supplier will provide Dropbox a copy of its SDL policy and process documents upon request.

### 3.4. Supporting Information. 
Upon Dropbox’s request, Supplier will provide its policy and process documents relating
to any of the security controls referenced in these Security Requirements to Dropbox.

### 3.5. Handling of Dropbox Data. 
Supplier will not move Dropbox Data from Supplier’s production environment unless
specifically asked to do so by Dropbox. Specifically, Dropbox Data must not be downloaded to phones or laptops,
and must not be shared with third parties. Supplier will delete Dropbox Data permanently upon Dropbox’s request.

## 4. Modifications. 
Dropbox may periodically update these Security Requirements by posting a new version. If Dropbox
changes these Security Requirements in a manner that materially increases Supplier’s obligations, Dropbox will notify
Supplier, and Supplier will have ninety days within which to object to the changes. If Supplier does not object within
this timeframe, Supplier agrees to comply with the modified Security Requirements. If Supplier objects within this time
frame, and Supplier and Dropbox cannot resolve the objection within thirty days, then Dropbox may terminate the
Agreement immediately upon written notice to Supplier.

## 5. Definitions.

“Agreement” means the executed Agreement between Supplier and Dropbox.

“Dropbox Data” means any data that is provided to Supplier by Dropbox or on behalf of Dropbox.

“Security Incident” means any: (i) breach or suspected breach of the security of the Services or the systems used to
provide the Services that may have resulted in the compromise of Dropbox Data; or (ii) other unauthorized access to
or use of Dropbox Data, or Supplier&#39;s reasonable belief that access or use may have occurred.

“Services” means the products or services provided by Supplier to Dropbox.

“Suppliers” means those vendors who provide services to Dropbox.
