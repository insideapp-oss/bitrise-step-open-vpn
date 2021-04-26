# Connect to OpenVPN Server step

Establish a VPN connection with the specified OpenVPN server.

This is a fork of the official bitrise step, that uses AES-256-CBC as cipher.

## Usage

In your ``bitrise.yml``, change the default OpenVPN step with:

```
- git::https://github.com/insideapp-oss/bitrise-step-open-vpn@master:
   inputs:
   - port: '443'
   - proto: tcp
   - host: vpn.host.com
```
