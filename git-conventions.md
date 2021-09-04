# git-conventions

## First Commit conventions

- Make sure that repository is sync with git

> ```shell
> cd repository-name
> git init
> ```

- Make sure that there is a readme documentation about the repository

> ```shell
> echo "# repository-name" >> readme.md
> ```

- Stage your change and commit it

> ```shell
> git add readme.md
> git commit -m "🚀️ First Commit"
> ```

## General Commit Conventions

```txt
<emoji> <type> <scope*> : <short_description>

<description_about_the_commit>

☢️ <extra-note_about_the_commit>

<issue id, tags, etc.>
```

## Emoji-Log's philosophy

Use :

- use `repository-name`

Here's the philosophy that guides writing commit messages with Emoji-Log:

### Imperative

Make your Git commit messages imperative.
Write commit message like you're giving an order.  
e.g: Use ✅ Add instead of ❌ Added  
e.g: Use ✅ Create instead of ❌ Creating  

### Rules

A small number of categories are easy to memorize.  
**Nothing more, nothing less** : 📦 NEW, 👌 IMPROVE, 🐛 FIX, 📖 DOC, 🚀 RELEASE, and ✅ TEST

### Actions

Make Git commits based on actions you take.
Use a good editor like VSCode to commit the right files with commit messages.

## Writing commit messages

Use only the following Git commit messages. The simple and small footprint is the key to Emoji-Logo.

- Use when you add something entirely new.  
  - 📦 NEW: Add Git ignore file  
- Use when you improve/enhance piece of code like refactoring etc.  
  - 👌 IMPROVE: Remote IP API Function
- Use when you fix a bug. Need I say more?
  - 🐛 FIX: Case converter
- Use when you add documentation, like `README.md` or even inline docs.
  - 📖 DOC: API Interface Tutorial
- Use when you release a new version.
  - 🚀 RELEASE: Version 2.0.0
- Use when you release a new version.
  - ✅ TEST: Mock User Login/Logout

That's it for now. Nothing more, nothing less.
