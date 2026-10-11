# Privacy Policy

**Gelato & Ice Cream Formulator (G-Formulator)**

Last updated: 11/10/2026

- App Store search name: **Gelato & Ice Cream Formulator**
- Home-screen name: **G-Formulator**
- Subtitle: **1-Click Multi-Recipe Engine**

---

## 1. Introduction

This Privacy Policy explains how the Gelato & Ice Cream Formulator application (shown on your device as **G-Formulator**) (the "App"), developed and operated by Nitin Shah ("we," "us," "our"), handles information.

**Summary:**
- We do **not** collect, store, transmit, or sell personal identifying information such as your name, email address, phone number, contacts, or location.
- The App has **no user accounts or logins**. Everything you create — recipes, custom ingredients, operational settings, costing data, and label drafts — remains strictly on your own device.
- To support in-app purchases (such as formulation tokens and lifetime feature unlocks), the App interacts with native application stores (**Apple App Store** and **Google Play**) and uses **RevenueCat, Inc.** for receipt validation and purchase synchronization. Payment card details are handled exclusively by Apple or Google; we never see or store your payment details.

---

## 2. Information We Do Not Collect

We do **not** collect, solicit, or have access to:

- Names, physical postal addresses, telephone numbers, or email addresses;
- Account credentials, passwords, or social logins (the App has no login system);
- Credit card numbers, bank accounts, or financial billing information (all transactions are executed by Apple or Google);
- Precise or coarse GPS location data;
- Device contacts, address books, camera, microphone, photo library, or external calendar data;
- User recipes, custom ingredient formulas, batch calculations, costings, or operational notes;
- Behavioral advertising identifiers (IDFA/GAID), cross-app tracking data, or targeted marketing profiles.

We do not sell, rent, or trade your data, nor do we track your activity across third-party websites or applications.

---

## 3. Information Processed for In-App Purchases and Receipt Validation

When you purchase consumable tokens (e.g., token packs) or non-consumable entitlements (e.g., Lifetime Manual Mode Unlock), the transaction is processed directly through Apple In-App Purchase (iOS/iPadOS) or Google Play Billing (Android).

To ensure that purchases are cryptographically validated, credited to your device, and able to be restored, the App integrates the **RevenueCat SDK** (operated by RevenueCat, Inc.).

### Data processed by RevenueCat and Store Platforms:
- **Anonymous App User ID:** A randomly generated, pseudonymous device-level identifier (UUID) assigned to your installation. This identifier is not linked to your name, email, or real-world identity.
- **Transaction Details:** Store product identifiers (e.g., `com.gformulator.tokens.5`, `com.gformulator.manual.lifetime`), transaction timestamps, purchase tokens, and cryptographic receipt data issued by Apple or Google.
- **Technical & Device Information:** Operating system (iOS, Android), OS version, device model, and general IP address (used by the store platforms solely for localized pricing, currency verification, and regional tax compliance).

### Purpose and Legal Basis:
This information is processed solely for **App Functionality**: to validate that a genuine purchase occurred, credit tokens to your local wallet, unlock purchased features, and restore previous non-consumable purchases when you reinstall or switch devices.

### Third-Party Payment Processors:
All payment card numbers, billing addresses, and payment authentication details are processed directly by **Apple Inc.** or **Google LLC** under their respective privacy policies. Neither Nitin Shah nor RevenueCat ever receives or stores your payment card credentials.

---

## 4. Information Stored Locally on Your Device

All core data created and used by the App is stored **exclusively on your device** in local storage (HTML5 localStorage, IndexedDB, or native secure storage such as iOS Keychain and Android Keystore). This includes:

- **Recipes:** All formulations you create, rescale, auto-generate, or save, including batch and multi-batch configurations;
- **Ingredients:** Built-in ingredient modifications and custom ingredients you add or import from CSV/AFCD files;
- **App Settings:** Machine capacity, overrun %, evaporation %, storage temperature, process type (hot/cold), and serving size;
- **Calculated Results:** Quick Check scores, Sensory & Physical Indices (Brix, RVI, MFI), freezing point curves, and label drafts;
- **Token Wallet & Entitlements:** Your current consumable token balance, cryptographic transaction signature mirrors, and lifetime unlock flags;
- **Preferences:** Selected language (18 supported languages), theme (light/system/dark), and temperature units (°C/°F).

**You control this data.** You can export recipes and ingredient databases at any time (PDF, Excel/CSV, JSON). Clearing the App's storage, deleting browser site data, or uninstalling the App will erase local data.

*Important note on consumable tokens:* Because token balances reside locally on your device, uninstalling the App or clearing storage without an exported Recovery Code will permanently delete unspent tokens.

---

## 5. Network Connections

