# Backrooms Builder

A browser playtest of the Unity game: arrange connected rooms, add creatures, then explore your world in first person.

Open the GitHub Pages game in Safari on an iPad or a recent desktop browser. Turn the iPad sideways and tap **Enter the backrooms** after loading.

- Drag room cards to build. Matching doorways appear automatically.
- Choose Entities to add creatures; use Blue Tape to connect environments.
- Explore with the left thumb to move and the right thumb to look. Tap Sprint to run.
- On a computer, use WASD, hold the right mouse button to look and hold Shift to sprint.
- Worlds save in this browser. Keep the site's data and use a normal browsing tab to retain them.
- Five taps on the BACKROOMS title reveal the Baldi school Easter egg.

The school cameo is fan artwork referencing [Baldi's Basics by Basically Games](https://www.basicallygames.com/baldis-basics-classic). Character models, room geometry and sounds in this prototype are created locally; no original-game assets or recordings are bundled.

This repository contains the generated Unity WebGL player. The Unity source project and native iPad build are maintained separately. The download uses Unity's gzip fallback so it can run on GitHub Pages without custom server headers.


## Bacteria and pipe slides

Choose **Entities → Bacteria** to place the wiry hunter. In **Pipes**, drag a colour onto an outside wall, then choose a matching exit in another room or area. Choose **Safe** or **Death** before placing: safe pipes always reach the matching exit, and death pipes always drop into the void. To change an existing pair, select Safe or Death and tap either pipe mouth. Death pipes have an X marker in the builder. Older random pipes become safe when upgrading. Multiple pairs, paired erase/undo and existing-save upgrades are supported.

Bacteria is an original procedural fan model inspired by the Backrooms Lifeform silhouette popularised by Kane Pixels; no original game models or recordings are included.

## Friendly hazmat explorers

Choose **0, 1 or 2** under **Hazmat explorers** in the builder. The visitors wear yellow suits, dark visors and air packs. They pick their own routes, pause to look around, and wave when they see you before continuing. They do not attack or block you. The visitor count saves with your world.
