# Future Publication and Visibility

**Current state:** No player wiki requested or configured. This repository is currently public; Markdown labels do not protect secrets. Do not commit confidential notes or spoilers assuming visibility: gm will conceal them.

## Long-term design

Keep Markdown canon as the authoring source of truth. A future publisher may produce a player wiki, GM manual, handouts, setting guide or system-specific material as derivative exports, never competing canonical documents.

Suggested canon frontmatter:
- status: canon | provisional | disputed | idea | superseded
- visibility: player | gm | spoiler
- type: lore category
- source_refs: citations into source/research records

**Fail-closed rule for future exports:** publish only explicitly marked, approved player-safe material. Invalid/missing metadata excludes a page; reject suspect mixed-visibility pages until reviewed. A player-facing summary of a spoiler-heavy topic should preferably have a separate safe page or safe excerpt whose inclusion can be tested.

Before any public wiki launch:
1. Decide whether authoring repo becomes private (recommended before meaningful spoilers).
2. Establish filtering and editorial policy.
3. Build isolated publication output and verify excluded GM/spoiler content.
4. Verify links/navigation, attachment rights, and asset provenance.
5. Review preview manually; publish intentionally.
6. Never assume a successful build is proof against information leakage.

A public GitHub history is still public even after an article is removed; plan repository privacy before spoilers are written.

