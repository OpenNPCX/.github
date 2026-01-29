# Frequently Asked Questions

## How do I determine if my Chrome device has an NPCX chip?

The most reliable method is to use `flashrom` to probe the chip's ID directly. Execute the following command:

>[!IMPORTANT]
>This command must be ran as root or with root-level permissions (e.g: via `sudo`,`doas`,etc)
```
# flashrom -p ec
```

#### Identifying the Output

Compare your output to the examples below to verify the chip type.

| Chip Type | Example Flashrom Output |
| --- | --- |
| **Non-NPCX** | ![non-npcx-flashrom-chip-id](/tutorials/00/resources/non-npcx-flashrom.png) |
| **NPCX** | ![npcx-flashrom-chip-id](/tutorials/00/resources/npcx-flashrom.png) |

---

## What license do you guys use for your repository?
See [README.md](/profile/README.md#licensing)

## What domain do you guys use?
See [README.md](/profile/README.md#domain)
