# :bomb: DEPRECATED :bomb:
### Please refer to: https://gitlab.cloudopsprod.aws.velocityfrequentflyer.internal/enc/ansible-role-one-partition.git

# one-partition

 Boring but useful

Creates a single partition with the full size of the disk and formats it


Variables

```yml
---
- partitions:
    - disk_volume: "/dev/xdvh"
      format_type: "ext4"
```

