# LSP <-> Lender protocol specification
APIs for interaction between lender and Loan Service Provider(LSP)

# Overview	

Sourcing, identity verification, underwriting, disbursement, recollections and dispute management are few of the many responsibilities managed by a lender today.  Historically, the best lenders have had to excel at each of these skills in order to maximise their profit pools and serve the larger and larger markets.

LSP is an initiative to unbundle lending and enable the creation of specialized entities, each specialized at one part of the job. Therefore, we envision the future of lending to be a partnership between multiple firms individually focused on sourcing/distribution, identity verification, underwriting, capital arrangement, recollections, etc.

This LSP is being created to showcase the power of the above idea. In its simplest form, it's a loan marketplace that enables SMEs to compare loan offers from multiple lenders and choose the best one. In its more advanced version, This LSP would be akin to a borrower’s financial advisor, looking after their interests, fetching the best offers and advising the customer to make good decisions.

In the longer run, it is envisioned that many more This LSP-like applications (LSPs) will be created. Each of these would focus on distinct borrower pools and build the specialized experiences suited to their customers. This would allow lenders to focus purely on their underwriting and collections logic and cater to diverse collaborations with the LSPs.

# High Level Architecture

![High Level Architecture](/ER-Diagram/HighLevelArchitecture.PNG)

# Sequence Diagram

![Loan Application](/Sequence-Diagram/LoanApplication.PNG)

![Consent API](/Sequence-Diagram/ConsentAPIs.PNG)

![Offer API](/Sequence-Diagram/OfferAPIs.PNG)

![Loan Acceptance API](/Sequence-Diagram/LoanAcceptanceAPIs.PNG)

![Grant Loan API](/Sequence-Diagram/GrantLoan.PNG)

![Consent Monitoring](/Sequence-Diagram/ConsentMonitoring.PNG)

![Repayment API](/Sequence-Diagram/RepaymentAPIs.PNG)

![Confirm Repayment](/Sequence-Diagram/ConfirmRepayment.PNG)

![Disbursement API](/Sequence-Diagram/Disbirsement.PNG)

![Dispute Management](/Sequence-Diagram/DisputeManagement.PNG)

![Trigger Repayment](/Sequence-Diagram/TriggerRepayment.PNG)







