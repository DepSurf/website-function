# Function: <code>bpf_iter_bpf_sk_storage_map</code>

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
int bpf_iter_bpf_sk_storage_map(struct bpf_iter_meta *meta, struct bpf_map *map, struct sock *sk, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff8301c17e)
Location: net/core/bpf_sk_storage.c:820
Inline: False
```
**Symbols:**

```
ffffffff8301c17e-ffffffff8301c18b: bpf_iter_bpf_sk_storage_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_iter_bpf_sk_storage_map(struct bpf_iter_meta *meta, struct bpf_map *map, struct sock *sk, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff832272bf)
Location: net/core/bpf_sk_storage.c:820
Inline: False
```
**Symbols:**

```
ffffffff832272bf-ffffffff832272cc: bpf_iter_bpf_sk_storage_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_iter_bpf_sk_storage_map(struct bpf_iter_meta *meta, struct bpf_map *map, struct sock *sk, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff8331165f)
Location: net/core/bpf_sk_storage.c:819
Inline: False
```
**Symbols:**

```
ffffffff8331165f-ffffffff8331166c: bpf_iter_bpf_sk_storage_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_iter_bpf_sk_storage_map(struct bpf_iter_meta *meta, struct bpf_map *map, struct sock *sk, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff834cb476)
Location: net/core/bpf_sk_storage.c:830
Inline: False
```
**Symbols:**

```
ffffffff834cb476-ffffffff834cb487: bpf_iter_bpf_sk_storage_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_iter_bpf_sk_storage_map(struct bpf_iter_meta *meta, struct bpf_map *map, struct sock *sk, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff83f0d890)
Location: net/core/bpf_sk_storage.c:800
Inline: False
```
**Symbols:**

```
ffffffff83f0d890-ffffffff83f0d8a1: bpf_iter_bpf_sk_storage_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_iter_bpf_sk_storage_map(struct bpf_iter_meta *meta, struct bpf_map *map, struct sock *sk, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff83733e80)
Location: net/core/bpf_sk_storage.c:798
Inline: False
```
**Symbols:**

```
ffffffff83733e80-ffffffff83733e91: bpf_iter_bpf_sk_storage_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_iter_bpf_sk_storage_map(struct bpf_iter_meta *meta, struct bpf_map *map, struct sock *sk, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff839683c0)
Location: net/core/bpf_sk_storage.c:799
Inline: False
```
**Symbols:**

```
ffffffff839683c0-ffffffff839683d1: bpf_iter_bpf_sk_storage_map (STB_GLOBAL)
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
