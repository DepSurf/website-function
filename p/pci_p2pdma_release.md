# Function: <code>pci_p2pdma_release</code>

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
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_p2pdma_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/p2pdma.c (ffffffff8191c47c)
Location: drivers/pci/p2pdma.c:209
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
**Symbols:**

```
ffffffff8191b9f0-ffffffff8191ba4e: pci_p2pdma_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_p2pdma_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/p2pdma.c (ffffffff8195fa85)
Location: drivers/pci/p2pdma.c:211
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
**Symbols:**

```
ffffffff8195f000-ffffffff8195f05e: pci_p2pdma_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_p2pdma_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/p2pdma.c (ffffffff819a9110)
Location: drivers/pci/p2pdma.c:211
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
**Symbols:**

```
ffffffff819a8660-ffffffff819a86be: pci_p2pdma_release (STB_LOCAL)
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
