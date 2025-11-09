# Portal Protocol Game Improvements TODO

## Priority 1: Bug Fixes
- [ ] Remove duplicate CSS blocks for #pauseMenu and consolidate styles.
- [ ] Move door interaction code outside the chestItems.forEach loop to prevent incorrect execution.
- [ ] Declare settingsButton and other variables before use; fix any undefined references in settings logic.

## Priority 2: Inventory Enhancement
- [ ] Modify chest item click to add item to first available hotbar slot instead of alert.
- [ ] Update hotbar click to "use" item (e.g., equip gun for shooting, medkit for health if added).
- [ ] Add item images/icons to hotbar slots.

## Priority 3: Add Shooting Mechanics
- [ ] Introduce bullet objects if gun is equipped; space key shoots bullets.
- [ ] Add basic collision detection for bullets.

## Priority 4: Add Enemies and Objectives
- [ ] Create simple enemy objects that move horizontally; player bullets can defeat them.
- [ ] Add health system; enemies damage player on collision.
- [ ] Objective: Defeat all enemies in a level to "stabilize rift".

## Priority 5: Improve Graphics
- [ ] Replace player rectangle with an image (e.g., load a sprite from URL).
- [ ] Add enemy sprites.

## Priority 6: Polish and Features
- [ ] Improve cutscene typing speed and smoothness.
- [ ] Add background music toggle in settings.
- [ ] Save/load full game state (position, inventory, progress) to localStorage.
- [ ] Add more levels/rooms via portals.

## Testing
- [ ] Test the game by launching in browser and verify all features.
