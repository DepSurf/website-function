# Function: <code>iommu_sva_prepare_bind_data</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iommu_sva_prepare_bind_data(void *udata, struct iommu_gpasid_bind_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817b9350)
Location: drivers/iommu/iommu.c:2117
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_uapi_sva_unbind_gpasid
  - drivers/iommu/iommu.c:iommu_uapi_sva_bind_gpasid
```
**Symbols:**

```
ffffffff817b9350-ffffffff817b93fe: iommu_sva_prepare_bind_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iommu_sva_prepare_bind_data(void *udata, struct iommu_gpasid_bind_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179c560)
Location: drivers/iommu/iommu.c:2148
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_uapi_sva_unbind_gpasid
  - drivers/iommu/iommu.c:iommu_uapi_sva_bind_gpasid
```
**Symbols:**

```
ffffffff8179c560-ffffffff8179c60d: iommu_sva_prepare_bind_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iommu_sva_prepare_bind_data(void *udata, struct iommu_gpasid_bind_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81825280)
Location: drivers/iommu/iommu.c:2169
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_uapi_sva_unbind_gpasid
  - drivers/iommu/iommu.c:iommu_uapi_sva_bind_gpasid
```
**Symbols:**

```
ffffffff81825280-ffffffff81825350: iommu_sva_prepare_bind_data (STB_LOCAL)
```
</details>
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
