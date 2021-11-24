# CloudBoy

## Something flashy

it'll work out of 16Kibbles of ram, cause um... marketing won?
I'm going to start with the gbdk playground and go to tonc..

if you want something finished go see
[The Amazing Work on GB Studio](https://www.gbstudio.dev/)

### you could also...
you clearly have google. make sure you have a github
and turn on two factor on both while you're at it.
//TODO "here's your tokens tap em on stuff to the links you get.

## Let's get Started!

**ETA** I unno yet, here take this pass and tell me your wait time.

### Setting Up Accounts
oh no I'm terrible

### while your at it click more and disable usage statistics for shell

```sh
gcloud config set disable_usage_reporting true
```

cough cough 

**ctrl-alt-T**

**RLZ Disable**

does check that rlz status says disabled lol

## Ya got any of them names?

First lets go find two ways to set 
global user and global email in the git config
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

NO! when we make branches cool add auto naming. 
might need my own git repo thing for that..

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

## Add GPG Key

```sh
gpg --full-generate-key
```
### Generate the key

it'll ask you to pick a key type
the default, or **RSA**

bits is **4096**
make a fun passphrase for it too
and I'd just use the same username
and email, maybe comment github?

I think this will be mute if I just use the track from github? 
or is it like a token ring of how stupid this recursion is?



```sh
gpg --armor --export "SPECIAL CODE"
```

then add it to [GitHub](https://github.com/settings/gpg/new) of course..

**HINT** the "SPECIAL CODE" will return

```terminal
-----BEGIN PGP PUBLIC KEY BLOCK-----
    ~~~~~~secret sauce~~~
-----END PGP PUBLIC KEY BLOCK-----
```

### With that added let's continue..

## GIT BASIC

### 

## BashRC?

don't know her.. how about
```sh
touch ~/.bash_aliases
```
### create a folder of ..

<walkthrough-editor-open-file filePath=".bash_aliases">**aliasi says me**</walkthrough-editor-open-file>


### **Recommend** you add 

```
alias tst="echo tested"
```

```sh
source ~/.bashrc
```

### and reload so it speaks your new lisps
```sh
tst
```

## Next GB Info

i dunno
the same as gbdk but maybe with a port 8080 gameboy.. gots to see

## That's all there is for now folks..

<walkthrough-conclusion-trophy></walkthrough-conclusion-trophy>