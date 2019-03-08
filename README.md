# Discord Invite in JS, HTML and CSS, CREDIT FOR JS/CSS TO <a href="https://github.com/Aegis7Gaming/Discord-Invite-JS-HTML-CSS">Aegis7Gaming</a>
A very-close-to-native Discord Invite script for websites.

miniMode Example:  
![Example of Discord Invite in miniMode](savestate.png?raw=true "Discord Invite Example: Savestate Discord (miniMode)")

## How to use
 1. Download the files. (discordInvite.js, discordInvite.css)
 1. Upload the files to your web server.
 1. Include the CSS file in the head of the page:
    ```html
    <head>
    <link rel="stylesheet" href="/path/to/discordInvite.css"/>
    </head>
    ```
 1. Include the JS file and initialise on the page:
    ```html
    <body>
    <script src="/path/to/discordInvite.js"></script>
    <script>
      discordInvite.init({
      inviteCode: '7ffxmPA',
      title: 'Savestate Discord',
      miniMode: 'True',
    });
    discordInvite.render();
    </script>
    </body>
    ```
1. Place this specific `<div>` wherever you want your invite to appear:
    ```html
    <div id="discordInviteBox"></div>
    ```
    
## No Support, 'as is'.
Please do not contact us for any support. We will do our best to provide updates when necessary and willing to accept pull requests but you should not expect us to fix issues for you, walk you through how to deploy this or anything of that nature.

## Discord
We are not affiliated in any way with Discord. We're just really big fans and we enjoy the platform! If at any time Discord and/or their staff tell us this isn't OK, we will take the script down. We're querying Discord servers and they can very well put this behind an Authentication layer, if this happens or the data is hidden or changed, this script will stop working; Please keep this in mind.
