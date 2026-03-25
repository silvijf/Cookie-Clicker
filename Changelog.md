
# CHANGELOG
The changlog started on May 24th 2026.

#### Possible sizes of updates from small to big
1. Bug fixes
2. Small change
3. Update
4. Big update
5. Mayor Update

1 and 2 should not change gameplay.

### Still working on
- When progress is loaded, the prices on the buttons are not updating.
- Ten million is currently being written as "10000000", this should be "10,000,000".

## Some little fixes (May 25th 2026): bug fixes
- When progress was loaded, decimal numbers could appear in the buy buttons. This is now fixed.

## Round down system fixed (May 24th 2026): bug fixes
- Fixed the round down system (the previous "fix" didn't work)
- The selling values were not updating if a player bought an item and the prices were not updating if a player sold an item. This is fixed in this update.
- ~~Fixed link to Cookie Clicker Manual.~~ Did <ins>**not**</ins> work.

## Round down system fixed (May 24th 2026): bug fixes
- ~~Fixed the round down system (it came with the New price system update) by replacing Math.floor by Math.trunc~~ Did <ins>**not**</ins> work.

## New price system and more (May 24th 2026): mayor update
- Made the price system. The prices of items will rise if you buy one. The formula for the price is: base cost × 1.15<sup>Current amount of buildings</sup>. The selling price is always 25% of the current price rounded down.
- Made "localStorage-setter" (function "createLocalVariables") for new players
- Ten million is now written as "10000000". This is due to the new price system. If anyone knows how to solve, please send me a pull request.

## Some little changes(May 24th 2026): bug fixes
- Shortened the check lists for the cursor in de function "updateButtons()"
- Made the cookie undraggable
- Changed some "oma's" to "grannies"

## Autosafe switch (May 24th 2026): small change
- Improved appearance of the autosafe switch

## Wizard Tower Update (May 24th 2026): big update
- Wizard Tower added
- Used English number system. For example, ten million was "10.000.000", and now it is '10,000,000".
- Fixed the favicon
