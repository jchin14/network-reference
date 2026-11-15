# Network Reference

A one-page network reference with three tabs:

- **IP ranges**: private, reserved and commonly-claimed IP ranges (phone hotspots, router defaults, Docker, Kubernetes, VMs, VPNs such as Tailscale, CGNAT, IPv6 ULA and link-local). Use it to pick a subnet that won't collide with something else on your network.
- **IPv6**: common IPv6 prefixes, which ones to use at home, what smart home gear (Matter, Thread) uses, NAT64/NPTv6, multicast and reserved blocks, plus an address checker and ULA generator.
- **Wi-Fi power limits (AU)**: the maximum EIRP allowed in Australia for each 2.4, 5 and 6 GHz band and channel width, with a mW/dBm converter and an EIRP calculator. Data from [Australian 802.11 EIRP Transmit Power Limits v2.0](https://wifiwizardofoz.com/wp-content/uploads/australian_802.11_eirp_transmit_power_limits_v2.0.pdf) by Brett Verney.

It's a static page (`index.html`) with no build step and no dependencies.

## Support

If you find this useful and can afford to, support is appreciated: [buy me a coffee](https://buymeacoffee.com/jchin14). Just getting started, the domain, hosting, Cloudflare Workers and Apple and Google developer accounts add up to a few hundred dollars. Your support helps me keep making tools that are helpful for everyone.

## License

[PolyForm Noncommercial 1.0.0](LICENSE). You're free to use, copy, modify and share this for any **noncommercial** purpose.

**Commercial use needs a separate license.** To ask for one, contact [@jchin14](https://github.com/jchin14) (for example, by opening an issue on this repo).
