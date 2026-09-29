# Community Jokes

A collection of jokes and memes submitted by the Interledger community. Got something to share? Follow the steps below to add it.

## How to contribute a joke

### Option A: In your browser (no installs)

1. Open the [`jokes/`](jokes/) folder and check the highest file number.
2. Click **Add file → Create new file**.
3. Name the file with the next number, for example `021.json`, and add your joke. Follow the format and rules in step 3 of Option B below.
4. Click **Commit changes**, choose **Create a new branch**, and name it something like `add-my-joke`.
5. Click **Propose changes**, then **Create pull request**. Give your PR a short title like `Add joke 021`.

### Option B: With git on your computer

#### 1. Clone the repository

```bash
git clone git@github.com:interledger/community-jokes.git
cd community-jokes
```

#### 2. Create a branch

```bash
git checkout -b add-my-joke
```

#### 3. Add your joke file

Jokes live in the `jokes/` directory. Each joke is its own JSON file named with a zero-padded three-digit number — check what the highest number currently is and add the next one.

For example, if `020.json` is the last file, create `021.json`:

```json
{
  "id": "021",
  "setup": "Why don't scientists trust atoms?",
  "punchline": "Because they make up everything."
}
```

**Formatting rules:**

- The filename and `id` value must match (e.g. file `021.json` → `"id": "021"`).
- `setup` is the question or premise of the joke.
- `punchline` is the answer or payoff.
- Both `setup` and `punchline` must be non-empty strings.
- Keep it family-friendly and kind — no jokes that punch down or target specific people or groups.

#### 4. Commit and push

```bash
git add jokes/021.json
git commit -m "add joke 021"
git push origin add-my-joke
```

#### 5. Open a pull request

1. Go to the repo on GitHub ([github.com/interledger/community-jokes](https://github.com/interledger/community-jokes)).
2. Click the **Compare & pull request** button that appears after your push.
3. Make sure the base branch is `main`.
4. Give your PR a short title like `Add joke 021`.
5. Click **Create pull request**.

A maintainer will review and merge it. That's it — thanks for contributing!

## How to contribute a meme

### Option A: In your browser (no installs)

1. Open the [`public/memes/`](public/memes/) folder and check the highest file number.
2. Name your image with the next number, for example `056.png`. Follow the rules in step 2 of Option B below.
3. Click **Add file → Upload files** and drag in your image.
4. Choose **Create a new branch**, name it something like `add-my-meme`, and click **Propose changes**.
5. Click **Create pull request**. Give your PR a short title like `Add meme 056`.

### Option B: With git on your computer

#### 1. Clone the repository and create a branch

Same first two steps as above. Clone the repo and create a branch:

```bash
git clone git@github.com:interledger/community-jokes.git
cd community-jokes
git checkout -b add-my-meme
```

#### 2. Add your image file

Memes live in the `public/memes/` directory. Name your file with a zero-padded three-digit number and a lowercase extension — check what the highest number currently is and use the next one.

For example, if `055.png` is the last file, add `056.png` (or `056.jpg`, etc.):

```
public/memes/056.png
```

**Formatting rules:**

- Supported formats: `.jpg`, `.jpeg`, `.png`, `.gif`, `.webp`.
- Use a lowercase extension (`.jpg` not `.JPG`).
- File name must be a zero-padded three-digit number, e.g. `056.png`.
- Keep it family-friendly and kind — no images that punch down or target specific people or groups.

#### 3. Commit and push

```bash
git add public/memes/056.png
git commit -m "add meme 056"
git push origin add-my-meme
```

#### 4. Open a pull request

1. Go to the repo on GitHub ([github.com/interledger/community-jokes](https://github.com/interledger/community-jokes)).
2. Click the **Compare & pull request** button that appears after your push.
3. Make sure the base branch is `main`.
4. Give your PR a short title like `Add meme 056`.
5. Click **Create pull request**.

A maintainer will review and merge it. Thanks for sharing the laughs!
