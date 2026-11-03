AyuGram+ (custom AyuGram Desktop build for Windows x64)
========================================================

Portable: unzip to a writable folder and run AyuGram.exe (data is usually
stored next to the exe in "tdata"). Auto-update is disabled in this build so it is never
replaced by the official AyuGram.

Changes compared to AyuGram Desktop:
- Win11 Red (red/black) theme is the built-in night theme and is enabled by
  default ("Follow system theme" keeps it on; turn that off in Settings >
  Chat settings to choose another theme). Extra variants are in themes\
  (Win11-Red-AMOLED, Win11-Red-Glass) - open them from Telegram to apply.
- Unified horizontal tab bar above the chat list:
  Inbox (All chats), Channels, Groups, Chats (local folders by chat type,
  not synced to your account) + your own folders, then
  Downloads, Music, Video, Photo, Stories (open the existing views).
- Saving of deleted / edited messages is ON by default (AyuGram default).
- No message send animation; typing / upload status is not sent by default
  (Settings > AyuGram > Ghost mode to change).
- Slightly faster uploads (bigger parts, 2 MB in flight per session,
  100 ms request interval; still 8 sessions max, conservative to avoid
  FLOOD_WAIT).

Uses AyuGram's documented public API credentials (docs/api_credentials.md).
