# SKUNKEI

<p align="center">
  <img src="logos/SKUNKEI.png" alt="SKUNKEI" width="220">
</p>

<p align="center"><strong>Digital services for everyday needs and specialist work.</strong></p>

<p align="center"><a href="https://www.skunkei.com/">Visit skunkei.com</a> · <a href="https://status.skunkei.com/">System Status</a> · <a href="https://help.skunkei.com/">Help Centre</a></p>

SKUNKEI is a collection of digital services operated by Keirran Blackley. The public website is the directory and entry point; each service has its own features and access requirements. A SKUNKEI account does not automatically provide access to every service.

## Services

### [StoreStock](https://storestock.skunkei.com)

Inventory management for ServiceM8 businesses. StoreStock helps track stock across warehouses, vehicles, and other locations, supports manager and staff workflows, and reconciles eligible job-material usage with location stock. See the [ServiceM8 add-on repository](https://github.com/SKUNKEI/storestock-servicem8-addon).

**Getting started:** Follow the [StoreStock setup guide](https://storestock.skunkei.com/guide). A manager connects an authorized ServiceM8 account, reviews the initial warehouse and stock balances, then configures locations and staff access. Review the [StoreStock privacy notice](https://storestock.skunkei.com/privacy) and the permissions shown during ServiceM8 authorization.

### [PassKei](https://pass.skunkei.com)

A hosted password manager for organizing and using saved credentials. Users can search their vault and explicitly reveal, copy, or autofill entries. Vault fields are encrypted at rest by the service. PassKei is not offline, end-to-end encrypted, or zero-knowledge.

Companion add-ons are available for [Chrome](https://github.com/SKUNKEI/passkei-chrome-addon) and [Firefox](https://github.com/SKUNKEI/passkei-mozilla-addon). Browser installations are paired and approved by the user, and support search, copy, and user-directed autofill. The [Android app](https://github.com/SKUNKEI/android-app) supports vault access and Android Autofill.

**Getting started:** Sign in with an eligible SKUNKEI account at [PassKei](https://pass.skunkei.com/). Pair each browser installation from the signed-in account and approve only pairing requests you initiated. Android Autofill requires Android 8.0 or later and must be enabled as the selected autofill provider in Android Settings. See the [PassKei privacy notice](https://pass.skunkei.com/privacy).

### [Storage](https://www.skunkei.com/storage/)

A file workspace for uploading and organizing files with folders; searching and filtering by file category; switching between list and grid views; and previewing, downloading, moving, or deleting files. Access currently requires administrator authorization. Contact [support](mailto:service@skunkei.com) to ask about access, and review the [SKUNKEI Privacy Policy](https://www.skunkei.com/privacy) before uploading sensitive or irreplaceable material.

### [BetKei](https://betkei.skunkei.com/)

Sports statistics, market analysis, and connected Betfair Exchange tools for authorized users. Access and live actions may be restricted. Information and model estimates can be incomplete or wrong; they are not betting or financial advice and do not guarantee outcomes.

**Getting started:** BetKei currently requires an authenticated account with administrative authorization. Betfair account features and live betting actions require additional authorization and may be disabled. Review the [BetKei privacy notice](https://betkei.skunkei.com/privacy) and confirm any order and its status directly with Betfair.

### [MedChart](https://www.skunkei.com/medchart/)

A personal and family health-organization workspace for keeping medication instructions, prescriptions, schedules, and care notes together. Access is through an authenticated workspace; contact [MedChart support](https://medchart.skunkei.com/support) about access. MedChart is an organizational tool, not a medical provider, and does not replace professional medical advice or care. See the [MedChart privacy notice](https://medchart.skunkei.com/privacy) before entering health information.

## Accounts and access

The [account area](https://www.skunkei.com/account/) lets members manage account details and sign-in security. Depending on the feature, authentication uses an email address or username and account password, with verification and recovery flows available for account maintenance.

Signed-in members can:

- Update profile details and choose whether their member profile is visible to other signed-in members.
- Change their email address after confirming the change.
- Change their account password or use the password-reset flow.
- Enable optional email-based multi-factor authentication (MFA).
- Review signed-in sessions and revoke sessions they no longer recognize or use.
- Request account deletion in account settings. Deletion is scheduled with a 30-day reactivation period before permanent removal.

Some services use the shared SKUNKEI account; others add separate authorization, provider connections, or staff permissions. Check each service's access requirements.

## Integrations

Some services connect to external platforms. PassKei browser add-ons request browser permissions for password-field detection and user-requested save or autofill workflows. StoreStock connects to a ServiceM8 account through its authorization flow. BetKei can connect to Betfair for account and exchange features when the user is authorized.

Third-party providers have their own terms, privacy policies, availability, and security practices. Review the permissions requested during connection and revoke provider access when it is no longer needed.

## Responsible security reporting

If you suspect a security vulnerability, report it privately to [service@skunkei.com](mailto:service@skunkei.com) rather than posting exploit details publicly. Include the affected service or component, a concise description, safe reproduction steps, and the potential impact. Do not include passwords, session cookies, API keys, vault contents, medical records, or other personal data. Please do not access, modify, or retain other users' data during testing.

## Security and privacy

SKUNKEI uses account authentication, server-side authorization, request validation, and session controls to protect platform features. Services apply additional controls suited to their data and workflows, such as request-security checks for state-changing browser requests, device approval, encryption, or role controls.

Security properties differ by product. Encryption at rest does not necessarily mean end-to-end encryption, and does not by itself mean the service operator cannot access information. For example, PassKei encrypts vault fields before database storage, but the service controls the encryption keys; it is not a zero-knowledge vault. Review each product's notice before storing sensitive information.

The [Privacy Policy](https://www.skunkei.com/privacy) explains platform-wide information handling, including account and technical data, service content, providers, retention, and privacy requests. The [Terms of Service](https://www.skunkei.com/terms) cover account responsibilities, service limits, and third-party connections.

No online service can guarantee complete security. Protect your account, devices, and connected-provider access. Do not send passwords or verification codes to support.

## Support

- [Visit SKUNKEI](https://www.skunkei.com/) or [Check System Status](https://status.skunkei.com/)
- Read the [Privacy Policy](https://www.skunkei.com/privacy) and [Terms of Service](https://www.skunkei.com/terms)
- Visit the [Help Centre](https://help.skunkei.com/) or [contact support](mailto:service@skunkei.com)
- Report a suspected security issue privately to [service@skunkei.com](mailto:service@skunkei.com)

For privacy or account requests, identify the service involved. Do not include passwords, one-time codes, recovery codes, tokens, or other secrets in your message.