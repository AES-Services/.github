# AES Services LLC

## AES Metalhost is coming

AES Services is building Metalhost: a cloud infrastructure platform for builders who need virtual machines, dedicated bare metal, private networking, storage, usage-aware billing, and a clean customer console.

We are moving from GPU leasing into a broader platform: instant VMs for everyday workloads, bare metal for customers who need direct hardware control, and a customer console/API layer that makes the whole stack easier to operate.

### What We Are Building

**Virtual Machines**
- CPU and future GPU-backed instances
- Private networking, public IPv4/IPv6, firewalls, custom images, snapshots, and persistent disks
- Public SDK and CLI for automation-first users

**Bare Metal**
- Dedicated servers for customers who need predictable performance
- GPU nodes, NVMe-heavy machines, and custom hardware profiles
- Rescue, reinstall, and inventory workflows for operator-managed hardware

**Metalhost Console**
- Projects, API keys, instances, disks, file shares, wallets, usage, and audit history
- Clear operations tracking for long-running infrastructure tasks
- Customer-facing workflows backed by the same API used by the CLI

### Current Status

Metalhost is in active buildout. The public SDK and CLI are available, and we have proven the full customer experience end-to-end in a real datacenter: VMs provision in under a minute, customer SSH works over both private and public IPv4, snapshots restore cleanly to new VMs, and NFS file shares are mountable from inside guests. Usage is metered per-second and settled to wallets.

### Public Repositories

- **[metalhost-sdk](https://github.com/AES-Services/metalhost-sdk)** — public Go SDK and API contract snapshots (proto + Connect-Web/Go clients + OpenAPI)
- **[metalhost-cli](https://github.com/AES-Services/metalhost-cli)** — public customer CLI; the `metalhost` binary covers VMs, disks, networking, object storage, wallets, quotas, audit, IAM, and webhooks

More public tooling will be added as the platform matures.

### Get In Touch

- **Website:** [aesservices.net](https://aesservices.net)
- **Contact:** [contact@aesservices.net](mailto:contact@aesservices.net)

---

**AES Services LLC** — building practical cloud infrastructure for VMs, bare metal, and GPU workloads.
