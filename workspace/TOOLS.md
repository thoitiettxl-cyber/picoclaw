# Notes for Skills

Skills define how tools work. This file is for your specifics — the stuff that's unique to your setup.

## What Goes Here

Things like:

- Camera names and locations
- SSH hosts and aliases
- Preferred voices for TTS
- Speaker/room names
- Device nicknames
- Anything environment-specific

### Tool Usage Rules
- **Playbook Tools**: Nếu tool được đề cập trong Playbook/Knowledge, **mặc định là có sẵn**. KHÔNG cần kiểm tra version (`--version`), dùng luôn để tiết kiệm token & thời gian.

## Examples

```markdown
### Cameras
- living-room → Main area, 180° wide angle
- front-door → Entrance, motion-triggered

### SSH
- home-server → 192.168.1.100, user: admin

### TTS
- Preferred voice: "Nova" (warm, slightly British)
- Default speaker: Kitchen HomePod
```

## Why Separate?

Skills are shared. Your setup is yours. Keeping them apart means you can update skills without losing your notes, and share skills without leaking your infrastructure.

Add whatever helps you do your job. This is your cheat sheet.
