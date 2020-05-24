# A-B Tech Mibew Invitation theme

These invitation styles for Mibew match the 2020 A-B Tech website redesign,
and serves as a companion to the A-B Tech Chat widget styles.

![Invitation widget screenshot render][screenshot]


## Implementation notes

Mibew expects a file called `invite.css` inside this project, as well as some
screenshots, but other than that, this theme folder is purposefully stark.

The `invite.css` file points to the file of the same name in the
[A-B Tech Chat theme]. This was done to leverage gulp tasks like code
compilation, the bootstrap icons and custom avatar image and reduce the
amount of code duplication.

## Installation

The installation and usage assumes Mibew 3.2.6 has already been installed
and configured and the [A-B Tech Chat theme] repository has already
been installed into `/mibew/styles/chat/abtech`. If you haven't done
this yet, start there.

1. In your Mibew installation, create a directory "abtech" inside
    `mibew/styles/invitations/`.
2. Download the latest [zipfile] of this repository's master branch on Github.
3. Unzip the contents into `mibew/styles/invitations/abtech/`.
5. In the web browser visit the Invitation themes preview page at:
    `/mibew/operator/style/invitation/preview` and select "abtech" from the
    dropdown to confirm it is properly installed.
6. In **Mibew Administration > Settings > Optional Services**, click the
   checkbox to __Enable "Tracking and inviting"__ and hit Save.
7. In **Mibew Administration > Button code** generate a new button code with:

        * Chat window style: `abtech`
        * Invitation style: `abtech`

8.  Provie button code to developer for integration into the website.

[screenshot]: https://github.com/BluesparkLabs/abtech-mibew-invitations/blob/master/screenshots/invitation.png?raw=true
[A-B Tech Chat theme]: https://github.com/BluesparkLabs/abtech-mibew-chat
[zipfile]: https://github.com/BluesparkLabs/abtech-mibew-invitations/archive/master.zip
