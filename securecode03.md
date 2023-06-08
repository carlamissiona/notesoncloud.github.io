## Notes On Secure Coding 


<br><br>


### Security Governance & Policy

**Security Governance - This is administration of an organization's security program**
 
* **Approaches to Security Governance - Top-down & Bottom-up**

* **Top-down**
   * **Upper management makes security policies**
   * **Lower professionals flesh out security policies**
   
   
* **Bottom-up**
* IT staff makes security decisions

**Strategic Plan**

* **Long-term Plan - Lifetime: 5 years**

* **Tactical Plan - Project & hiring plans, budget strategy**

* **Operation Plan- Training plans, Software deployment plans** 


**Change Management**
* **Changes can lead to security issues -So prevent compromise after change**
 
* **Do These Mitigations**
  * Monitor change
  * Test change
  * Allow rollback of change
  * Inform users of change
  * Analyze effects of change
  * Minimize negative impact of change
  * Allow review of change by Change Approval Board (CAB)
 <br>
 
 **Security Policy**

* Requires support of senior management to succeed

* Evidence of due care and due diligence
<br>

 **Confidentiality Requirements**

* Use of password masking and encryption 

* Use of TLS communication this is protection for data in transit

* Logfiles should not include sensitive information

* Do not use FTP use SFTP FTPS


 **Integrity Requirements**

* Code injection is integrity threat - use input validation for mitigation of sql injection 

* Message Digest, Hashing, CRC & checksum


 **Availability Requirements**

* Make highly available infrastructure, graceful-degradation and fail-safe security 


