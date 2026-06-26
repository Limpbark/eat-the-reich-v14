# Changelog

All notable changes to this Foundry VTT system are documented here.

## [2.1.0] - 2026-06-26

Community fork maintained by [Limpbark](https://github.com/Limpbark), updated for **Foundry VTT V14**.

### Changed
- **Foundry V14 compatibility.** Manifest now targets `minimum: 14`, `verified: 14.360`. Support for v12/v13 has been dropped.
- Migrated all V13-deprecated globals to their namespaced forms so the system runs warning-free on V14:
  - `renderTemplate` → `foundry.applications.handlebars.renderTemplate`
  - `TextEditor` → `foundry.applications.ux.TextEditor.implementation`
  - `FilePicker` → `foundry.applications.apps.FilePicker.implementation`
  - `DragDrop` → `foundry.applications.ux.DragDrop.implementation`
  - `SortingHelpers.performIntegerSort` → `foundry.utils.SortingHelpers.performIntegerSort`
  - `Actors` / `Items` collections → `foundry.documents.collections.*`
  - `ActorSheet` / `ItemSheet` (sheet unregistration) → `foundry.appv1.sheets.*`
- Removed dead V12 code paths now that the floor is V14: the legacy `renderChatMessage` hook handler, the V12 settings-sidebar branch, and the `game.release.generation` version guards.
- Repointed repository links (manifest, download, bugs, README, in-app GitHub button) to the fork at `Limpbark/eat-the-reich-v14`.

### Credits
Based on the original [Eat the Reich system](https://github.com/philote/eat-the-reich) by Joseph Hopson (ephson) and contributors. The 'Eat The Reich' game is © Rowan, Rook and Decard; artwork © Will Kirkby. Published under the RR&D Community License.
