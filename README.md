# Userscripts

## [Reddit Comment/Post Mass Deleter](https://greasyfork.org/en/scripts/540119-reddit-comment-post-mass-deleter/)

## Usage

### On **old.reddit.com**:

Make sure you are viewing your user page in the **old Reddit interface**:

- Comments page URL pattern:  
  `https://old.reddit.com/user/yourusername/comments/`

- Posts (submitted) page URL pattern:  
  `https://old.reddit.com/user/yourusername/submitted/`

---

### Buttons available on the Comments page:

- **Randomize All Comments**:  
  Replaces the text of all your comments on the page with random 8-word sentences generated from a cached English wordlist.

- **Delete All Comments**:  
  Deletes all your comments visible on the current page.

- **Go to Posts**:  
  Navigates to your submitted posts page.

---

### Buttons available on the Posts page:

- **Delete All Posts**:  
  Deletes all your posts visible on the current page.

- **Go to Comments**:  
  Navigates to your comments page.

---

### On New Reddit (`reddit.com`):

- A **Go to Old Reddit** button appears in the bottom-right corner.  
- Clicking it redirects you to your old Reddit comments page for using the mass deleter features.

---

## Important Notes

- The script **only works on old Reddit** user comment and submitted pages.
- Mass actions affect all items **visible on the current page only**.
- **Rate limits are handled** automatically; if Reddit temporarily blocks actions, the script will wait before retrying.
- Deleting comments or posts **cannot be undone**. Use with caution.
- Make sure you are logged in to Reddit in the tab where you run the script.

---

## Troubleshooting

- If buttons don't show up, verify you are on the correct old Reddit URLs.
- If randomization or deletion fails, it might be due to Reddit interface changes or rate limiting.
- Check the browser console for error messages.

---
