# Send a Message Using Go with Maytapi WhatsApp API

This repository demonstrates how to send a WhatsApp message using Go and the Maytapi WhatsApp API. Maytapi provides a powerful and easy-to-use API for integrating WhatsApp messaging into your applications.

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
