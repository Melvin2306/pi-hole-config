# pi-hole-config
Configuration for Pi-hole that can be imported through the Teleporter 

## Setup

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/Melvin2306/pi-hole-config
   ```

2. When opening the Web GUI of Pi-hole, navigate to Settings → Teleporter → Restore → File Input and upload the directory [import_into_teleporter](import_into_teleporter).

## Adlists

The main purpose of this configuration is to have as much security as possible. The configuration consists of several ad and malware lists that block around 〜 11.8 million domains. Please note that the lists are focused on Germany.

## Custom domains

The custom white and blacklists feature certain domains special to certain devices. 
The whitelist adds domains that are being used by Apple's private relay.
The blacklist adds domains from Microsoft and Amazon (Alexa). I highly recommend you to keep them enabled, but in case some devices or services does not work as expected, try deactivating the domains that seem to be the problem.

## Contributing

Contributions to improve the configuration or add new adlists are welcome. Please follow the standard GitHub pull request process to submit your contributions.