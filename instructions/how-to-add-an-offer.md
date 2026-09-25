# How to Add a New Offer

1. Open [`Database/database.md`](../Database/database.md).
2. Find the correct section (UAE Resident & Student Discounts / Global Student & Developer Freebies / Shopping, Coupons & Cashback). If none fit, propose a new section in your PR description.
3. Add a new row at the **end** of that section's table using this exact format:

```
| [OFFER NAME](https://link-to-offer) | One-line benefit description | Category |
```

Example:

```
| [Spotify Student Plan](https://www.spotify.com/ae-en/student/) | Discounted Premium for verified students | Music |
```

4. Save the file, commit, and open a Pull Request.
5. In the PR description, confirm: the link works, the offer is currently live, and you checked it isn't already listed.

That's it — no code, no build step. It's a Markdown table.
