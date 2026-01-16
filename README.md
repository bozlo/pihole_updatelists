# blocklist or whitelist for pihole

My pihole uses https://github.com/jacklul/pihole-updatelists?tab=readme-ov-file

In my pihole/etc-pihole-updatelists/pihole-updatelists.conf

```
BLOCKLISTS_URL="https://v.firebog.net/hosts/lists.php?type=tick https://raw.githubusercontent.com/bozlo/pihole_updatelists/refs/heads/main/blocklist-collection.txt"
ALLOWLISTS_URL="https://raw.githubusercontent.com/bozlo/pihole_updatelists/refs/heads/main/whitelist-collection.txt"

BLACKLIST_URL=""
WHITELIST_URL=""
```
