# NGP Automation APIs

To support greater automation and operational efficiency for CPOs and EMPs, the following APIs are being developed and enhanced to streamline how NGP service offers are created, maintained, and consumed within the HBS platform.

These APIs reduce manual workload, minimize input errors, and enable seamless backend integration for pricing, service offers, and subscriptions—benefiting both CPOs and EMPs across the eRoaming ecosystem.

Authentication and authorization is done through a valid contract (SSL certificate) between Hubject and the CPO (or EMP) for the provided service APIs.

## CPO APIs:
1. EVSE Assignment API:
- Assign EVSEs to current EVSE Groups
2. EVSE Network API:
- Creating an EVSE Network with EVSE Groups and EVSEs
3. Upload Terms & Conditions (PDF) API:
- Upload “Terms and Conditions” pdf document for to be created service offer 
4. Create NGP Service Offer API:
- Enables CPOs to programmatically create new NGP service offers including detailed tariff, pricing, and subscription information.
5. Update Pricing for NGP Offers API:
- CPO users can update pricing for NGP Unlimited Offers.
6. Extract Offer & Subscription Details API:
- Lets CPOs retrieve detailed offer and subscriber information for syncing and reporting.


## EMP APIs:
1. Enhanced Contracts API:
- Improves the existing Contract API to allow EMPs to pull pricing and tariff information for all NGP offers they are subscribed to, including data tied to specific EVSE Groups.