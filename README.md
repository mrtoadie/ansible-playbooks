# ansible-playbooks

> [!NOTE]
> In some Playbooks, you may need to adjust *paths* / *users* or other *parameters*.
## Playbooks
### Linux
- **Git**
  - **[Git]()**
    - *[git_01.yml]()*
    - *[git_02.yml]()*
    - *[git_03.yml]()*
- **System**
  - **[Backups]()**
    - *[backup_local_01.yml]()*
    - *[backup_local_02.yml]()*
  - **[Maintenance]()**
    - *[reboot.yml]()*
    - *[shutdown_classic.yml]()*
    - *[shutdown_systemd.yml]()*
  - **[Monitoring]()**
    - *[diskspace_linux.yml]()*
    - *[gather_facts_01.yml]()*
    - *[gather_facts_02.yml]()*
    - *[gather_facts_03.yml]()*
  - **[Updates]()**
    - *[arch_update.yml]()*
    - *[centos_update.yml]()*
    - *[ubuntu_update.yml]()*
- **Virtual Machines**
  - **[KVM]()**
    - *[check_running_vms_01.yml]()*
    - *[check_running_vms_02.yml]()*
---

> [!CAUTION]
> For **safety**, you should never test Playbooks on a productive system!