# Blackwall Tech Static Site

This is the static website for `blackwalltech.com`.

## GitHub Pages

1. Create a GitHub repository, for example `blackwalltech.com`.
2. Push these files to the repository root.
3. In GitHub, open `Settings > Pages`.
4. Set `Source` to `Deploy from a branch`.
5. Choose the `main` branch and `/ (root)`.
6. Keep the custom domain as `blackwalltech.com`.

The `CNAME` file is already included for GitHub Pages custom-domain hosting.

## DNS

For GitHub Pages, point the domain DNS to GitHub Pages:

```text
blackwalltech.com  A      185.199.108.153
blackwalltech.com  A      185.199.109.153
blackwalltech.com  A      185.199.110.153
blackwalltech.com  A      185.199.111.153
www                CNAME  <your-github-username>.github.io
```

Optional IPv6 records:

```text
blackwalltech.com  AAAA   2606:50c0:8000::153
blackwalltech.com  AAAA   2606:50c0:8001::153
blackwalltech.com  AAAA   2606:50c0:8002::153
blackwalltech.com  AAAA   2606:50c0:8003::153
```

After GitHub verifies the domain, enable `Enforce HTTPS`.
