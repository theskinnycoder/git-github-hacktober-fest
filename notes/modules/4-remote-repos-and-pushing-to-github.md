# Module 4 : Remote Repositories & Pushing to GitHub

## A) The Theory behind Remote Repositories :

- What is **origin**?
- What is **upstream**?

## B) Creating a Remote Repository on **GitHub** :

- Create a remote repo on **GitHub**

## C) Linking the Local & Remote Repos :

- Link the remote & the local repos :

```bash
git remote add origin <remote-url>
```

- Update the Remote URL to another :

```bash
git remote set-url origin <remote-url>
```

## D) Pulling & Pushing Code :

- Pull the code from the remote repository :

```bash
git pull
```

- Now Push the code from the local repo to the remote repo (for the 1st time) :

```bash
git push -u origin main
```

- Why should we pull before we push?

## E) Cloning Repositories

- Create a remote repo before creating a local repo
- Clone that into the local machine :

```bash
git clone <remote-url> .
```
