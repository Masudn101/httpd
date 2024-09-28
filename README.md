# httpd


Here’s a list of common **RHEL 8 services** along with their **package names** and **configuration file locations**:

| **Service Name**    | **Package Name**       | **Configuration File**                                |
|---------------------|------------------------|-------------------------------------------------------|
| `httpd`             | `httpd`                | `/etc/httpd/conf/httpd.conf`                          |
| `sshd`              | `openssh-server`       | `/etc/ssh/sshd_config`                                |
| `firewalld`         | `firewalld`            | `/etc/firewalld/firewalld.conf`                       |
| `crond`             | `cronie`               | `/etc/crontab`, `/etc/cron.d/*`, `/etc/cron.hourly/*` |
| `NetworkManager`    | `NetworkManager`       | `/etc/NetworkManager/NetworkManager.conf`             |
| `chronyd`           | `chrony`               | `/etc/chrony.conf`                                    |
| `rsyslog`           | `rsyslog`              | `/etc/rsyslog.conf`                                   |
| `postfix`           | `postfix`              | `/etc/postfix/main.cf`                                |
| `cups`              | `cups`                 | `/etc/cups/cupsd.conf`                                |
| `nginx`             | `nginx`                | `/etc/nginx/nginx.conf`                               |
| `mariadb`           | `mariadb-server`       | `/etc/my.cnf`, `/etc/my.cnf.d/`                       |
| `docker`            | `docker`               | `/etc/docker/daemon.json`                             |
| `podman`            | `podman`               | `~/.config/containers/containers.conf`                |
| `redis`             | `redis`                | `/etc/redis.conf`                                     |
| `rsync`             | `rsync`                | `/etc/rsyncd.conf`                                    |
| `vsftpd`            | `vsftpd`               | `/etc/vsftpd/vsftpd.conf`                             |
| `named` (DNS)       | `bind`                 | `/etc/named.conf`                                     |
| `samba`             | `samba`                | `/etc/samba/smb.conf`                                 |
| `dhcpd`             | `dhcp-server`          | `/etc/dhcp/dhcpd.conf`                                |
| `libvirtd`          | `libvirt`              | `/etc/libvirt/libvirtd.conf`                          |
| `xinetd`            | `xinetd`               | `/etc/xinetd.conf`                                    |
| `ntpd`              | `ntp`                  | `/etc/ntp.conf`                                       |

This list covers some of the most common services. If you need more specific packages or services, let me know!
