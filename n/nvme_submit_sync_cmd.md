# Function: <code>nvme_submit_sync_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int nvme_submit_sync_cmd(struct request_queue *q, struct nvme_command *cmd, void *buffer, unsigned int bufflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff817487f6)
Location: drivers/nvme/host/core.c:853
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_scan_work
  - drivers/nvme/host/core.c:nvme_get_log
  - drivers/nvme/host/core.c:nvme_pr_command
  - drivers/nvme/host/core.c:nvme_report_ns_ids
  - drivers/nvme/host/core.c:nvme_toggle_streams
Direct callers:
  - drivers/nvme/host/lightnvm.c:nvme_nvm_set_bb_tbl
  - drivers/nvme/host/lightnvm.c:nvme_nvm_get_bb_tbl
  - drivers/nvme/host/lightnvm.c:nvme_nvm_identity
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_setup_io_queues
  - drivers/nvme/host/pci.c:nvme_setup_io_queues
  - drivers/nvme/host/pci.c:adapter_delete_queue
```
**Symbols:**

```
ffffffff81743bb0-ffffffff81743bd3: nvme_submit_sync_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int nvme_submit_sync_cmd(struct request_queue *q, struct nvme_command *cmd, void *buffer, unsigned int bufflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff8172a416)
Location: drivers/nvme/host/core.c:853
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_scan_work
  - drivers/nvme/host/core.c:nvme_get_log
  - drivers/nvme/host/core.c:nvme_pr_command
  - drivers/nvme/host/core.c:nvme_report_ns_ids
  - drivers/nvme/host/core.c:nvme_toggle_streams
Direct callers:
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_setup_io_queues
  - drivers/nvme/host/pci.c:nvme_setup_io_queues
  - drivers/nvme/host/pci.c:adapter_delete_queue
```
**Symbols:**

```
ffffffff81725840-ffffffff81725863: nvme_submit_sync_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
</ul>
