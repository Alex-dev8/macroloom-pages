---
title: MacroLoom Privacy Policy
---

# MacroLoom Privacy Policy

**Last updated: 28 August 2026**

This Privacy Policy explains how personal data is handled when you use MacroLoom.

## 1. Who is responsible for your data

MacroLoom is operated by **Salvatore Alexander Cannizzo, trading as MacroLoom**, based in England, United Kingdom.

For privacy questions or requests, contact:

**Email:** [macroloom.support@gmail.com](mailto:macroloom.support@gmail.com)

For the purposes of UK data-protection law, MacroLoom's operator is the data controller for personal data processed through the app.

## 2. Information MacroLoom processes

Depending on the features you use, MacroLoom processes the following information.

### Account information

- The account identifier provided through Sign in with Apple.
- Your name and Apple relay email address, if Apple makes them available.
- Authentication and session information needed to keep you signed in.

MacroLoom does not receive your Apple ID password.

### Profile, health and goal information

- Date of birth.
- Height, current weight and goal weight.
- Sex used for energy calculations.
- Activity level, goal direction and weekly target.
- Calorie and macro targets.
- Unit and photo-retention preferences.
- Body-weight records imported from Apple Health when you request an import and grant access.

Some of this information may constitute special-category health data under UK data-protection law.

### Food, photo and diary information

- Food photographs selected for analysis.
- Meal names, food items, portions and meal times.
- Estimated calories, protein, carbohydrates and fat.
- AI confidence information, clarification prompts and analysis results.
- Your edits and saved diary entries.

### Subscription information

- The subscription product selected.
- Trial, active, grace-period, expired or revoked status.
- Transaction identifiers, purchase and expiry dates, and renewal, refund or revocation information supplied by Apple.

Apple processes payment-card and billing credentials. MacroLoom does not receive your full payment-card details.

### Product analytics

If you enable product analytics, MacroLoom uses PostHog to record information such as:

- Screens and features used.
- Onboarding, paywall and purchase-flow events.
- Meal capture, analysis and save outcomes.
- Broad analysis-duration and confidence categories.
- Diary, goals, progress, export, deletion and Apple Health feature interactions.
- App lifecycle, app version, device and operating-system information made available by the analytics service.

Product analytics is disabled until you opt in and can be disabled in MacroLoom Settings.

MacroLoom's own analytics events are designed not to include food or item names, photographs, calorie or macro values, weight values, body measurements, dates of birth, notes, email addresses, Apple credentials, signed transactions or access tokens. Automatic session replay and automatic screen-content capture are not enabled.

### Diagnostics and security information

MacroLoom uses Sentry and service logs to process information about:

- Crashes, hangs, errors and failed operations.
- Retry outcomes and broad performance measurements.
- App, device and operating-system information.
- A MacroLoom account identifier used to investigate failures affecting a particular account.
- Technical request identifiers and server response status categories.

Sentry is configured without screenshots, view-hierarchy capture, default personal-information collection or automatic network-request capture. Diagnostics operate separately from optional product analytics.

### Support communications

MacroLoom processes information you include when contacting support, together with related correspondence and any information reasonably needed to verify account ownership.

## 3. Where the information comes from

Information is obtained:

- Directly from you when you enter profile, goal, meal or support information.
- From photographs you select.
- From Apple when you use Sign in with Apple or make an App Store purchase.
- From Apple Health when you request a weight import and grant access.
- Automatically from the app and backend when necessary to operate, secure and diagnose the service.

## 4. Why information is used and the lawful bases

MacroLoom processes personal data for the following purposes:

| Purpose | UK GDPR lawful basis |
|---|---|
| Create and maintain your account; calculate goals; maintain your diary; analyse food; synchronise information; provide exports; and delete your account. | Performance of the service contract. Where the information constitutes special-category health data, explicit consent is also required. |
| Verify subscriptions, enforce scan limits, prevent fraud and abuse, and protect accounts and infrastructure. | Performance of the contract and legitimate interests in operating and securing the service. |
| Record optional product analytics through PostHog. | Consent. You can withdraw it in Settings. |
| Diagnose crashes, errors, hangs and performance problems through Sentry and service logs. | Legitimate interests in maintaining a reliable and secure service. |
| Respond to support and data-rights requests. | Performance of the contract, legal obligations and legitimate interests in supporting users and resolving disputes. |
| Meet tax, accounting, consumer-protection, regulatory or legal requirements and establish or defend legal claims. | Legal obligation and legitimate interests. |

Where processing relies on consent, you may withdraw that consent. Withdrawal does not make earlier processing unlawful. If consent is withdrawn for information that is necessary to provide MacroLoom's core nutrition and health-tracking features, those features may no longer be available and account deletion may be required to remove the associated information.

## 5. AI food analysis and photographs

When you request food-photo analysis, the selected image is uploaded to MacroLoom's Supabase backend and sent to OpenAI to produce an editable nutrition estimate. The request may also include the meal category, device locale and a one-way account-derived safety identifier.

