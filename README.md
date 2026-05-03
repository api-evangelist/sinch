# Sinch

Sinch is a cloud communications platform providing APIs for SMS, voice, video, fax, verification, and omnichannel messaging. It enables businesses to integrate global communication capabilities into their applications through programmable APIs for sending messages, making calls, verifying phone numbers, and managing sender identities across carrier networks worldwide.

**URL:** [https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Communications
- Messaging
- SMS
- Voice
- Verification
- CPaaS

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-02

## APIs

### Sinch SMS API

The Sinch SMS API enables developers to send and receive SMS messages globally at scale with batch messaging, scheduled delivery, delivery reports, group management, and inbound message handling via webhooks.

**Human URL:** https://developers.sinch.com/docs/sms
**Base URL:** https://us.sms.api.sinch.com

#### Properties

- [Documentation](https://developers.sinch.com/docs/sms)
- [OpenAPI](openapi/sinch-sms-openapi.yml)
- [AsyncAPI](asyncapi/sinch-sms-webhooks-asyncapi.yml)

### Sinch Conversation API

The Sinch Conversation API is an omnichannel messaging platform supporting SMS, RCS, WhatsApp, Facebook Messenger, Instagram, Viber, Telegram, KakaoTalk, and LINE through a single unified API.

**Human URL:** https://developers.sinch.com/docs/conversation

#### Properties

- [Documentation](https://developers.sinch.com/docs/conversation)
- [OpenAPI](openapi/sinch-conversation-openapi.yml)
- [AsyncAPI](asyncapi/sinch-conversation-webhooks-asyncapi.yml)

### Sinch Voice API

The Sinch Voice API is a programmable voice platform for making, receiving, and managing voice calls over PSTN, SIP, and in-app channels with TTS, IVR, recording, transcription, and conferencing.

**Human URL:** https://developers.sinch.com/docs/voice

#### Properties

- [Documentation](https://developers.sinch.com/docs/voice)
- [OpenAPI](openapi/sinch-voice-openapi.yml)
- [AsyncAPI](asyncapi/sinch-voice-callbacks-asyncapi.yml)

### Sinch Verification API

The Sinch Verification API provides phone number verification via SMS OTP, flashcalls, and automated phone calls for user identity verification.

**Human URL:** https://developers.sinch.com/docs/verification

#### Properties

- [Documentation](https://developers.sinch.com/docs/verification)
- [OpenAPI](openapi/sinch-verification-openapi.yml)
- [AsyncAPI](asyncapi/sinch-verification-callbacks-asyncapi.yml)

### Sinch Numbers API

The Sinch Numbers API enables programmatic search, purchase, configuration, and management of phone numbers across multiple countries.

**Human URL:** https://developers.sinch.com/docs/numbers

#### Properties

- [Documentation](https://developers.sinch.com/docs/numbers)
- [OpenAPI](openapi/sinch-numbers-openapi.yml)

### Sinch Fax API

The Sinch Fax API enables programmatic fax sending and receiving with HIPAA, SOC 2 Type 1, and GDPR compliance.

**Human URL:** https://developers.sinch.com/docs/fax

#### Properties

- [Documentation](https://developers.sinch.com/docs/fax)
- [OpenAPI](openapi/sinch-fax-openapi.yml)

### Sinch Elastic SIP Trunking API

The Sinch Elastic SIP Trunking API enables programmatic creation and management of SIP trunks for connecting telephony infrastructure to the Sinch network.

**Human URL:** https://developers.sinch.com/docs/est

#### Properties

- [Documentation](https://developers.sinch.com/docs/est)
- [OpenAPI](openapi/sinch-elastic-sip-trunking-openapi.yml)

### Sinch Brands API

The Sinch Brands API allows creation and management of brand profiles required for compliant A2P business messaging.

**Human URL:** https://developers.sinch.com/docs/brands

#### Properties

- [Documentation](https://developers.sinch.com/docs/brands)
- [OpenAPI](openapi/sinch-brands-openapi.yml)

### Sinch Provisioning API

The Sinch Provisioning API enables programmatic setup of messaging channel senders, accounts, and templates.

**Human URL:** https://developers.sinch.com/docs/provisioning-api

#### Properties

- [Documentation](https://developers.sinch.com/docs/provisioning-api)
- [OpenAPI](openapi/sinch-provisioning-openapi.yml)

### Sinch Registration API

The Sinch Registration API manages sender ID registrations for compliant business messaging in regulated markets.

**Human URL:** https://developers.sinch.com/docs/registration-api

#### Properties

- [Documentation](https://developers.sinch.com/docs/registration-api)
- [OpenAPI](openapi/sinch-registration-openapi.yml)

## OpenAPI Specifications

- [SMS API](openapi/sinch-sms-openapi.yml)
- [Conversation API](openapi/sinch-conversation-openapi.yml)
- [Voice API](openapi/sinch-voice-openapi.yml)
- [Verification API](openapi/sinch-verification-openapi.yml)
- [Numbers API](openapi/sinch-numbers-openapi.yml)
- [Fax API](openapi/sinch-fax-openapi.yml)
- [Elastic SIP Trunking API](openapi/sinch-elastic-sip-trunking-openapi.yml)
- [Brands API](openapi/sinch-brands-openapi.yml)
- [Provisioning API](openapi/sinch-provisioning-openapi.yml)
- [Registration API](openapi/sinch-registration-openapi.yml)

## AsyncAPI Specifications

- [SMS Webhooks](asyncapi/sinch-sms-webhooks-asyncapi.yml)
- [Conversation Webhooks](asyncapi/sinch-conversation-webhooks-asyncapi.yml)
- [Voice Callbacks](asyncapi/sinch-voice-callbacks-asyncapi.yml)
- [Verification Callbacks](asyncapi/sinch-verification-callbacks-asyncapi.yml)

## Capabilities

- [Omnichannel Messaging](capabilities/omnichannel-messaging.yaml) - Unified SMS and Conversation API messaging workflow
- [Voice and Verification](capabilities/voice-and-verification.yaml) - Voice calling and phone number verification workflow
- [Number Management](capabilities/number-management.yaml) - Phone number search, provisioning, and management

### Shared Definitions

- [SMS](capabilities/shared/sms.yaml)
- [Conversation](capabilities/shared/conversation.yaml)
- [Voice](capabilities/shared/voice.yaml)
- [Verification](capabilities/shared/verification.yaml)
- [Numbers](capabilities/shared/numbers.yaml)

## Rules

- [Sinch Rules](rules/sinch-rules.yml)

## JSON Schemas

- [Message Schema](json-schema/sinch-message-schema.json)
- [Contact Schema](json-schema/sinch-contact-schema.json)
- [Verification Schema](json-schema/sinch-verification-schema.json)

## JSON Structures

- [Message Structure](json-structure/sinch-message-structure.json)
- [Contact Structure](json-structure/sinch-contact-structure.json)

## JSON-LD

- [Sinch Context](json-ld/sinch-context.jsonld)

## Examples

- [Send SMS Batch](examples/sinch-send-sms-batch-example.json)
- [Send Conversation Message](examples/sinch-send-conversation-message-example.json)
- [Start Verification](examples/sinch-start-verification-example.json)

## Vocabulary

- [Sinch Vocabulary](vocabulary/sinch-vocabulary.yml)

## Common Links

- **Website:** https://www.sinch.com/
- **Developer Portal:** https://developers.sinch.com/
- **Documentation:** https://developers.sinch.com/docs/
- **Pricing:** https://www.sinch.com/pricing/
- **Blog:** https://www.sinch.com/blog/
- **GitHub:** https://github.com/sinch
- **Sign Up:** https://dashboard.sinch.com/signup
- **Support:** https://www.sinch.com/contact-us/
- **Status:** https://status.sinch.com/
- **Terms of Service:** https://www.sinch.com/terms-of-service/
- **Privacy Policy:** https://www.sinch.com/privacy-policy/

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
