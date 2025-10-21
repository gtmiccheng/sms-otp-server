# SMS OTP Server API

This is a backend service that provides endpoints for sending and verifying One-Time Passwords (OTPs) via SMS. The API Contract can be found in the [OpenAPI folder](./openapi).

## Assumptions

- The service is designed to be used by other applications (e.g., web, mobile) to implement SMS-based OTP functionality.
- SMS Delivery is handled by a third-party service (e.g., Twilio, Nexmo). No need to implement in code.

## To view the OpenAPI Docs

### Use Swagger UI

1. Visit [Swagger Editor](https://editor.swagger.io/).
2. Import this URL: `https://raw.githubusercontent.com/gtmiccheng/sms-otp-server/refs/heads/main/openapi/openapi-v1.yaml`
3. You can now view and interact with the API documentation.

### Use a OpenAPI Extension in VSCode

Install the [42Crunch OpenAPI Extension](https://marketplace.visualstudio.com/items?itemName=42Crunch.vscode-openapi) and preview the `openapi-v1.yaml` file located in the `openapi` folder.