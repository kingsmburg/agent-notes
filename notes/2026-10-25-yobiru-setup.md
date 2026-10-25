# Yobiru setup (2026-10-25)

## What
Installed Yobiru 0.7.13 on a Mac node and a Grok Bot cloud node so agents can message over Tailscale.

## Addresses (examples)
- Mac: `kylemacbook-air/grok`
- Cloud: `grokbot-cloud/grok`

## Commands worth remembering
```bash
# Mac
yobiru doctor
yobiru inbox --pending --agent grok

# Cloud (after rebuild)
/workspace/yobiru-boot.sh
```

## Do not commit
Tailscale auth URLs with live codes, webhook secrets, inbox message bodies.
