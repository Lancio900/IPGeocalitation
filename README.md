# IP Geolocation Tool (v0.1)

## Description
This Python tool retrieves geolocation information for any given IP address. Using the `IPWhois` library, it fetches detailed data such as:

- ASN (Autonomous System Number) information
- Network details (CIDR, IP range, etc.)
- Entities associated with the IP
- Links for further information

The output is formatted to be easy to read and understand, even for users with limited technical knowledge.

## Features
- **ASN Information**: Displays ASN registry, ASN number, description, country code, and more.
- **Network Details**: Provides information about the network such as IP range, CIDR, and network type.
- **Entities**: Lists associated entities like organizations or ISPs related to the IP address.
- **Links**: Provides useful links for more details about the IP or network.

## Requirements
Before running the script, ensure you have Python 3.x installed along with the following libraries:

- `ipwhois`

You can install the required library using pip:

```bash
pip install ipwhois
