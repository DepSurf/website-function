# Function: <code>mvebu_mmio_mpp_ctrl_set</code>

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
int mvebu_mmio_mpp_ctrl_set(struct mvebu_mpp_ctrl_data *data, unsigned int pid, long unsigned int config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (ffff8000106aa9d8)
Location: drivers/pinctrl/mvebu/pinctrl-mvebu.c:69
Inline: False
```
**Symbols:**

```
ffff8000106aa9d8-ffff8000106aaa5c: mvebu_mmio_mpp_ctrl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mvebu_mmio_mpp_ctrl_set(struct mvebu_mpp_ctrl_data *data, unsigned int pid, long unsigned int config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (c084a814)
Location: drivers/pinctrl/mvebu/pinctrl-mvebu.c:69
Inline: False
Direct callers:
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pmu_mpp_ctrl_set
```
**Symbols:**

```
c084a814-c084a878: mvebu_mmio_mpp_ctrl_set (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
