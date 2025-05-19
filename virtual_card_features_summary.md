## Research on Existing Virtual Card Systems - Summary of Features

Based on initial research, including analysis of providers like Revolut, Capital One, and Privacy.com, common features of virtual card services include:

*   **Card Generation:** Users can typically generate unique virtual card numbers, complete with their own CVV and expiration dates. This is a core function, allowing for the creation of disposable or purpose-specific card details.
*   **Card Types & Usage:**
    *   **Single-Use Cards:** Designed for one-time transactions, these cards often automatically close after the first purchase, enhancing security for transactions on unfamiliar websites.
    *   **Merchant-Locked Cards:** These cards can be restricted for use only at a specific merchant. This is a significant security feature, as if the card details are compromised from that merchant, they cannot be used elsewhere.
    *   **Multi-Use Cards:** Standard virtual cards that can be used for multiple purchases, often with user-defined spending limits and the ability to be paused or closed manually.
*   **Spending Controls:**
    *   **Spending Limits:** Users can often set maximum spending limits for their virtual cards, either per transaction, on a daily, weekly, or monthly basis. Some services link this to the underlying funding source's limit.
    *   **Card Management:** The ability to instantly pause, resume, or permanently close virtual cards provides users with significant control over their spending and security.
*   **Funding Methods:** Virtual cards are typically linked to a primary funding source. Common methods observed include direct bank account debits (ACH) and linking to existing debit cards. The user's request for PayPal compatibility is a point for further investigation in terms of direct funding, though users could potentially use PayPal to fund a linked bank account first.
*   **Security Features:**
    *   **Masking Real Information:** The primary benefit is that the user's actual bank account or physical card details are not exposed to merchants.
    *   **Tokenization:** Some services may use tokenization to further secure transaction data.
    *   **Two-Factor Authentication (2FA):** Commonly implemented by providers for account access security.
    *   **PCI DSS Compliance:** Reputable virtual card providers adhere to Payment Card Industry Data Security Standard (PCI DSS) to ensure secure handling of cardholder data.
    *   **Fraud Monitoring:** Providers often have systems to detect and alert users to suspicious transactions.
*   **User Experience & Accessibility:**
    *   **Management Platforms:** Services are usually managed through web-based dashboards and dedicated mobile applications (iOS and Android), allowing users to create cards, set limits, and view transaction history on the go.
    *   **Browser Extensions:** Some providers offer browser extensions (e.g., for Chrome, Firefox, Edge, Safari) that facilitate the auto-filling of virtual card details during online checkout, streamlining the purchase process.
    *   **Onboarding:** While aiming for ease, onboarding typically involves Know Your Customer (KYC) procedures to comply with financial regulations.
*   **Global Capabilities:** Some providers, like Revolut, are designed for international use, supporting payments in multiple currencies. This is a key consideration for a global service.
*   **Pricing Models:** These vary widely and can include:
    *   **Free Tiers:** Offering basic functionality with a limited number of cards or features.
    *   **Per-Card Fees:** Charges for creating additional virtual cards beyond a certain allowance.
    *   **Transaction Fees:** A percentage or fixed fee on each transaction made with the virtual card.
    *   **Subscription Plans:** Monthly or annual fees for access to premium features, higher card limits, or more cards (e.g., Privacy.com's Pro and Premium plans).

This summary covers many of the features requested by the user, such as single-use/multi-use cards, user-defined spending limits, and the core security proposition. The desire for PayPal funding and recurring payment capabilities are noted for more specific investigation during the technical infrastructure and business model phases.
