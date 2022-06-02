# SkyblockAddons

Bug Fixes
- Fix Crystal Hollows and Forge warps not being clickable for non-MVP+ players despite being unlocked (#609)
- Fix dungeon map markers being offset
- Data downloading improvements
 - Increase timeouts for requests
 - Retry requests twice before failing
 - Use Crowdin CDN for localized strings
 - Don't download online strings for English
 - Add root cause message to LoadingException
 - Add error message in chat for failed requests when player joins Skyblock
 - Fix delayed flag change after changing language
