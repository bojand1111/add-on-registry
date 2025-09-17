# Add-On Registry
A registry for Minecraft Bedrock Add-Ons and their basic meta-data. This is intended to be used by features such as WAILA-add-ons to display accurate information about packs.

If you are an add-on creator, you are welcome to add your pack to the registry so that it can be displayed accurately in other add-ons that display information about content from various add-ons.


## Contribution
To add your pack, add an entry to `registry.js` with the required details, and submit it via pull-request.

Information:
* Key: The key under which you add an entry should be the ID of your add-on. This should be the namespace that your add-on uses for blocks, entities etc.
* `name`: The name of the add-on.
* `creator`: The name of the creator or studio that created the add-on.

Please leave a trailing comma at the end of the list and use 4 spaces for indentation to make merging easier!


## Including it in your pack

