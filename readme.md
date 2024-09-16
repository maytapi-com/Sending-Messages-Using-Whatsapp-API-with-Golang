# WhatsApp Send Message Using Golang

This repository demonstrates how to send a WhatsApp message using Go and the Maytapi WhatsApp API. Maytapi provides a powerful and easy-to-use API for integrating WhatsApp messaging into your applications.

## Quick Start Guide

Maytapi WhatsApp API offers a powerful and user-friendly solution for integrating WhatsApp communication into your project. To get started, create a free account on Maytapi's website and receive a 3-day trial membership. After linking your WhatsApp account via QR code and obtaining your API credentials, you can begin using the API in your project. We recommend exploring our [Google Sheets](https://console.maytapi.com/integrations/sheets) and [Google Contacts](https://console.maytapi.com/integrations/contacts) integrations, as well as additional tools on our [GitHub page](https://github.com/maytapi-com), to optimize your workflow. This guide outlines the steps to help you maximize the potential of Maytapi WhatsApp API.


1. **Registration**
   - Visit [https://console.maytapi.com/register](https://console.maytapi.com/register) to create your account.
   - No credit card or additional identity verification is required.
   - Upon registration, you'll receive a 3-day trial membership.

2. **Connect Your Device**
   - Navigate to the Dashboard and locate the QR code section.
   - Open WhatsApp on your mobile device.
   - Go to Settings -> Linked Devices -> Link a Device -> Scan QR Code.
   - Scan the QR code displayed on the Maytapi dashboard.

3. **Obtain API Credentials**
   - Visit [https://console.maytapi.com/developers/token](https://console.maytapi.com/developers/token).
   - Retrieve your unique Product ID and API Token.
   - Note the Phone ID associated with your connected device.

4. **Start Using the API**
   - You're now ready to use the Maytapi WhatsApp API.
   - Implement the API in your project using the obtained credentials.

5. **Explore API Capabilities**
   - For a comprehensive overview of API functionalities, visit:
     [https://console.maytapi.com/developers/documentation](https://console.maytapi.com/developers/documentation)
   - This documentation provides detailed information on available endpoints and their usage.



## Features

- Send text messages to WhatsApp numbers
- Easy integration with Maytapi WhatsApp API
- Configurable settings for API credentials

## Requirements

- Go 1.16 or higher
- Maytapi account and API credentials

## Installation

1. Clone this repository:
```bash
https://github.com/maytapi-com/send-a-message-with-golang-using-whatsapp-api.git
cd project-folder
```

2. Configure your Maytapi credentials in `main.go`:
```
productID := "your_product_id"
phoneID := "your_phone_id"
apiKey := "your_api_key"
```
3. Build the project:
```golang
go build
```
## Usage

To send a test message, run the compiled program:
```bash
./maytapi-whatsapp-go
```

To use in your own project:
1. Copy the `main.go` file to your project.
2. Update the Maytapi credentials with your own.
3. Import and use the necessary functions in your code.

> [!NOTE]
> **To perform all these operations correctly, you need to register with maytapi.com, get the credentials, and place them in the config file.**



## Why Maytapi?

[Maytapi](https://maytapi.com) offers a robust WhatsApp API solution with features like:

- Multi-device support
- Affordable pricing
- Easy integration
- Comprehensive documentation

Learn more about Maytapi's [WhatsApp API](https://maytapi.com) and how it can benefit your projects.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Support

For questions about Maytapi's WhatsApp API, visit their [official documentation](https://maytapi.com/whatsapp-api-documentation) or contact their support team.
