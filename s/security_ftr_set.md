# Function: <code>security_ftr_set</code>

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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/security.c (c00000000003bb54)
Location: arch/powerpc/include/asm/security_features.h:27
Inline: True
Inline callers:
  - arch/powerpc/kernel/security.c:setup_count_cache_flush
```
```
In arch/powerpc/platforms/powernv/setup.c (c00000000135a7c4)
Location: arch/powerpc/include/asm/security_features.h:27
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/setup.c:pnv_setup_arch
  - arch/powerpc/platforms/powernv/setup.c:pnv_setup_arch
  - arch/powerpc/platforms/powernv/setup.c:pnv_setup_arch
  - arch/powerpc/platforms/powernv/setup.c:pnv_setup_arch
  - arch/powerpc/platforms/powernv/setup.c:pnv_setup_arch
  - arch/powerpc/platforms/powernv/setup.c:pnv_setup_arch
  - arch/powerpc/platforms/powernv/setup.c:pnv_setup_arch
  - arch/powerpc/platforms/powernv/setup.c:pnv_setup_arch
```
```
In arch/powerpc/platforms/pseries/setup.c (c0000000000ee2e0)
Location: arch/powerpc/include/asm/security_features.h:27
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/setup.c:pseries_setup_rfi_flush
  - arch/powerpc/platforms/pseries/setup.c:pseries_setup_rfi_flush
  - arch/powerpc/platforms/pseries/setup.c:pseries_setup_rfi_flush
  - arch/powerpc/platforms/pseries/setup.c:pseries_setup_rfi_flush
  - arch/powerpc/platforms/pseries/setup.c:pseries_setup_rfi_flush
  - arch/powerpc/platforms/pseries/setup.c:pseries_setup_rfi_flush
  - arch/powerpc/platforms/pseries/setup.c:pseries_setup_rfi_flush
  - arch/powerpc/platforms/pseries/setup.c:pseries_setup_rfi_flush
```
</details>
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
