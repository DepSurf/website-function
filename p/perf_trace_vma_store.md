# Function: <code>perf_trace_vma_store</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_vma_store(void *__data, struct maple_tree *mt, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813c5aa0)
Location: include/trace/events/mmap.h:71
Inline: False
```
**Symbols:**

```
ffffffff813c5aa0-ffffffff813c5bb1: perf_trace_vma_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_vma_store(void *__data, struct maple_tree *mt, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813f9ef0)
Location: include/trace/events/mmap.h:71
Inline: False
```
**Symbols:**

```
ffffffff813f9ef0-ffffffff813fa001: perf_trace_vma_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_vma_store(void *__data, struct maple_tree *mt, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81425cb0)
Location: include/trace/events/mmap.h:71
Inline: False
```
**Symbols:**

```
ffffffff81425cb0-ffffffff81425dc1: perf_trace_vma_store (STB_LOCAL)
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
