# Sinch (sinch)
Sinch is a cloud communications platform that provides APIs for SMS, voice, video, and messaging across multiple channels. Their developer platform enables businesses to integrate programmable communications into applications, supporting everything from phone number provisioning and verification to omnichannel messaging via WhatsApp, RCS, Facebook Messenger, and more.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - SMS, Voice, Messaging, Verification, Omnichannel, Telephony, Fax, SIP, Phone Numbers

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-03-20

## APIs

### Sinch SMS API
The Sinch SMS API enables developers to send and receive SMS messages globally at scale. It supports batch messaging with scheduled delivery, message templates, delivery reports, and inbound message handling via webhooks. The API provides group management for organizing recipients, automatic message encoding optimization, and supports both transactional and marketing use cases across carriers worldwide.

**Human URL:** [https://developers.sinch.com/docs/sms](https://developers.sinch.com/docs/sms)


#### Tags:

 - SMS, Messaging, Text Messages, Notifications

#### Properties

- [Documentation](https://developers.sinch.com/docs/sms/api-reference)

### Sinch Voice API
The Sinch Voice API is a programmable voice platform that allows developers to make, receive, and manage voice calls over PSTN, SIP, and in-app channels. It supports text-to-speech in over 115 languages, interactive voice response (IVR) menus, call recording, transcription, number masking, and conferencing. The API enables outbound and inbound calling with real-time call control through callbacks and SVAML instructions.

**Human URL:** [https://developers.sinch.com/docs/voice](https://developers.sinch.com/docs/voice)


#### Tags:

 - Voice, Calling, Telephony, Text To Speech, IVR

#### Properties

- [Documentation](https://developers.sinch.com/docs/voice/api-reference/authentication)

### Sinch Verification API
The Sinch Verification API provides phone number verification through multiple methods including SMS, flashcalls, phone calls, and data verification. It enables developers to verify user identity by sending one-time codes or initiating automated verification flows. The API can be consumed directly via REST endpoints or through the Sinch Verification SDKs, and supports configurable verification workflows to optimize cost and conversion rates.

**Human URL:** [https://developers.sinch.com/docs/verification](https://developers.sinch.com/docs/verification)


#### Tags:

 - Verification, Identity, Phone Numbers, Authentication

#### Properties

- [Documentation](https://developers.sinch.com/docs/verification/api-reference/)

### Sinch Conversation API
The Sinch Conversation API is an omnichannel messaging platform that enables developers to send and receive messages across multiple channels including SMS, RCS, WhatsApp, Facebook Messenger, Instagram, Viber, Telegram, KakaoTalk, and LINE through a single unified API. It provides contact management, conversation tracking, message templating, and webhook callbacks for real-time event handling. The API normalizes message formats across channels, allowing developers to build multichannel messaging experiences without channel-specific integrations.

**Human URL:** [https://developers.sinch.com/docs/conversation](https://developers.sinch.com/docs/conversation)


#### Tags:

 - Messaging, Omnichannel, WhatsApp, RCS, Facebook Messenger

#### Properties

- [Documentation](https://developers.sinch.com/docs/conversation/api-reference)

### Sinch Numbers API
The Sinch Numbers API enables developers to programmatically search for, purchase, configure, and manage phone numbers across multiple countries. It supports local, national, mobile, and toll-free number types that can be used with Sinch SMS, Voice, and Conversation APIs. The API provides endpoints for listing available numbers by region and type, activating numbers, updating number configurations, and releasing numbers when they are no longer needed.

**Human URL:** [https://developers.sinch.com/docs/numbers](https://developers.sinch.com/docs/numbers)


#### Tags:

 - Phone Numbers, Provisioning, Telephony

#### Properties

- [Documentation](https://developers.sinch.com/docs/numbers/api-reference/numbers/available-number)

### Sinch Fax API
The Sinch Fax API allows developers to send and receive faxes programmatically at scale. It supports sending faxes to single or multiple recipients, downloading received faxes, and managing fax numbers. The API is HIPAA, SOC 2 Type 1, and GDPR compliant, making it suitable for healthcare and other regulated industries that require secure document transmission. It integrates with the Sinch Numbers API for provisioning fax-capable phone numbers.

**Human URL:** [https://developers.sinch.com/docs/fax](https://developers.sinch.com/docs/fax)


#### Tags:

 - Fax, Documents, Healthcare, HIPAA

#### Properties

- [Documentation](https://developers.sinch.com/docs/fax/api-reference)

### Sinch Elastic SIP Trunking API
The Sinch Elastic SIP Trunking (EST) API enables developers to programmatically create and manage SIP trunks for connecting existing telephony infrastructure to the Sinch network. It provides endpoints for managing SIP endpoints, trunk configurations, and access control lists. The API supports elastic scaling of voice capacity without requiring fixed-capacity commitments, allowing businesses to connect their PBX systems, contact centers, or communication platforms to global PSTN connectivity.

**Human URL:** [https://developers.sinch.com/docs/est](https://developers.sinch.com/docs/est)


#### Tags:

 - SIP, Trunking, Voice, Telephony

#### Properties

- [Documentation](https://developers.sinch.com/docs/est/api-reference/est/sip-endpoints)

### Sinch Provisioning API
The Sinch Provisioning API allows developers to programmatically set up senders, accounts, and templates on the messaging platforms used by the Sinch Conversation API. It provides endpoints for configuring messaging channel integrations, managing sender identities, and setting up message templates for approval. This API streamlines the onboarding process for new messaging channels and automates the configuration that would otherwise require manual setup through dashboards.

**Human URL:** [https://developers.sinch.com/docs/provisioning-api](https://developers.sinch.com/docs/provisioning-api)


#### Tags:

 - Provisioning, Configuration, Messaging

#### Properties

- [Documentation](https://developers.sinch.com/docs/provisioning-api/api-reference)

### Sinch Registration API
The Sinch Registration API provides endpoints for managing sender ID registrations required by various markets and regulatory bodies. It enables developers to retrieve market-specific requirements, create and submit registrations for sender IDs, and track the status of registration applications. This API helps businesses comply with local messaging regulations across different countries where sender registration is mandatory for SMS delivery.

**Human URL:** [https://developers.sinch.com/docs/registration-api](https://developers.sinch.com/docs/registration-api)


#### Tags:

 - Registration, Sender ID, Compliance

#### Properties

- [Documentation](https://developers.sinch.com/docs/registration-api/api-reference)

### Sinch Brands API
The Sinch Brands API allows developers to create, update, and manage customer brand profiles used across Sinch messaging products. Brands represent the business identity associated with messaging campaigns and sender registrations. The API provides endpoints for creating brand records, updating brand details, listing brands, and deleting brands, enabling programmatic management of the brand entities required for compliant business messaging.

**Human URL:** [https://developers.sinch.com/docs/brands](https://developers.sinch.com/docs/brands)


#### Tags:

 - Brands, Identity, Messaging

#### Properties

- [Documentation](https://developers.sinch.com/docs/brands/api-reference/brands/overview)

## Common Properties

- [Portal](https://developers.sinch.com/)
- [Documentation](https://developers.sinch.com/docs)
- [Website](https://www.sinch.com/)
- [PrivacyPolicy](https://www.sinch.com/privacy-notice/)
- [TermsOfService](https://www.sinch.com/terms-of-service/)
- [Support](https://www.sinch.com/contact-us/)
- [Blog](https://www.sinch.com/blog/)
- [Login](https://dashboard.sinch.com/)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
