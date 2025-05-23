# Function: <code>__sgx_get_key_hash</code>

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
int __sgx_get_key_hash(struct crypto_shash *tfm, const void *modulus, void *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81066ee0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:469
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
**Symbols:**

```
ffffffff81066ee0-ffffffff81066f30: __sgx_get_key_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sgx_get_key_hash(struct crypto_shash *tfm, const void *modulus, void *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067480)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:470
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
**Symbols:**

```
ffffffff81067480-ffffffff810674d0: __sgx_get_key_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sgx_get_key_hash(struct crypto_shash *tfm, const void *modulus, void *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81071830)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:470
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
**Symbols:**

```
ffffffff81071830-ffffffff81071880: __sgx_get_key_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sgx_get_key_hash(struct crypto_shash *tfm, const void *modulus, void *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107f5f0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:470
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
**Symbols:**

```
ffffffff8107f5f0-ffffffff8107f663: __sgx_get_key_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sgx_get_key_hash(struct crypto_shash *tfm, const void *modulus, void *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810914c0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:459
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
**Symbols:**

```
ffffffff810914c0-ffffffff81091533: __sgx_get_key_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sgx_get_key_hash(struct crypto_shash *tfm, const void *modulus, void *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81094400)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:459
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
**Symbols:**

```
ffffffff81094400-ffffffff81094473: __sgx_get_key_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sgx_get_key_hash(struct crypto_shash *tfm, const void *modulus, void *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109b8e0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:459
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
**Symbols:**

```
ffffffff8109b8e0-ffffffff8109b953: __sgx_get_key_hash (STB_LOCAL)
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
