# redvault

A distributed nearline backup system.

## Idea

* Use available space on many (remote) disks to backup data.
* Split data into shards for for effective usage of storage space.
* Rule based replication of shards over multiple disks/computers for redundancy.
* Use SSH for remote access.

  * No dedicated server software needed.
  * SSH takes care of access security.

* Use YAML header and tar body for shard format.
