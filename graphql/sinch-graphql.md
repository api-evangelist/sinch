# Sinch GraphQL Schema

## Overview

This conceptual GraphQL schema covers the Sinch cloud communications platform, which provides APIs for SMS, voice, video, fax, verification, and omnichannel messaging. The schema unifies Sinch's REST APIs — including the SMS API, Conversation API, Voice API, Verification API, Numbers API, Fax API, Elastic SIP Trunking API, Brands API, Provisioning API, and Registration API — into a single GraphQL surface.

## Source APIs

- SMS API: https://developers.sinch.com/docs/sms
- Conversation API: https://developers.sinch.com/docs/conversation
- Voice API: https://developers.sinch.com/docs/voice
- Verification API: https://developers.sinch.com/docs/verification
- Numbers API: https://developers.sinch.com/docs/numbers
- Fax API: https://developers.sinch.com/docs/fax
- Elastic SIP Trunking API: https://developers.sinch.com/docs/sip-trunking
- Brands API: https://developers.sinch.com/docs/brands
- Provisioning API: https://developers.sinch.com/docs/provisioning
- Registration API: https://developers.sinch.com/docs/registration

## Schema File

See `sinch-schema.graphql` for the full type definitions.

## Type Summary

| Domain | Types |
|---|---|
| Messaging (SMS/MMS) | Message, SMSMessage, MMSMessage, Batch, BatchDelivery, BatchRecipient, DeliveryReport, InboundMessage |
| Omnichannel / Conversation | WhatsAppMessage, RCSMessage, ViberMessage, Messenger, InstagramMessage, CampaignMessage, Conversation, ConversationMessage |
| Campaigns | Campaign, IncomingEvent |
| Voice | Call, CallLeg, Conference, PSTN, SIP, DataCall, Recording, Transcription, CalloutRequest, TextToSpeech, FlashCall |
| Verification | Verification, VerificationRequest, NumberCheck, DataVerification |
| Numbers | PhoneNumber, NumberCapability, DIDOrder |
| Platform / Auth | App, Application, APIKey, Credential, Webhook, WebhookTrigger |
| Contacts | Contact, Group, GroupMember |
| Events | Event, User |

## Usage

This schema is a conceptual representation derived from Sinch's REST API surface. It is intended to assist with API discovery, schema mapping, and tooling integration. Sinch does not currently expose a native public GraphQL endpoint; this schema models what such an endpoint would look like if the REST APIs were unified under GraphQL.

## References

- Developer Portal: https://developers.sinch.com/
- API Reference: https://developers.sinch.com/reference/
- GitHub: https://github.com/sinch
- Status: https://status.sinch.com/
