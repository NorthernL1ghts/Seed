# Seed (Part of the Briefcase project)

- Your seed node should have port **20202** publicly accessible. It may be pinged from time to time to determine its validity and reliability.

To add to the list of seed nodes on the network, simply add your node to `seed.csv`.

The file has two columns: `type` and `value`.

- `type` is one of `ipv4`, `ipv6`, or `domain`, where `domain` is resolved in the DNS.
- `value` is the respective address of the node you're trying to add.

For example:
  - `ipv4`, 127.0.0.1
  - `ipv6`, ::1
  - `domain`, localhost
