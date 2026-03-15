# How to publish a new release (so people can download the skill zips)

You only need to do this when you have a **new version** of a skill zip to share. The first time takes about 2 minutes.

## Step 1: Open the repo’s Releases page

1. Go to **https://github.com/justinplemel-lang/docs**
2. Click **Releases** (on the right side, or under the repo name).
3. Click the green button **“Draft a new release”** (or “Create a new release” if you’ve never made one).

## Step 2: Choose or create a tag

- In the **“Choose a tag”** dropdown, type a new tag name, e.g. **`v1.0`** (for the first release) or **`v1.1`** (for an update).
- When it says **“Create new tag: v1.0 on publish”**, leave it like that. You don’t need to pick an existing branch unless you want to.

## Step 3: Fill in the release details

- **Release title:** Something like **“AI Enablement skills – March 2025”** (or whatever month).
- **Description (optional):** You can write a short note, e.g.  
  **“Slide generation skill (brand) and AI Enablement Hub helper. Download the zips below and add them in Claude → Settings → Skills.”**

## Step 4: Attach the two zip files

- Scroll to the **“Assets”** section at the bottom.
- Either **drag and drop** the two zip files into the box, or click **“Attach binaries by dropping them here or selecting them.”**
- Attach:
  1. **federato-brand-with-icons.zip**
  2. **ai-enablement-hub-helper.zip**

(Use the files from your Downloads folder or wherever you keep them.)

## Step 5: Publish

- Click the green **“Publish release”** button.
- Done. The two zips are now available at stable URLs.

## What happens next

The docs site (Mintlify) already points to these URLs. Once the release is published, anyone who clicks **“Download”** on the hub will get the zip straight from GitHub — they never have to use GitHub themselves.

**Direct links (after you publish a release with tag `v1.0`):**

- Slide generation skill:  
  `https://github.com/justinplemel-lang/docs/releases/download/v1.0/federato-brand-with-icons.zip`
- Hub helper:  
  `https://github.com/justinplemel-lang/docs/releases/download/v1.0/ai-enablement-hub-helper.zip`

If you use a different tag (e.g. `v1.1`), replace `v1.0` in the URLs with that tag. The docs can be updated to match.

## When you update a skill later

1. Go to **Releases** again.
2. Click **“Draft a new release”**.
3. Choose a **new** tag (e.g. **`v1.1`**, **`v1.2`**).
4. Attach the **updated** zip(s), add a short note, and click **“Publish release”**.
5. Tell the docs maintainer the new tag so the download links can be updated (or update the links in the repo yourself if you’re comfortable editing the hub).

That’s it.
