---
layout: default
---
# Knowledge Base

## Hardware Specifications

| **Plan**     | **vCPU** | **Memory** | **SSD** | **Bandwidth** | **PHP Workers** | **Type** |
| Starter      | 1 | 1GB | 20GB | 1TB | 2 | Shared |
| Standard     | 1 | 2GB | 50GB | 2TB | 2 | Shared |
| Deluxe       | 2 | 4GB | 75GB | 4TB | 4 | Shared |
| Professional | 2 | 4GB | 75GB | 4TB | 4 | Dedicated |
| Ultimate     | 4 | 8GB | 150GB | 5TB | 6 | Dedicated |

Each plan is provided with an isolated Virtual Machine running on a high-performance KVM hypervisor with [AMD EYPC](https://www.linode.com/amd/) processors.

**Standard Plans:** AMD EYPC Naples (7001 Series) & AMD EYPC Rome (7002 Series)

**Premium Plans:** AMD EYPC - Milan (7003 Series)

### Software Specifications

| **Package**   | **Version** |
| Kernel        | 6.2.9 |
| Ubuntu Server | 22.04 LTS |
| OpenLiteSpeed | 1.7.17 |
| WordPress     | 6.2 |
| lsPHP         | 8.1 |
| MariaDB       | 10.11 |
| Redis         | 6.0.16 |
| Python        | 3.9 |

**Pre-Installed Plugins:**

- Jetpack Free
- Jetpack Protect Free
- Litespeed Cache
- WPS Hide Login

### Content Delivery Network Specifications

[Friendly Bot Allowlist](https://www.quic.cloud/docs/cdn/friendly-bot-allowlist/)

[CDN Edge Addresses](https://quic.cloud/ips) - Updated daily.

- Native HTTP/3 QUIC Support
- Caches complex dynamic content with private cache and ESI support.
- Supports WooCommerce and bbPress.
- Automatically performs targeted purges based on WordPress events.
- Provides advanced Layer-7 DDoS protection.
- Under abnormally high traffic conditions, CDN-level reCAPTCHA kicks in to challenge non-Trusted visitors.

| **Plan**       | **Bandwidth** | **Service Supports** |
| Standard Plans | 5GB | Best-Effort CDN queue priority |
| Premium Plans  | 1TB | Expedite queue priority |

Standard Plans are eligible for Expedited CDN priority if....

### Object Storage Specifications

Standard Plans are not eligible for Object Storage at this time.

- S3-compatible storage solution
- Stored data is durable and fault-tolerant
- Objects can be accessed through unique URLs
- Unlimited Bandwidth offered.

[s4cmd Tool Guide](https://www.linode.com/docs/products/storage/object-storage/guides/s4cmd/)

**Maximum individual file upload size:** 5GB

**Rate limiting:** 750 requests per second per bucket.

**Restricted file name characters:** ```" ' < > & + =```
