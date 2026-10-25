ROMERO FAMILY — animated mobile app prototype

Files:
- index.html: complete mobile-first app UI and demo interactions
- manifest.json: PWA install metadata
- sw.js: basic offline caching

Included:
- Animated page transitions, subtle red glow, shimmer, interactive tile feedback, and radio-disc rotation while playing
- Home dashboard
- Demo Gang Roster and rank filtering
- Rank labels and demo role hierarchy
- Announcements, including demo admin publishing
- Local demo chat
- Photo gallery preview
- Radio stream URL player
- La Maison info and saved location
- Member of the Month
- VIP Lounge
- Admin demo panel for adding members and announcements

Important:
This is a front-end prototype. Demo data is stored in the browser on one device only.
It does NOT yet have real user authentication, shared cloud chat, secure admin permissions,
shared photo uploads, or a deployed public URL. Those require a backend and deployment.
To install as a PWA, host these files over HTTPS, then use the browser's Add to Home Screen
(or Install App) option. Opening index.html directly is only a preview and may not enable
PWA installation or offline mode.
