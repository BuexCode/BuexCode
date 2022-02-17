# BuexCode Design Principles

- Readable /before/ fully optimized and cool code
- non-blocking Snippets
- Reuse of Snippets / Code Blocks / Standardization
- Stable before any Feature
- Network anbaled
- MQTT enabled
- Leveled Security (do not ignore but not for any price)
- delay() aviodance (>1000 msec>)
- 1-3 Quests per NodeMCU, 2 are default
- each in a virtual own "Sub loop"
- Manage Ressources conservatively 
- Cooperative Multitasking / TimeWheelSlot concept 
- Standard variables separated from quest specific naming 
