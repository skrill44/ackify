## 📜 Commands

### Announcements

/announce create title:<text> body:<text>
/announce list
/announce delete id:<number>
/announce toggleack on|off

### Checklists

/checklist create name:<text>
/checklist list
/checklist view id:<number>
/checklist add id:<number> item:<text>
/checklist done itemid:<number>
/checklist delete id:<number>

### Moderation
/ban user:<user> reason:<text?>
/kick user:<user> reason:<text?>
/timeout user:<user> duration:<time> reason:<text?>
/untimeout user:<user>

### Settings
/settings view
/settings setstaff role:<role>
/settings setlog channel:<channel>
/settings setannounce channel:<channel>
/settings toggleack on|off
/settings adminonly on|off

### 📝 Logging

To enable moderation logs:

/settings setlog channel:#mod-logs

All bans, kicks, and timeouts will appear there automatically.
