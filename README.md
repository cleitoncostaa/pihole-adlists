![Pi-hole Logo](Pi-hole_Logo.png)

# Pi-hole Adlists

Curated references for Pi-hole blocklists used in a home lab / home network context.

## Main List

Use this URL in Pi-hole:

```text
https://raw.githubusercontent.com/cleitoncostaa/pihole-adlists/main/adlists/adlist1.txt
```

## How To Add

1. Open Pi-hole Admin.
2. Go to **Group Management > Adlists**.
3. Paste the raw URL above.
4. Click **Add**.
5. Run **Tools > Update Gravity**.

## Maintenance Rules

- Keep one URL per line in `adlists/adlist1.txt`.
- Prefer raw file URLs instead of GitHub HTML pages.
- Avoid duplicates.
- Review aggressive categories before using them in family or work networks.
- Validate availability before relying on a new external list.

## Notes

Some external lists can block social networks, messaging apps, games, gambling, adult content or telemetry. Enable only what matches the network policy you actually want.

## Official References

- [Pi-hole Documentation](https://docs.pi-hole.net/)
- [Pi-hole GitHub](https://github.com/pi-hole/pi-hole)
