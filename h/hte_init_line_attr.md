# Function: <code>hte_init_line_attr</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hte_init_line_attr(struct hte_ts_desc *desc, u32 line_id, long unsigned int edge_flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hte/hte.c (ffffffff81be4800)
Location: drivers/hte/hte.c:735
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:hte_edge_setup
```
**Symbols:**

```
ffffffff81be4800-ffffffff81be4884: hte_init_line_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hte_init_line_attr(struct hte_ts_desc *desc, u32 line_id, long unsigned int edge_flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hte/hte.c (ffffffff81d90890)
Location: drivers/hte/hte.c:735
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:hte_edge_setup
```
**Symbols:**

```
ffffffff81d90890-ffffffff81d90914: hte_init_line_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hte_init_line_attr(struct hte_ts_desc *desc, u32 line_id, long unsigned int edge_flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hte/hte.c (ffffffff81dfeb20)
Location: drivers/hte/hte.c:735
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:hte_edge_setup
```
**Symbols:**

```
ffffffff81dfeb20-ffffffff81dfeba4: hte_init_line_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hte_init_line_attr(struct hte_ts_desc *desc, u32 line_id, long unsigned int edge_flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hte/hte.c (ffffffff81eb5e10)
Location: drivers/hte/hte.c:730
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:hte_edge_setup
```
**Symbols:**

```
ffffffff81eb5e10-ffffffff81eb5e94: hte_init_line_attr (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
