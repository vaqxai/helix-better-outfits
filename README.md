# helix-better-outfits
Better outfit item base for the Helix framework

1. Improved bodygroup mixing: You can omit resetting bodygroups when applying new ones, using: `ITEM.noResetBodyGroups = true`
2. Added model whitelisting: Only allow certain models to use your bodygroup-related items, using: `ITEM.allowedModels = {"abc.mdl"}`
3. Fixed Skins not being saved. Items using `ITEM.newSkin = n` will now properly save between character reloads.
