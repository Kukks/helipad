## Testing on an Umbrel device.


If you have an Umbrel device and want to test this app on it, do the following:

1. Go to the root folder of your Umbrel system (where the apps and app-data folders are).
2. Create a new subfolder within the apps folder called "podcasting20-boosts": `mkdir apps/podcasting20-boosts`
3. Save the docker-compose.yml (from this repo) into that new folder.
4. Run this command: `sudo scripts/app install podcasting20-boosts`.