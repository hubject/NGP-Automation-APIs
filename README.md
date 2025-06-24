# NGP Automation APIs

To support greater automation and operational efficiency for CPOs and EMPs, a suite of APIs has been developed and released to streamline how Next Generation Pricing (NGP) service offers are created, maintained, and consumed within the Hubject B2B Services (HBS) platform.

These APIs reduce manual workload, minimize input errors, and enable seamless backend integration for pricing logic, service offer lifecycle management, and EMP subscription flows—benefiting both CPOs and EMPs across the eRoaming ecosystem.
By integrating these APIs into their backend systems, market participants can:
- Automate tariff creation and updates,
- Align service offers with internal pricing tools and business contracts,
- Maintain better visibility into offer states and subscription activity,
- Improve time-to-market and accuracy of pricing-related data.

Authentication and authorization for these APIs are handled through secure SSL certificate-based access, established via a valid intercharge contract between Hubject and the respective CPO or EMP.

## CPO APIs:

1. EVSE Assignment API:

- Assign EVSEs to current EVSE Groups

2. EVSE Network API:

- Creating an EVSE Network with EVSE Groups and assign EVSEs to them

3. Upload Terms & Conditions (PDF) API:

- Upload “Terms and Conditions” pdf document for to be created service offer

4. Create NGP Service Offer API:

- Enables CPOs to programmatically create new NGP service offers including detailed tariff, pricing, and subscription information.

5. Update Pricing for NGP Offers API:

- Allows CPOs to update the prices of existing NGP unlimited offers (both Bilateral and Offer-to-All)

6. Extract Offer & Subscription Details API:

- Provides CPOs with a way to retrieve detailed information about active NGP offers and subscriptions, including EMP subscriber data, network and billing
  details.

## EMP APIs:

1. Enhanced Contracts API:

- Improves the existing Contract API to allow EMPs to pull pricing and tariff information for all NGP offers they are subscribed to, including data tied to
  specific EVSE Groups, EVSE Network details and CPO contact data.

2. Contracts EVSEs API:

- Allows EMPs to fetch a paginated list of EVSEs belonging to a particular EVSE Group, within an EVSE Network where the subscribed NGP offer resides.