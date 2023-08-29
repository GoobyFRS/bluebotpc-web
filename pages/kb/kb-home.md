---
layout: default
permalink: pages/kb/
---
# Knowledge Base

## Hardware Specifications

| **Plan**     | **vCPU** | **Memory** | **SSD** | **Bandwidth** | **PHP Workers** | **Type** |
| Starter      | 1 | 1GB | 20GB | 1TB | 2 | Shared |
| Standard     | 1 | 2GB | 50GB | 2TB | 2 | Shared |
| Deluxe       | 2 | 4GB | 75GB | 4TB | 4 | Shared |
| Professional | 2 | 4GB | 75GB | 4TB | 4 | Dedicated |
| Ultimate     | 4 | 8GB | 150GB | 5TB | 6 | Dedicated |

## Network Specifications

| **Plan**     | **Network-Out** | **Network-In** |
| Starter      | 1Gbps | 40Gbps |
| Standard     | 2Gbps | 40Gbps |
| Deluxe       | 4Gbps | 40Gbps |
| Professional | 4Gbps | 40Gbps |
| Ultimate     | 5Gbps | 40Gbps |

Each plan is provided with an isolated Virtual Machine running on a high-performance KVM hypervisor with [AMD EYPC-Milan](https://www.linode.com/amd/) processors.

## Software Specifications

| **Package**   | **Version** |
| Kernel        | 6.2 |
| Ubuntu Server | 22.04 LTS |
| OpenLiteSpeed | 1.7 |
| lsPHP         | 8.1 |
| MariaDB       | 10.11 |
| Redis         | 6.0 |
| WordPress     | 6.2 |
| Python        | 3.9 |

**Pre-Installed Plugins:**

- Jetpack Free
- Jetpack Protect Free
- Litespeed Cache
- WPS Hide Login

### Object Storage Specifications

Standard Plans are not eligible for Object Storage at this time. Ideal for High Quality Content Sharing.

- S3-compatible storage solution
- Stored data is durable and fault-tolerant
- Objects can be accessed through unique URLs
- Unlimited Bandwidth offered.

[s4cmd Tool Guide](https://www.linode.com/docs/products/storage/object-storage/guides/s4cmd/)

**Maximum individual file upload size:** 5GB

**Rate limiting:** 750 requests per second per bucket.

**Restricted file name characters:** ```" ' < > & + =```

### Content Delivery Network Specifications

[Friendly Bot Allowlist](https://www.quic.cloud/docs/cdn/friendly-bot-allowlist/)

[CDN Edge Addresses](https://quic.cloud/ips) - Updated daily.

- Native HTTP/3 QUIC Support
- Caches complex dynamic content with private cache and ESI support.
- Supports WooCommerce and bbPress.
- Automatically performs targeted purges based on WordPress events.
- Provides advanced Layer-7 DDoS protection.
- Under abnormally high traffic conditions, CDN-level reCAPTCHA kicks in to challenge non-Trusted visitors.

Bandwidth Overage Fees do not apply to BlueBotCDN. CDN and Online Services use Vendor Credits. 20 Credits = 1GB Bandwidth.

| **Plan**       | **Bandwidth/Credits** | **Service Supports** |
| Standard Plans | 5GB / 100 Credits    | Best-Effort queue priority |
| Premium Plans  | 1TB / 20,480 Credits | Expedite queue priority while credits last. |

Standard Plans are eligible for Expedited CDN priority if BlueBotCDN-Extra is purchased. If a Premium Plan also purchases BlueBotCDN-Exta, they are allocated an additional 20,480 credits.

### Total Cost of Subscription Evaluation

| **Plan**     | **Monthly** | **Yearly** | **2-Year** | **3-Year** |
| Starter      | $20         | $220       | $440       | $660   |
| Standard     | $40         | $440       | $875       | $1,310 |
| Deluxe       | $85         | $925       | $1,850     | $2,780 |
| Professional | $100        | $1,090     | $2,180     | $3,272 |
| Ultimate     | $250        | $2,730     | $5,450     | $8,182 |

**Monthly** is at the base rate. **Yearly** subscriptions have applicable discounts applied. **2-Year** and **3-Year** assume the Yearly 10% discount.

#### CyberPanel Add-Ons

- WordPress Manager
- Backups V2
- SSLv2
- Root File Manager
- RSPAMD Manager
- Apache as Reverse Proxy
