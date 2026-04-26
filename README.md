# AES Services LLC

## AES Foundry is coming

AES Services is building Foundry: a cloud infrastructure platform for builders who need virtual machines, dedicated bare metal, private networking, storage, usage-aware billing, and a clean customer console.

We are moving from GPU leasing into a broader platform: instant VMs for everyday workloads, bare metal for customers who need direct hardware control, and a future console/API layer that makes the whole stack easier to operate.

### What We Are Building

**Virtual Machines**
- CPU and future GPU-backed instances
- Private networking, firewalls, images, snapshots, and persistent disks
- Public SDK and CLI for automation-first users

**Bare Metal**
- Dedicated servers for customers who need predictable performance
- GPU nodes, NVMe-heavy machines, and custom hardware profiles
- Rescue, reinstall, and inventory workflows for operator-managed hardware

**Foundry Console**
- Projects, API keys, instances, disks, wallets, usage, and audit history
- Clear operations tracking for long-running infrastructure tasks
- Customer-facing workflows backed by the same API used by the CLI

### Current Status

Foundry is in active buildout. The public SDK and CLI are available, and the control plane has proven the VM lifecycle in the lab: create/delete flows reach Kubernetes/KubeVirt, usage is metered, and the next infrastructure milestone is a customer-like cluster with HA control-plane nodes, KubeVirt workers, and Rook/Ceph storage.

### Public Repositories

- **[foundry-sdk](https://github.com/AES-Services/foundry-sdk)** - public Go SDK and API contract snapshots
- **[foundry-cli](https://github.com/AES-Services/foundry-cli)** - public customer CLI for Foundry APIs

More public tooling will be added as the platform matures.

### Get In Touch

- **Website:** [aesservices.net](https://aesservices.net)
- **Contact:** [contact@aesservices.net](mailto:contact@aesservices.net)

---

**AES Services LLC** - building practical cloud infrastructure for VMs, bare metal, and GPU workloads.
