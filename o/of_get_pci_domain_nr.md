# Function: <code>of_get_pci_domain_nr</code>

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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int of_get_pci_domain_nr(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (ffff8000106f9578)
Location: drivers/pci/of.c:201
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_find_domain_nr
```
**Symbols:**

```
ffff8000106f9578-ffff8000106f95e8: of_get_pci_domain_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_get_pci_domain_nr(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (c0891b54)
Location: drivers/pci/of.c:201
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_find_domain_nr
```
**Symbols:**

```
c0891b54-c0891bc8: of_get_pci_domain_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_get_pci_domain_nr(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (c000000000876cb0)
Location: drivers/pci/of.c:201
Inline: False
```
**Symbols:**

```
c000000000876cb0-c000000000876d2c: of_get_pci_domain_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_get_pci_domain_nr(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (ffffffe0004c997c)
Location: drivers/pci/of.c:201
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_find_domain_nr
```
**Symbols:**

```
ffffffe0004c997c-ffffffe0004c99be: of_get_pci_domain_nr (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
