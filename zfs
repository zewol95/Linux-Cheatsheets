# 📌 ZFS Command

## 🔹 Pool Management
| Command                          | Description |
|----------------------------------|-------------|
| `zpool create <pool> <device>`  | Creates a new ZFS pool |
| `zpool destroy <pool>`          | Destroys a ZFS pool |
| `zpool list`                    | Lists available pools |
| `zpool status`                  | Shows the status of pools |
| `zpool scrub <pool>`            | Starts a data integrity check |
| `zpool add <pool> <device>`     | Adds a new device to an existing pool |
| `zpool remove <pool> <device>`  | Removes a device from a pool |
| `zpool export <pool>`           | Exports a pool for use on another system |
| `zpool import <pool>`           | Imports an exported pool |
| `zpool upgrade`                 | Upgrades all pools to the latest ZFS version |

## 📂 Dataset Management
| Command                                 | Description |
|-----------------------------------------|-------------|
| `zfs create <pool>/<dataset>`          | Creates a new dataset |
| `zfs destroy <pool>/<dataset>`         | Deletes a dataset |
| `zfs list`                              | Lists datasets and their properties |
| `zfs rename <pool>/<old> <pool>/<new>` | Renames a dataset |
| `zfs get all <dataset>`                | Retrieves all properties of a dataset |
| `zfs set <property>=<value> <dataset>` | Sets a property on a dataset |

## 🔍 Snapshot and Cloning
| Command                                 | Description |
|-----------------------------------------|-------------|
| `zfs snapshot <pool>/<dataset>@<snap>` | Creates a snapshot |
| `zfs list -t snapshot`                 | Lists all snapshots |
| `zfs rollback <pool>/<dataset>@<snap>` | Rolls back to a snapshot |
| `zfs destroy <pool>/<dataset>@<snap>`  | Deletes a snapshot |
| `zfs clone <pool>/<dataset>@<snap> <pool>/<new_dataset>` | Creates a clone from a snapshot |
| `zfs send <pool>/<dataset>@<snap>`     | Sends a snapshot (for backup/replication) |
| `zfs receive <pool>/<dataset>`         | Receives a sent snapshot |

## 🔒 Quota and Reservations
| Command                                    | Description |
|--------------------------------------------|-------------|
| `zfs get quota <pool>/<dataset>`          | Shows the current quota |
| `zfs set quota=<size> <pool>/<dataset>`   | Sets a quota on a dataset |
| `zfs get reservation <pool>/<dataset>`    | Shows reserved space for a dataset |
| `zfs set reservation=<size> <pool>/<dataset>` | Reserves space for a dataset |

## 🛠️ Compression, Deduplication, and Encryption
| Command                                    | Description |
|--------------------------------------------|-------------|
| `zfs get compression <dataset>`           | Checks compression status |
| `zfs set compression=<on/off/lz4/gzip>`   | Enables/disables compression |
| `zfs get dedup <dataset>`                 | Checks deduplication status |
| `zfs set dedup=<on/off>`                  | Enables/disables deduplication |
| `zfs get encryption <dataset>`            | Checks encryption status |
| `zfs set encryption=<algorithm>`          | Enables encryption (only at dataset creation) |

## 📦 Pool and Dataset Usage
| Command                        | Description |
|--------------------------------|-------------|
| `zfs get used,available <dataset>` | Shows used and available space |
| `zpool list -v`                | Displays detailed pool space usage |
| `zpool iostat -v`              | Shows I/O statistics |
| `zpool history`                | Displays the history of ZFS commands |

## 🏁 Exit and Cleanup
| Command                        | Description |
|--------------------------------|-------------|
| `zpool clear <pool>`           | Clears errors from a pool |
| `zfs destroy -r <pool>/<dataset>` | Recursively deletes a dataset and all snapshots |
| `zpool offline <pool> <device>` | Marks a device as offline |
| `zpool online <pool> <device>`  | Brings a device back online |
