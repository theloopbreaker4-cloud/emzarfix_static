# Emzar — Washing Machine Repair Tbilisi

Static landing site for **Emzar** — professional washing machine repair in Tbilisi, Georgia.

- **Domain**: TBD
- **Server**: CX23 · `/var/www/emzar`
- **Stack**: Pure HTML/CSS/JS, no build step
- **Phone**: +995 557 500 458

## Deploy

```bash
# When domain is ready — issue SSL
ssh root@SERVER "certbot --nginx -d DOMAIN -d www.DOMAIN --non-interactive --agree-tos -m YOUR_EMAIL"

# Update site
ssh root@SERVER "cd /var/www/emzar && git pull"
```
