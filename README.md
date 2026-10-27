# Home Assistant Nest Integration

A personal, non-commercial integration that connects authorized Google Nest devices to a self-hosted [Home Assistant](https://www.home-assistant.io/) instance.

## What it does

This setup uses Google's Smart Device Management (SDM) API to make supported Nest devices available in Home Assistant for private household use. Depending on the devices and permissions granted, it can:

- Display supported Nest device status and sensor information.
- Control supported thermostat and other device settings.
- Use supported device events in Home Assistant automations.
- Receive events through Google Cloud Pub/Sub when configured.

## Intended use

This project is for the owner and authorized household members only. It is not a public or commercial application, and it does not offer accounts or services to outside users.

Access to Nest data requires authorization through Google's OAuth consent process. Available features depend on Google's APIs, device compatibility, granted permissions, and Home Assistant configuration.

## Privacy and terms

- [Privacy Policy](PRIVACY.md)
- [Terms of Service](TERMS.md)

The documents describe this personal integration's intended data handling and use.

## Disconnecting

To stop using this integration, remove the Nest integration from Home Assistant and revoke its Google Account authorization. Review Home Assistant's local history and backups separately if you also wish to remove retained data.

## Contact

For questions about this integration or its policies: **Jner93@gmail.com**

---

This is an independent personal setup and is not affiliated with, sponsored by, or endorsed by Google or the Home Assistant project.
