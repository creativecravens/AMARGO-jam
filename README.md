# Amargo Jam

The website for Amargo Jam — small-batch bittersweet jam made by hand in Dallas, Texas.

**Contribute:** https://gofund.me/e860d35dc
**Cash App:** [$ccvd21](https://cash.app/$ccvd21) · **PayPal:** [paypal.me/ccvd21](https://www.paypal.me/ccvd21)
**Instagram:** [@amargojam](https://www.instagram.com/amargojam)

---

## Files in this repo

| File | What it is |
|---|---|
| `index.html` | The entire website. Photos are built into the file, so nothing can break. |
| `favicon.png` | The little logo that shows in the browser tab. |
| `social-preview.jpg` | The picture that appears when someone shares the link. |
| `.nojekyll` | Tells GitHub to publish the file exactly as-is. Leave it alone. |

## Putting it online (free, about 5 minutes)

1. Go to [github.com/new](https://github.com/new) and create a repository. Name it **`amargojam`**. Set it to **Public**. Don't tick any of the extra boxes.
2. On the next page, click **uploading an existing file**.
3. Drag in all five files from this folder at once, including the `.nojekyll` file. Click **Commit changes**.
4. Go to the **Settings** tab, then **Pages** in the left sidebar.
5. Under "Branch", pick **main** and **/ (root)**, then click **Save**.
6. Wait 2 minutes, then refresh. Your address appears at the top — it'll be `https://YOURUSERNAME.github.io/amargojam/`.

That link is live and shareable. Put it in your Instagram bio.

## Making an edit later

Click `index.html` in the repo, click the pencil icon, change the text, then **Commit changes**. The live site updates in about a minute.

## Where the money goes

The site sends supporters to three places. All three are live and confirmed:

- GoFundMe — `https://gofund.me/e860d35dc`
- Cash App — `https://cash.app/$ccvd21`
- PayPal — `https://www.paypal.me/ccvd21`

If any of these ever change, search `index.html` for the old address and replace every copy of it.

## Two things to do once the site is live

**1. Fix the social share image link.** Open `index.html`, find the two lines containing `content="social-preview.jpg"` and `content="social-preview.jpg"` under twitter:image, and change both to the full address, like:

```
https://YOURUSERNAME.github.io/amargojam/social-preview.jpg
```

Facebook and Instagram need the complete address to show the preview picture.

**2. Add your real jar photo.** The jam photo currently on the site is a stock picture of strawberry jam, and your jam is lemon and blackberry. A clear phone photo of your actual jars will do more for you than a stock shot. Send it to me and I'll swap it in.

## If you buy a domain later

Buy `amargojam.com` from Namecheap or Cloudflare (roughly $12/year), then add a file to this repo named `CNAME` containing one line:

```
amargojam.com
```

Then point the domain's DNS at GitHub Pages. GitHub walks you through it under Settings → Pages → Custom domain.
