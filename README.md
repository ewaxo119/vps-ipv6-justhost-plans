# VPS IPv6: What You Get, Why IPv6-Only Costs Less, and Which JustHost Plan Fits (Current Price Table)

Buying a VPS with IPv6 comes down to three checks: whether the provider gives you one address or a routed /64, whether IPv6 is configured when the server boots, and whether the data center you choose actually has IPv6. JustHost takes an unusual position on the first two. It sells IPv6-only VPS plans that cost less than its IPv4 plans, and it runs an IPv4-to-IPv6 SSH gateway for people whose own connection is still IPv4-only. If you need a public IPv4 address for visitors, its standard IPv4 plans remain the safer choice.

> **Quick pick:** The IPv6-only Sirius plan is the cheapest IPv6 entry in the current table: 1 core, 1 GB RAM, 20 GB NVMe, 300 Mbps, **$3.61/mo**, or **$2.88/mo** when paid 12 months. It fits a small service, a lab box, or a tunnel endpoint. If IPv4 visitors need to reach the same machine, pick a standard IPv4 plan instead. 👉 [Check the IPv6-only Sirius plan](https://justhost.asia/en/services/vps/tariffs/sirius_ipv6?ref=196392)

## JustHost VPS plans and current prices

The monthly column is the regular rate. The 12-month column is the effective monthly rate when you pay for 12 months, not the total amount. All plans use NVMe storage and fair-share unmetered ports. The table covers the configurations and prices displayed in full on JustHost’s current tariff page; the live page is the authority if the catalogue changes.

| Plan | Configuration | Monthly | 12 months (per month) | Order |
| --- | --- | ---: | ---: | --- |
| VPS Promo | 1 core / 512 MB / 5 GB NVMe / 10 Mbps | $1.99 | — | [ Order](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392) |
| New Star | 1 core / 1 GB / 10 GB NVMe / 100 Mbps | $3.81 | $3.05* | [ Order](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392) |
| Double Star | 2 cores / 2 GB / 20 GB NVMe / 200 Mbps | $7.08 | $5.67* | [ Order](https://justhost.asia/en/services/vps/tariffs/double-star-c2r2048nvme?ref=196392) |
| Bright Star | 4 cores / 4 GB / 30 GB NVMe / 300 Mbps | $9.80 | $7.84* | [ Order](https://justhost.asia/en/services/vps/tariffs/bright-star-c4r4096nvme?ref=196392) |
| Sirius | 1 core / 1 GB / 20 GB NVMe / 300 Mbps | $4.85 | $3.88 | [ Order](https://justhost.asia/en/services/vps/tariffs/sirius?ref=196392) |
| Arcturus | 1 core / 2 GB / 30 GB NVMe / 300 Mbps | $6.92 | $5.53 | [ Order](https://justhost.asia/en/services/vps/tariffs/arcturus?ref=196392) |
| Alpha Centauri | 2 cores / 2 GB / 40 GB NVMe / 400 Mbps | $8.99 | $7.19 | [ Order](https://justhost.asia/en/services/vps/tariffs/alpha_centauri?ref=196392) |
| Vega | 2 cores / 4 GB / 80 GB NVMe / 500 Mbps | $13.44 | $10.75 | [ Order](https://justhost.asia/en/services/vps/tariffs/vega?ref=196392) |
| Capella | 4 cores / 4 GB / 120 GB NVMe / 750 Mbps | $18.30 | $14.64 | [ Order](https://justhost.asia/en/services/vps/tariffs/capella?ref=196392) |
| Rigel | 4 cores / 8 GB / 200 GB NVMe / 750 Mbps | $27.94 | $22.35 | [ Order](https://justhost.asia/en/services/vps/tariffs/rigel?ref=196392) |
| Antares | 5 cores / 8 GB / 300 GB NVMe / 750 Mbps | $33.12 | $26.49 | [ Order](https://justhost.asia/en/services/vps/tariffs/antares?ref=196392) |
| Betelgeuse | 6 cores / 12 GB / 400 GB NVMe / 750 Mbps | $45.54 | $36.43 | [ Order](https://justhost.asia/en/services/vps/tariffs/betelgeuse?ref=196392) |
| Spica | 8 cores / 16 GB / 500 GB NVMe / 750 Mbps | $61.06 | $48.85 | [ Order](https://justhost.asia/en/services/vps/tariffs/spica?ref=196392) |
| Altair | 8 cores / 24 GB / 600 GB NVMe / 750 Mbps | $81.76 | $65.41 | [ Order](https://justhost.asia/en/services/vps/tariffs/altair?ref=196392) |
| Aldebaran | 8 cores / 32 GB / 700 GB NVMe / 750 Mbps | $123.16 | $98.53 | [ Order](https://justhost.asia/en/services/vps/tariffs/aldebaran?ref=196392) |
| Procyon | 12 cores / 32 GB / 1000 GB NVMe / 1000 Mbps | $164.56 | $131.65 | [ Order](https://justhost.asia/en/services/vps/tariffs/procyon?ref=196392) |
| Sirius IPv6 | 1 core / 1 GB / 20 GB NVMe / 300 Mbps | $3.61 | $2.88 | [ Order](https://justhost.asia/en/services/vps/tariffs/sirius_ipv6?ref=196392) |
| Arcturus IPv6 | 1 core / 2 GB / 30 GB NVMe / 300 Mbps | $4.85 | $3.88 | [ Order](https://justhost.asia/en/services/vps/tariffs/arcturus_ipv6?ref=196392) |
| Alpha Centauri IPv6 | 2 cores / 2 GB / 40 GB NVMe / 400 Mbps | $6.92 | $5.53 | [ Order](https://justhost.asia/en/services/vps/tariffs/alpha_centauri_ipv6?ref=196392) |

\*The 12-month rate for New Star, Double Star, and Bright Star requires an order of 3 months or more.

JustHost also lists IPv6 versions of larger configurations on the same tariff page. Those rows were not displayed with full pricing in the source I checked, so they are not in the table above.

## What a “VPS IPv6” plan actually includes

Providers use the same phrase for four different products. The label tells you almost nothing about what happens after the server boots.

| Provider | How IPv6 is delivered | Default state | Allocation and notes |
| --- | --- | --- | --- |
| JustHost | IPv6-only plans, separate from the standard IPv4 line | IPv6 is the only stack on those plans | The published connection example is a single address; an IPv4-to-IPv6 SSH gateway is available for IPv4-only networks |
| ServerPoint | Separate IPv6 interface, `eth2`, alongside public IPv4 and a private VLAN | Disabled by default; enable it in the client portal | One address from a `/64`; `/64` or `/56` on request; PTR, BGP, routed rather than NAT; no extra cost; IPv6 live in 3 of 6 data centers at the time of its announcement |
| OVHcloud | IPv4 and IPv6 delivered on the VPS | Only IPv4 is configured by default; some newer Linux images may preconfigure IPv6 | A single address commonly uses a `/128` prefix, which requires care with the gateway route |
| Liquid Web | IPv6 added when building the server | Select “Add IPv6” at checkout | Free add-on; the page I checked was dated 2025-02-06 and listed a Memory plan at $17/mo and a CPU plan at $22/mo |

ServerPoint’s setup is the clearest example of “supported but switched off.” Every VPS has three interfaces: public IPv4 on `eth0`, a private VLAN on `eth1`, and IPv6 on `eth2`. IPv6 is disabled by default. You enable it in the client portal, and instances created before the feature existed need a reboot so automation can add the interface. That reboot is easy to miss when you are debugging from the operating system.

OVHcloud shows the opposite problem. The VPS is delivered with an IPv4 address and an IPv6 address, but only IPv4 is configured by default. Its documentation also notes that recent Linux images may already have IPv6 configured, so you should check the system’s network files before changing anything. The same provider can produce two different outcomes depending on the image you chose.

## Why JustHost’s IPv6-only line costs less

JustHost’s documentation says an IPv6 VPS costs significantly less than a regular IPv4 server while offering the same functionality. The tariff page shows the gap for matched configurations:

- Sirius: **$4.85/mo** with IPv4, **$3.61/mo** IPv6-only. On 12-month billing, **$3.88** versus **$2.88**.
- Arcturus: **$6.92/mo** with IPv4, **$4.85/mo** IPv6-only. On 12-month billing, **$5.53** versus **$3.88**.
- Alpha Centauri: **$8.99/mo** with IPv4, **$6.92/mo** IPv6-only. On 12-month billing, **$7.19** versus **$5.53**.

That is roughly 23% to 30% less for the same core, RAM, NVMe, and port configuration. The missing piece is the public IPv4 address.

JustHost provides a workaround for management. If your own network cannot reach IPv6, use the 4to6 gateway:

bash
ssh root@4to6.justhost.asia -p <port>


The port number is in the email JustHost sends when the VPS is created. If your network has IPv6, connect directly to the address in the welcome mail, for example `2a00:b700:2::2:131`.

The gateway is documented as an SSH connection method. It is not the same thing as putting a public IPv4 address on the VPS. If IPv4 visitors need to reach a website running on the machine, the standard IPv4 plan is the straightforward choice. 👉 [Compare all current JustHost VPS prices](https://justhost.asia/en/services/vps/tariffs-all?ref=196392)

## The IPv6 setup traps that make a VPS unreachable

### 1. The IPv6 interface may be off

ServerPoint ships IPv6 disabled and expects you to enable it in the portal. OVHcloud ships the address but leaves the configuration to you on many images. If you buy a standard plan from a provider that treats IPv6 as an add-on, check the toggle before you edit `/etc/network/interfaces`. A server with no global IPv6 address will still boot, still accept IPv4 SSH, and still look healthy.

JustHost’s IPv6-only plans remove the fallback. There is no IPv4 stack to hide behind. The practical check is whether your own network can reach IPv6, or whether you need the 4to6 gateway for SSH.

### 2. A `/128` address and the gateway are not in the same subnet

OVHcloud commonly assigns a single IPv6 address with a `/128` prefix. The gateway sits outside that prefix, so a simple default route fails. On Netplan, add a link-scope route to the gateway first, then the default route. Replace the address and gateway with the values from your provider:

yaml
network:
  version: 2
  ethernets:
    eth0:
      addresses:
        - 2001:xxxx:xxxx:xxxx::1/128
      routes:
        - to: fe80::1
          scope: link
        - to: ::/0
          via: fe80::1


Use spaces for indentation, not tabs. Run `sudo netplan try` first so the change rolls back if it cuts off your connection. Windows may warn that the gateway is not on the same subnet when you enter a `/128` address and gateway. OVHcloud’s documentation says that warning can be ignored and the configuration can continue.

### 3. The interface may not be `eth0`

OVHcloud’s VPS LE instances have two interfaces by default. IPv6 may need to be configured on `eth1` rather than `eth0`. Run `ip addr` to see the actual interface names before you copy a configuration file from a guide.

### 4. Cloud-init can overwrite your work

On images with Cloud-init, a reboot can reset network settings. OVHcloud documents a way to disable automatic network management by creating `/etc/cloud/cloud.cfg.d/98-disable-network-config.cfg` with this line:

yaml
network: {config: disabled}


A reboot may be needed. Removing the file restores automatic management. If your IPv6 configuration works until the next restart and then disappears, this is one of the first things to check.

### 5. The address may be present but not global

Run:

bash
ip -6 addr show eth0


A configured address appears with `scope global`, alongside a `fe80::...` link-local address. If you only see the link-local address, the global address is missing, the interface is down, or the configuration did not apply.

## How much IPv6 do you need: one address, a `/64`, or a `/56`?

A single IPv6 address is enough for one server running services on different ports. It is not enough to give every container or virtual machine its own globally routable address.

A `/64` is the standard subnet size for one network segment. It contains 18,446,744,073,709,551,616 addresses. A `/56` contains 256 `/64` subnets, which is what you want when you need to split addresses across multiple virtual networks or delegate prefixes to other systems.

ServerPoint includes one address from a `/64` with every VPS and lets customers request a `/64` or `/56`. Both are routed directly to the VPS’s IPv6 interface, with PTR and BGP support and no extra charge. That is a useful benchmark for what a mature IPv6 setup looks like.

JustHost’s published example is a single address, and its tariff page does not advertise a routed `/64`. If you need a prefix for containers, nested virtualization, or multiple public services, ask before ordering. A cheap IPv6-only plan is still a good fit for a single host. It is a poor fit for a lab that needs dozens of routable addresses. 👉 [Check the JustHost IPv6-only Arcturus plan](https://justhost.asia/en/services/vps/tariffs/arcturus_ipv6?ref=196392)

## Data center availability is a separate question

“IPv6 supported” does not always mean “IPv6 live in every location.” ServerPoint’s announcement is a clear example: Silicon Valley, Amsterdam, and Singapore were live, while Las Vegas, Dallas, and Ashburn were still in rollout. The status was accurate at the time of the announcement and may have changed since.

JustHost says all of its data centers support IPv6. Confirm the exact location at checkout if you are buying for latency, data residency, or a specific network path. A provider can have IPv6 in one region and a different setup in another.

## Which JustHost plan fits your use case

**You need the cheapest IPv6-only box for a small service or lab:** Sirius IPv6 at **$3.61/mo**, or **$2.88/mo** on 12-month billing. One core, 1 GB RAM, 20 GB NVMe, 300 Mbps.

**You need more RAM for a database or a few containers:** Arcturus IPv6 at **$4.85/mo**, or **$3.88/mo** on 12-month billing. It doubles the RAM to 2 GB and the disk to 30 GB for $1.24/mo more than Sirius IPv6.

**You need more CPU and disk:** Alpha Centauri IPv6 at **$6.92/mo**, or **$5.53/mo** on 12-month billing. Two cores, 2 GB RAM, 40 GB NVMe, 400 Mbps.

**You need IPv4 visitors to reach the server:** standard Sirius at **$4.85/mo**, Arcturus at **$6.92/mo**, or Alpha Centauri at **$8.99/mo**. These avoid the gateway question for inbound IPv4 traffic. If you need both IPv4 and IPv6 on the same instance, ask JustHost whether the standard plan includes IPv6 before you order. The cheap IPv6-only line is not a dual-stack product.

**You need a routed `/64` or `/56`:** ask first. The published JustHost example is a single address, and the tariff page does not list a prefix size. Do not assume a `/64` comes with the IPv6-only plans.

## FAQ

**Is one IPv6 address enough for a VPS?**
For one host running services on different ports, yes. For per-container public addresses, multiple virtual machines, or prefix delegation, no. Ask for a `/64` or `/56`.

**Why does `ip -6 addr` show only a `fe80::` address?**
That is the link-local address. The global address is missing or the interface is down. Check `ip -6 addr show eth0` for a `scope global` line. On OVHcloud, a `/128` address also needs a correct gateway route.

**My IPv6 configuration disappears after a reboot. What should I check?**
Cloud-init may be resetting the network configuration. Disable automatic network management with the `98-disable-network-config.cfg` file described above. Also confirm you edited a persistent configuration file rather than using a temporary `ip addr add` command.

**Should I use a `/128` or a `/64`?**
Use the prefix your provider assigns. A single VPS address often comes as `/128`. A routed subnet comes as `/64`. If the gateway is outside the prefix, add a link-scope route before the default route.

**Can I manage a JustHost IPv6-only VPS from an IPv4-only network?**
Yes, for SSH. Use `4to6.justhost.asia` and the port from the welcome email. If you need IPv4 visitors to reach a website on the VPS, choose a standard IPv4 plan instead.

Pick by the address you need, not by the “IPv6 supported” badge. For a cheap IPv6-only box, JustHost’s Sirius IPv6 at **$3.61/mo** is the lowest entry in the current table, and Arcturus IPv6 at **$4.85/mo** doubles the RAM for $1.24 more. If IPv4 visitors are part of the job, standard Sirius at **$4.85/mo** or Arcturus at **$6.92/mo** avoids the gateway question. Before ordering, ask two things: whether the specific data center has IPv6 live, and whether the plan includes a single address or a routed `/64`. 👉 [Start with the JustHost IPv6-only Sirius plan](https://justhost.asia/en/services/vps/tariffs/sirius_ipv6?ref=196392)
