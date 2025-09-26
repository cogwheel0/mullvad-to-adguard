# AdGuard Home Lists (Adblock-style only)

Source: mullvad/dns-blocklists/output/doh.
Categories equal upstream filenames (minus doh_/relay_ and extension).

## Outputs
- all/adblock.txt
- categories/<category>/adblock.txt

Each rule is Adblock syntax: ||domain^ (blocks the domain and all its subdomains).
