# Function: <code>inode_storage_map_free</code>

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
void inode_storage_map_free(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_inode_storage.c (ffffffff81221480)
Location: kernel/bpf/bpf_inode_storage.c:234
Inline: False
```
**Symbols:**

```
ffffffff81221480-ffffffff812214af: inode_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inode_storage_map_free(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_inode_storage.c (ffffffff81226140)
Location: kernel/bpf/bpf_inode_storage.c:234
Inline: False
```
**Symbols:**

```
ffffffff81226140-ffffffff81226171: inode_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inode_storage_map_free(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_inode_storage.c (ffffffff8125e160)
Location: kernel/bpf/bpf_inode_storage.c:234
Inline: False
```
**Symbols:**

```
ffffffff8125e160-ffffffff8125e191: inode_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inode_storage_map_free(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_inode_storage.c (ffffffff812a85a0)
Location: kernel/bpf/bpf_inode_storage.c:239
Inline: False
```
**Symbols:**

```
ffffffff812a85a0-ffffffff812a85d8: inode_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inode_storage_map_free(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_inode_storage.c (ffffffff81307010)
Location: kernel/bpf/bpf_inode_storage.c:211
Inline: False
```
**Symbols:**

```
ffffffff81307010-ffffffff81307033: inode_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inode_storage_map_free(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_inode_storage.c (ffffffff81335f00)
Location: kernel/bpf/bpf_inode_storage.c:197
Inline: False
```
**Symbols:**

```
ffffffff81335f00-ffffffff81335f23: inode_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inode_storage_map_free(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_inode_storage.c (ffffffff8135a560)
Location: kernel/bpf/bpf_inode_storage.c:197
Inline: False
```
**Symbols:**

```
ffffffff8135a560-ffffffff8135a583: inode_storage_map_free (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
