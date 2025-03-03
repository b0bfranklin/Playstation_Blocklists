# Playstation Blocklists

This repository contains blocklists for Pi-hole to block update servers for PlayStation 4 and PlayStation 5. These blocklists can be used to prevent your console from downloading updates.

## Blocklists

### PS4 Blocklist
The PS4 blocklist contains domains related to PlayStation 4 update servers.

- [ps4_blocklist.txt](ps4_blocklist.txt)

### PS5 Blocklist
The PS5 blocklist contains domains related to PlayStation 5 update servers.

- [ps5_blocklist.txt](ps5_blocklist.txt)

## Usage

To use these blocklists with Pi-hole, follow these steps:

1. Go to the Pi-hole admin interface.
2. Navigate to "Group Management" -> "Adlists."
3. Add the URL to the raw version of the blocklist file to the "Address" field.
   - For PS4: `https://raw.githubusercontent.com/b0bfranklin/Playstation_Blocklists/main/ps4_blocklist.txt`
   - For PS5: `https://raw.githubusercontent.com/b0bfranklin/Playstation_Blocklists/main/ps5_blocklist.txt`
4. Click "Add" to include the blocklist in your Pi-hole configuration.
5. Update your Pi-hole gravity list by running `pihole -g` on your Pi-hole server.

## Disclaimer

Use these blocklists at your own risk. Blocking update servers may prevent your console from receiving important updates and fixes.
