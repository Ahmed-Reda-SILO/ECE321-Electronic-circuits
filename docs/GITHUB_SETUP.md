# Upload the course repository to GitHub

Suggested repository name: **ECE321-Electronic-Circuits**

Suggested description:

> ECE321 Electronic Circuits course materials: lecture slides and handwritten notes on frequency response, op-amps, feedback, current mirrors, and differential amplifiers.

## Upload through the GitHub website

1. Extract the repository ZIP on your computer.
2. On GitHub, create a repository named `ECE321-Electronic-Circuits` and choose its visibility.
3. Leave automatic README, license, and gitignore creation unselected; this package already includes a README and gitignore.
4. Use **uploading an existing file** or **Add file → Upload files**.
5. Upload the contents of the extracted `ECE321-Electronic-Circuits` folder, including its subfolders, so `README.md` is at the repository root.
6. Commit the upload with a message such as `Add ECE321 lecture slides and handwritten notes`.

## Upload with Git

Alternatively, open a terminal inside the extracted `ECE321-Electronic-Circuits` folder and run:

```bash
git init -b main
git add .
git commit -m "Add ECE321 lecture slides and handwritten notes"
git remote add origin YOUR_REPOSITORY_URL
git push -u origin main
```

Replace `YOUR_REPOSITORY_URL` with the URL of the empty repository you created. If Git prompts for an author name or email, configure your own Git identity before committing.

The downloadable package contains the course files without local Git history. No remote repository has been created or published by packaging these files.
