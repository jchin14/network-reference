# Network Reference

A one-page network reference with two tabs:

- **IP ranges**: private, reserved and commonly-claimed IP ranges (phone hotspots, router defaults, Docker, Kubernetes, VMs, VPNs such as Tailscale, CGNAT, IPv6 ULA and link-local). Use it to pick a subnet that won't collide with something else on your network.
- **Wi-Fi power limits (AU)**: the maximum EIRP allowed in Australia for each 2.4, 5 and 6 GHz band and channel width, with a mW/dBm converter and an EIRP calculator. Data from [Australian 802.11 EIRP Transmit Power Limits v2.0](https://wifiwizardofoz.com/wp-content/uploads/australian_802.11_eirp_transmit_power_limits_v2.0.pdf) by Brett Verney.

It's a static page (`index.html`) with no build step and no dependencies.

## License

[PolyForm Noncommercial 1.0.0](LICENSE). You're free to use, copy, modify and share this for any **noncommercial** purpose.

**Commercial use needs a separate license.** To ask for one, contact [@jchin14](https://github.com/jchin14) (for example, by opening an issue on this repo).
