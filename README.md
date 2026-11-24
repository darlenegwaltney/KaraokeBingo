# Karaoke Bingo

A bingo game for karaoke night. Each player opens the link on their phone, types their name and gets their own random card. They tap a square when someone sings a song that fits it. When they complete a line, the game shows "Bingo!" and they show their card to the host.

- No sign-up, no app to install.
- Each card is shuffled at random and saved on that player's phone, so closing the page doesn't lose it.
- Each card shows a short code (like "Card TZMJ") to tell cards apart.

---

## Files

| File | What it is |
|---|---|
| `index.html` | The whole game. This is the only file the site needs. |
| `README.md` | These instructions. Optional to upload. |

---

## Put it online with GitHub Pages (about 10 minutes, free)

You can do this on a computer or a phone browser. On a phone, use the GitHub **website** in Safari or Chrome, not the GitHub app, because the app can't upload files. If a button is hidden on a phone, switch the browser to **Request Desktop Website**.

### 1. Create a GitHub account
Go to https://github.com and sign up (free). Your username becomes part of the game's web address.

### 2. Create a repository (a folder for the site)
1. Click the **+** at the top right, then **New repository**.
2. **Repository name:** `karaoke-bingo` (or anything you like, with no spaces).
3. Choose **Public**. GitHub Pages is free only for public repositories.
4. Click **Create repository**.

### 3. Upload the files
1. On the new repository page, click **uploading an existing file** (or **Add file → Upload files**).
2. Drag in or choose `index.html` and `README.md`. Unzip the download first if needed.
3. Scroll down and click **Commit changes**.

The file must be named exactly `index.html`, all lowercase.

### 4. Turn on GitHub Pages
1. In the repository, click **Settings**. On a phone it may be under the **···** menu.
2. In the left menu, click **Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Under **Branch**, choose **main** and **/ (root)**, then click **Save**.

### 5. Get your link
Wait 1 to 2 minutes and refresh the Pages settings screen. A box appears that says **"Your site is live at…"**. Your link will look like this:

```
https://YOUR-USERNAME.github.io/karaoke-bingo/
```

Open it on your own phone to check it works, then text it to your friends or turn it into a QR code (search "QR code generator").

---

## Changing the categories or the game name

1. In the repository, click `index.html`, then the **pencil icon** (Edit).
2. Near the top, find the section marked **EDIT YOUR GAME HERE**.
3. Change `GAME_TITLE` to rename the game (for example `"Gwaltney Karaoke Bingo"`).
4. Edit the list. Put each category in quotes with a comma after it:
   ```
   "Classic rock",
   "Backup dancer",
   ```
5. Click **Commit changes**. The live site updates in a minute or two.

Card size is chosen automatically:
- **24 or more categories:** 5 × 5 with a free centre (each card uses 24 at random)
- **16 to 23:** 4 × 4
- **9 to 15:** 3 × 3

When you change the list, everyone gets a fresh card the next time they open the page.

---

## Playing tips

- **Starting over:** players tap **Deal a new card** (and tap again to confirm), or **Clear my dabs** to keep the same card with no marks.
- **Checking a Bingo:** have the winner show their screen. The winning line is outlined in yellow.
- **Long category names** are shortened on the square. Tap the square to read the full name below the card.
- **Lost card:** cards are saved in the phone's browser. A private or incognito window, or clearing browser data, loses the card, and the player just deals a new one.

---

## Troubleshooting

- **404 / "There isn't a GitHub Pages site here":** wait a couple more minutes. Then check that the file is named `index.html` and that Pages is set to the **main** branch and **/ (root)** folder.
- **The old list still shows after an edit:** refresh the page. GitHub can take a few minutes to update.
- **Typo in the list breaks the page:** each category needs quotes on both sides and a comma after it. Use straight quotes `"` rather than curly ones `“ ”`.
