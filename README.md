This repo is used for hosting mod downloads for the Planetary Annihilation Mod Manager

### Usage for non-members

- Fork this repository
- Clone your fork (check it out to your local computer)
- Zip your mod up correctly for PAMM.
- Add it to the user_mods dir.
- Add your update/release to the news tab by copying the commented code in news.html and filling it in with your announcement. (Optional)
- Commit and send a pull request

Then when the pull request is accepted, we'll run the tool to regenerate modlist.json and your mod will be available :) After you make a couple of mods we'll add you as a member so you won't need to wait for your pull requests to be accepted anymore.

### Usage for members

- Clone this repository
- Zip your mod up correctly for PAMM.
- Add it to the user_mods dir.
- Run ListGenerator.exe
  - For Windows .NET Framework 2.0 or higher required
  - For Linux and Mac just run it with Mono (tested with 2.8)
- Add your update/release to the news tab by copying the commented code in news.html and filling it in with your announcement. (Optional)
- Commit all changes (adding/replacing your mod zip and updating modlist.json)
- Push changes

### Help! I don't know git

- Create a github account on https://github.com/
- Download github for windows http://github-windows.s3.amazonaws.com/GitHubSetup.exe
- Set it up.
- Clone this repository using the url: https://github.com/pamods/pamods.github.io.git (You will need to fork it if you are not a member)
- Make changes and push them up (This is the instructions above)


### More information on making mods for PA and how to configure them for PAMM
https://forums.uberent.com/threads/guide-getting-your-mod-on-pamm.55189/
