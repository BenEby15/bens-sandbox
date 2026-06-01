# All County Collision Plugin

Content writing plugin for All County Collision (Eustis, FL). Replaces the All County Collision Custom GPT with an installable Cowork plugin.

## What's inside

One skill: `all-county-collision-writer`. Triggers when you ask Claude to write content for All County Collision, ACC, Ryan DeMarco, or the body shop in Eustis/Oxford FL. Handles all content types: blogs, website content, service pages, landing pages, GBP posts, FAQs, press releases, and social posts.

## Knowledge structure

**Primary** (source of truth — `skills/all-county-collision-writer/references/primary/`):

- `services.md`
- `company-overview.md`
- `competitive-positioning.md`
- `marketing-and-brand.md`
- `owner-story-and-mission.md`
- `certifications.md`

**Secondary** (supporting reference — `skills/all-county-collision-writer/references/secondary/`):

- `warranty.md`
- `repair-contract.md`
- `market-data-eustis.md`
- `market-data-oxford.md`

## Install in Cowork

From this repo:

1. Open Cowork
2. Open the plugin manager
3. Add this repo URL as a plugin source: `https://github.com/BenEby15/bens-sandbox`
4. Install the `all-county-collision` plugin

## Updating

Pull the latest from this repo. Cowork picks up the changes on next session start (or via the plugin manager).

## Usage

In any Cowork chat, just describe what you need:

- "Write a 1200-word Big 5 blog for All County Collision about Tesla collision repair. Target keyword: tesla collision repair eustis fl."
- "Draft 5 GBP posts for All County Collision focused on ADAS calibration."
- "Build a service page for All County Collision about structural repair. 800 words. Eustis FL primary location."

The skill fires automatically when it detects the request is about All County Collision.
