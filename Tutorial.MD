# CloudBoy

## Something flashy

it'll work out of 16bibbles of ram, cause um... marketing won?
I'm going to start with the gbdk playground and go to tonc..

if you want something finished go see
https://www.gbstudio.dev/

## Actually.. First here I want..


**ETA** I unno yet, here take this pass and tell me your wait time.

### Setting Up Accounts

will has clicks for it later?
I'm ignoring google cloud repo for.. lets say political reasons.

does want set who you is where?
he means..
might get more better later, but I don't want to 
bash my head with branching more right now
it's where I see the most ui need enough as it stands.

## Let's get Started!

First lets go find two ways to set 
global user and gloabl email in the git config
this is saved in the file ~/.gitconfig

```bash
git config --global user.name "FIRST_NAME LAST_NAME"
```

```bash
git config --global user.email "MY_NAME@example.com"
```
### Recomendation

Set this to your github handle and registered address.

### open the file and check that it's correct

```bash
cat ~/.gitconfig
```

if that looks good let's move on...

## Add SSH Key

Here get a lock on yourself and help

```bash
ssh-keygen -t ed25519 -C "your_email@example.com"
```
### Use the same thing as github so we can link that

```sh
eval "$(ssh-agent -s)"
```
### check that we got's a key man

```bash
ssh-add ~/.ssh/id_ed25519
```

### add the key for github to the cloud shell

### **Go to GitHub and add this output***

```bash
cat ~/.ssh/id_ed25519
```
[GitHub Add Key](https://github.com/settings/ssh/new)
or email it to me lol

## Next GB Info

i dunno
the same as gbdk but maybe with a port 8080 gameboy.. gots to see

## That's all there is for now folks..

<walkthrough-conclusion-trophy></walkthrough-conclusion-trophy>