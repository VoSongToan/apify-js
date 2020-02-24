---
id: system-status-options
title: SystemStatusOptions
---

<a name="systemstatusoptions"></a>

## Properties

### `currentHistorySecs`

**Type**: `Number` <code> = 5</code>

Defines max age of snapshots used in the [`SystemStatus.getCurrentStatus()`](/docs/api/system-status#getcurrentstatus) measurement.

---

### `maxMemoryOverloadedRatio`

**Type**: `Number` <code> = 0.2</code>

Sets the maximum ratio of overloaded snapshots in a memory sample. If the sample exceeds this ratio, the system will be overloaded.

---

### `maxEventLoopOverloadedRatio`

**Type**: `Number` <code> = 0.2</code>

Sets the maximum ratio of overloaded snapshots in an event loop sample. If the sample exceeds this ratio, the system will be overloaded.

---

### `maxCpuOverloadedRatio`

**Type**: `Number` <code> = 0.4</code>

Sets the maximum ratio of overloaded snapshots in a CPU sample. If the sample exceeds this ratio, the system will be overloaded.

---

### `maxClientOverloadedRatio`

**Type**: `Number` <code> = 0.2</code>

Sets the maximum ratio of overloaded snapshots in a Client sample. If the sample exceeds this ratio, the system will be overloaded.

---

### `snapshotter`

**Type**: [`Snapshotter`](/docs/api/snapshotter)

The `Snapshotter` instance to be queried for `SystemStatus`.

---