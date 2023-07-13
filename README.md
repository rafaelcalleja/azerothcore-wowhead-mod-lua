## Azerothcore WowHead Mod Lua

This module creates a npc that allows you to enter a WoWHead URL to get the given GearSet by email.

WoWHead page https://www.wowhead.com/classic/gear-sets

### Requirements:
    1. Server compiled with https://github.com/azerothcore/mod-eluna
    2. Run main.py setting up 3 environment variables: AZEROTHCORE_REMOTE_ADDRESS GM_USERNAME and GM_PASSWORD

### Install
    1. Copy files from lua inside azerothcore lua_script folder. for example ~/azerothcore-wotlk/env/dist/bin/lua_scripts/
    2. Customize file lua_scripts/wowhead.lua: adjust API_ENDPOINT variable.
    3. [Optional] execute up sql from databas directory.
    4. [Optional] create npc with a gm command: .npc add 3442