The App is designed to perform all formulation, recipe balancing, mathematical modeling, and export functions offline without an active internet connection. When an internet connection is present, network activity is strictly limited to:

**a) In-App Purchase Validation (RevenueCat & App Stores):**
When purchasing tokens, unlocking features, or pressing "Restore Purchases", the App connects securely over HTTPS to `api.revenuecat.com` and store endpoints to verify digital receipts.

**b) Optional Online Nutrition Search (USDA FoodData Central):**
If and only when you actively perform an ingredient search in the USDA FoodData Central lookup tool, the App transmits the food query text you typed. The request contains **only your search term** — no personal information or recipe content is ever sent.

**c) Optional FSANZ / AFCD Data:**
Australian Food Composition Database data is processed from local files you choose to import. Files you load remain in device memory and are never uploaded to any remote server.

**d) Content Delivery Networks (CDNs):**
The App may fetch public open-source libraries (e.g., PDF generation and spreadsheet parsing libraries) and standard fonts from public CDNs (e.g., Google Fonts, cdnjs). These requests transmit only standard technical HTTP request headers required to deliver the files.

---

## 6. App Store Privacy Declarations (Data Safety / Nutrition Labels)

In compliance with Apple App Store and Google Play data disclosure requirements:

| Data Type | Collected? | Linked to Identity? | Used for Tracking? | Purpose |
| :--- | :--- | :--- | :--- | :--- |
| **Contact Info** (Name, Email, Phone) | **No** | N/A | No | None |
| **Financial / Payment Info** | **No** (Processed by Store) | N/A | No | Payments handled directly by Apple/Google |
| **Purchase History** | **Yes** (Via RevenueCat) | **No** (Pseudonymous UUID) | **No** | App Functionality (Fulfilling tokens & lifetime unlocks) |
| **Identifiers** (Anonymous User ID) | **Yes** (Via RevenueCat) | **No** | **No** | App Functionality (Receipt validation & restoring purchases) |
| **User Content** (Recipes, Ingredients) | **No** (Stored locally) | N/A | No | Maintained on-device only |
| **Location Data** | **No** | N/A | No | None |
| **Usage Diagnostics** | **No** (No 3rd-party analytics) | N/A | No | Optional native OS crash logs managed by Apple/Google |

---

## 7. Device Permissions

The App requests no intrusive device permissions. It does **not** access your camera, microphone, GPS location, contacts, calendar, or photo library. File access is confined solely to files you manually select via the system file picker when importing ingredient CSVs or saving exported PDFs/spreadsheets.

---

## 8. Children's Privacy

The App is not directed at children under the age of 13, and we do not knowingly collect personal information from children under 13. Since the App collects no personal identifying information from any user, this applies universally. If you believe any personal data has been transmitted to us inadvertently, contact us at G-Formulator@outlook.com and we will promptly delete it.

---

## 9. Data Security and Backups

Because your recipes, database modifications, and token balances are stored locally on your device, data security depends on your device's security settings. We strongly recommend:
- Using a device passcode or biometric lock;
- Regularly backing up your recipes and custom ingredients using the built-in export features (PDF, Excel, JSON);
- Utilizing the **Export Recovery Code** feature within the Token Store modal to retain a portable backup of your token balance.

We cannot recover lost recipes or unspent consumable tokens resulting from device loss, OS resets, or app uninstallation.

---

## 10. Your Rights (GDPR, CCPA/CPRA, DPDP)

International privacy frameworks (including EU/UK GDPR, California CCPA/CPRA, and India's Digital Personal Data Protection Act) grant individuals rights regarding access, rectification, portability, and erasure of personal data.

Because **we hold no personal identifying data about you**, there is no central database for us to query, modify, or delete on your behalf:
- **Access & Portability:** Export your recipes and ingredient database at any time using the App's export tools;
- **Erasure:** Erase your local database and settings by clearing the App's storage in your device settings or uninstalling the App;
- **Opt-Out of Sale / Sharing:** We do not sell, rent, or share personal information with third parties for commercial advertising.

If you contact us via email, we will retain your email address and message contents solely for the duration necessary to assist you with your inquiry.

---

## 11. Changes to This Privacy Policy

We may update this Privacy Policy periodically to reflect enhancements in the App or regulatory updates. Any revisions will be indicated by the "Last updated" date at the top of this document. Continued use of the App following any update constitutes your acknowledgement of the revised policy.

---

## 12. Contact Us

If you have any questions or feedback regarding this Privacy Policy or our privacy practices, please contact:

**Nitin Shah**  
15, Gurukul Society, Nr. Circuit House,  
Shahibaug, Ahmedabad – 380004, Gujarat, India  
Email: **G-Formulator@outlook.com**