MacroLoom sends API requests with `store: false`. OpenAI may still process or temporarily retain API information as described in its applicable service terms, privacy documentation and abuse-monitoring policies.

If meal-photo retention is disabled, MacroLoom removes the photo from its storage after the analysis request and cleanup process complete. If retention is enabled, the photograph is associated with the saved meal and retained with the account until it is removed through supported deletion processes. Interrupted uploads or requests may require additional cleanup time.

AI nutrition results are estimates. A result may be recorded temporarily or with the account to complete the request safely and avoid duplicate processing. It is added to the user's meal diary only after being presented for review and saved by the user.

## 6. Apple Health

MacroLoom requests read-only access to body-weight records. It does not request permission to write information to Apple Health. Health access is requested only when you choose the import feature.

You can revoke MacroLoom's Health access in iOS Settings. Revoking access stops future imports but does not automatically remove weight records already imported into MacroLoom. Those records can be removed by deleting the MacroLoom account.

Apple Health information is not used for advertising, sold to data brokers or included in MacroLoom's product-analytics events.

## 7. Service providers and recipients

MacroLoom uses the following providers:

- **Apple** for authentication, App Store purchases, subscription notifications and Apple Health permissions.
- **Supabase** for authentication, database services, private file storage and server functions.
- **OpenAI** for food-photo analysis.
- **PostHog EU** for optional product analytics.
- **Sentry EU** for crash, error and performance diagnostics.
- **GitHub Pages** to host public legal or support information, if these pages are published there.

These providers process information under their applicable terms and data-processing arrangements. They may use their own subprocessors.

Personal data may be processed outside the United Kingdom. Where UK data-protection law requires a transfer mechanism, MacroLoom relies on an applicable adequacy regulation or contractual safeguards made available by the relevant provider.

MacroLoom may also disclose information when required by law, to protect users or the service, to establish or defend legal claims, or as part of a business transfer subject to appropriate safeguards and notice where required.

MacroLoom does not currently use personal data for third-party advertising or cross-service advertising tracking.

## 8. Retention

MacroLoom uses the following retention criteria:

- Profile, goal, diary, analysis-request and weight information is generally retained while your account exists.
- Photographs not selected for retention are removed after processing and request cleanup.
- Retained meal photographs are generally kept with the associated account data.
- Optional analytics and diagnostic information is retained according to the configured retention periods in PostHog and Sentry and for no longer than reasonably needed for product analysis, reliability and security.
- Subscription, security and fraud-prevention records may be retained for as long as reasonably needed to handle disputes, prevent abuse and meet legal, tax or accounting obligations.
- Support correspondence is retained while needed to answer the request and handle related legal or security matters.
- Deleted information may remain temporarily in restricted backups until those backups are overwritten under the provider's normal backup cycle.

Retention settings and provider configurations should be reviewed when MacroLoom's service plans or processing activities change.

## 9. Your choices and rights

MacroLoom provides controls to:

- Edit diary entries and nutrition goals.
- Disable optional product analytics.
- Disable retention for future meal photographs.
- Revoke Apple Health access through iOS Settings.
- Export your MacroLoom data.
- Delete your MacroLoom account and associated app data.

Depending on the circumstances, UK data-protection law may also give you the right to:

- Request access to your personal data.
- Correct inaccurate or incomplete data.
- Request deletion of data.
- Restrict or object to processing.
- Receive certain data in a portable format.
- Withdraw consent.
- Complain to a supervisory authority.

To exercise a right, email [macroloom.support@gmail.com](mailto:macroloom.support@gmail.com). Reasonable information may be requested to verify your identity and protect the account.

You may complain to the UK Information Commissioner's Office through [ico.org.uk/make-a-complaint](https://ico.org.uk/make-a-complaint/).

## 10. Account deletion and subscriptions

You can delete your account from MacroLoom Settings. Account deletion removes the authentication account, profile, diary, weight history, analysis-request records and stored meal photographs from active MacroLoom systems, subject to limited legal retention and backup periods described above.

Deleting the app or your MacroLoom account does not cancel an App Store subscription. Subscriptions must be managed separately through your Apple account's subscription settings.

## 11. Automated processing

MacroLoom uses automated calculations and AI to suggest calorie and macro estimates and starting goals. Users review the results and can edit saved meal information and targets. MacroLoom does not use solely automated processing to make decisions that produce legal or similarly significant effects about users.

## 12. Children

MacroLoom is intended only for people aged 18 or over and is not directed to children.

## 13. Security

MacroLoom uses measures including authenticated requests, encrypted network connections, private file storage, owner-scoped database access controls, server-side subscription verification, input validation and restricted service credentials.

No internet service can guarantee complete security. If you believe your account or information has been compromised, contact [macroloom.support@gmail.com](mailto:macroloom.support@gmail.com).

## 14. Changes to this policy

This policy may be updated when MacroLoom's features, providers, legal obligations or processing activities change. The date at the top will be updated. Material changes will be communicated in the app or through another appropriate method where required.

## 15. Contact

[macroloom.support@gmail.com](mailto:macroloom.support@gmail.com)
