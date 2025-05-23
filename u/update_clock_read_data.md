# Function: <code>update_clock_read_data</code>

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
void update_clock_read_data(struct clock_read_data *rd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/sched_clock.c (ffff8000101b4340)
Location: kernel/time/sched_clock.c:124
Inline: False
Direct callers:
  - kernel/time/sched_clock.c:sched_clock_register
  - kernel/time/sched_clock.c:update_sched_clock
```
**Symbols:**

```
ffff8000101b4340-ffff8000101b43c8: update_clock_read_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void update_clock_read_data(struct clock_read_data *rd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/sched_clock.c (c03fded4)
Location: kernel/time/sched_clock.c:124
Inline: False
Direct callers:
  - kernel/time/sched_clock.c:sched_clock_register
  - kernel/time/sched_clock.c:update_sched_clock
```
**Symbols:**

```
c03fded4-c03fdf5c: update_clock_read_data (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void update_clock_read_data(struct clock_read_data *rd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/sched_clock.c (ffffffe00013a742)
Location: kernel/time/sched_clock.c:124
Inline: False
Direct callers:
  - kernel/time/sched_clock.c:sched_clock_register
  - kernel/time/sched_clock.c:update_sched_clock
```
**Symbols:**

```
ffffffe00013a742-ffffffe00013a7ae: update_clock_read_data (STB_LOCAL)
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
