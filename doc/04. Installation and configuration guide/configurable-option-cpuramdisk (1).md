# Configurable Option (CPU/RAM/DISK)

### Docker NextCloud module **[WHMCS](https://puqcloud.com/link.php?id=77)** 

##### [Order now](https://puqcloud.com/whmcs-module-docker-nextcloud.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-NextCloud/) | [FAQ](https://faq.puqcloud.com/) | [n8n](https://puqcloud.com/link.php?id=117)

In order for the client to have a choice of operating system in the configuration of the virtual machine for NextCloud, you need to configure the Configurable Options and link them to the package.

#### Create Group

Add new Configurable Option to WHMCS

```
System Settings -> Configurable Option -> Create a New Group
```

[![Create Group](https://doc.puq.info/uploads/images/gallery/2022-09/scaled-1680-/image-1663138303613.png)](https://doc.puq.info/uploads/images/gallery/2022-09/image-1663138303613.png)

**Enter the group name, description, and select the products you need.**

**Group Name:** NextCloud

[![Group configuration](https://doc.puq.info/uploads/images/gallery/2025-04/scaled-1680-/image-1745864110464.png)](https://doc.puq.info/uploads/images/gallery/2025-04/image-1745864110464.png)

#### Add Configurable Option

[![Add Options](https://doc.puq.info/uploads/images/gallery/2025-04/scaled-1680-/image-1745864205353.png)](https://doc.puq.info/uploads/images/gallery/2025-04/image-1745864205353.png)

##### CPU|CPU – The first element before `|` must remain unchanged, the second is the label shown to clients

[![CPU Config](https://doc.puq.info/uploads/images/gallery/2025-04/scaled-1680-/image-1745866390473.png)](https://doc.puq.info/uploads/images/gallery/2025-04/image-1745866390473.png)

The first part in the option is responsible for the quantity, and the second is just a description.

##### RAM|MEM – The first element before `|` must remain unchanged, the second is the label shown to clients

[![RAM Config](https://doc.puq.info/uploads/images/gallery/2025-04/scaled-1680-/image-1745866413434.png)](https://doc.puq.info/uploads/images/gallery/2025-04/image-1745866413434.png)

The first part in the option is responsible for the quantity, and the second is just a description.

##### DISK|Disk – The first element before `|` must remain unchanged, the second is the label shown to clients

[![Disk Config](https://doc.puq.info/uploads/images/gallery/2025-04/scaled-1680-/image-1745866456963.png)](https://doc.puq.info/uploads/images/gallery/2025-04/image-1745866456963.png)

The first part in the option is responsible for the quantity, and the second is just a description.