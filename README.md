# SMS OTP Server API

This is a backend service that provides endpoints for sending and verifying One-Time Passwords (OTPs) via SMS. The API Contract can be found in the [OpenAPI folder](./openapi).

## Assumptions

- The service is designed to be used by other applications (e.g., web, mobile) to implement SMS-based OTP functionality.
- SMS Delivery is handled by a third-party service (e.g., Twilio, Nexmo).