<div align="center">

# Nunya

**A VPN client that is safe, fast, reliable, secure and easy to use,**<br>
**growing into one client for every VPN and proxy protocol.**

</div>

## What we care about

| | |
| --- | --- |
| **Safe** | VPN mode carries the whole device, and the app never claims more than it covers. In proxy mode it says exactly which apps are protected. |
| **Fast** | Every server is tested for latency and for where its traffic really comes out. Quick Connect picks the fastest, the one you use most, or the one you used last. |
| **Reliable** | A server only counts as working if traffic actually comes out of it, and the status shield turns red when a tunnel is up but nothing gets through. |
| **Secure** | No accounts and no telemetry. The engine is a checksum-pinned build, the app and the engine verify each other, and your credentials are stored where only you can read them. |
| **Easy to use** | Paste a link, a subscription or a WireGuard config, or scan a QR code, and connect. |

## Today: the client

- [**nunya**](https://github.com/nunyavpn/nunya): the desktop app, open source under GPL-3.0.
- [**nunya-core**](https://github.com/nunyavpn/nunya-core): the engine it runs, based on sing-box.

What works now:

- **Protocols**: VLESS, VMess, Trojan and WireGuard (Cloudflare WARP included).
- **Transports and security**: TCP, WebSocket, gRPC, HTTP/2, HTTPUpgrade and QUIC, with TLS and Reality.
- **Subscriptions**: share-link lists, or whole Xray, sing-box and Clash configurations.
- **Two modes**: a VPN for the whole device, or a local proxy for machines where a VPN can't run.
- **Per server**: usage history, its real location on a map, and WireGuard sharing that the official WireGuard apps can scan.

## Where it's going

1. **One client for every protocol.** Shadowsocks, Hysteria2, TUIC, SSH, AmneziaWG, OpenVPN and more, across more than one engine. It's planned in the open, in the [client's issues](https://github.com/nunyavpn/nunya/issues).
2. **nunya-server-core**: the server side, as a Docker image anyone can run.
3. **nunya-cluster**: many nodes working as one, scaling up and down on their own.
4. **nunya-server-panel**: configs and users managed from one place.

| Repository | What it is | Status |
| --- | --- | --- |
| [nunya](https://github.com/nunyavpn/nunya) | the desktop client | active |
| [nunya-core](https://github.com/nunyavpn/nunya-core) | the engine | active |
| nunya-server-core | the server, as a Docker image | planned |
| nunya-cluster | multiple nodes, auto-scaling | planned |
| nunya-server-panel | config and user management | planned |

## Taking part

The Nunya client began as a fork of [Throne](https://github.com/throneproj/Throne) and, like it, is
GPL-3.0. Each repository states its own license. Bug reports, ideas and pull requests for the
client are welcome. Start with the [open issues](https://github.com/nunyavpn/nunya/issues).
