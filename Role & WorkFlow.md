
# **Overall Business Workflow (Simplified)**

1. User Authentication (SSO)
  - Users log in securely using Single Sign-On.
2. Underwriting Workbench (UW)
  - Underwriters review applications, assess risk, and approve or reject policies.
  - Connects with rating engines for premium calculation.
3. Rating & APIs (TTMN APIs & Coherent APIs)
  - These APIs handle rating calculations and communicate between systems.
  - Coherent APIs specifically manage rating rules and premium calculations.
4. Enterprise Transaction Manager (ETM)
  - Acts as middleware to process transactions and send updates to downstream systems.
5. Policy Administration System (ConceptOne)
  - Core system for managing the policy lifecycle:
    - New Business → Renewal → Endorsement → Cancellation
  - Stores policy details and sends data to Data Lake for analytics.
6. Brokerage Binding Desktop
  - Used for broker interactions and binding coverage.
7. Data Lake (EDW)
  - Stores historical and transactional data for reporting and analytics.

# **Your Role in the Workflow**

Form Testing
Verified that all policy forms (applications, endorsements, renewals) were generated correctly based on state, product, and coverage rules.

Product Testing
Ensured rating, underwriting rules, and policy issuance worked as expected for different insurance products.

Policy Lifecycle Testing
Tested end-to-end flow:
Application Submission → Underwriting Approval → Policy Issuance → Renewal → Endors


# **2-Minute Interview Answer**
In my last project, I worked on the Policy Administration System called ConceptOne, which is part of an end-to-end insurance workflow. 
The overall process starts with user authentication via SSO, then moves to underwriting where risks are assessed and rated using APIs. 
Once approved, the policy details flow into ConceptOne for lifecycle management—covering new business, renewals, endorsements, and cancellations.

### My responsibilities ### included policy lifecycle testing, product testing, and form testing to ensure accurate generation of policy documents. 
I also verified class codes, program and sub-program mappings, tested broker and affiliate mappings, and validated subjectivities and conditions as per 
business rules. Additionally, I performed UI testing for the ConceptOne application and database testing for backend validation to ensure 
data integrity across integrated systems like ETM and Data Lake.


RSUM helps insurance companies by:
Designing and managing specialized insurance programs for industries with unique risks.
Underwriting policies (deciding coverage and pricing) for these niche markets.
Acting as an expert middle layer between insurance carriers and brokers.


How you can say it in an interview:
“RSUM is a specialty underwriting agency. They create and manage insurance programs for niche industries like energy, healthcare, and construction. 
Instead of selling directly, they work as MGUs with authority from carriers to underwrite policies. Their role is to provide expertise in complex risk areas 
and offer tailored insurance solutions.”
