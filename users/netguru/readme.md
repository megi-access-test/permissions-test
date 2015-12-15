### sample member.yml
_Sidenote_: `users/` dir is to be renamed to `members/` as soon as Access App can handle it.
We decided to use `members/` to stay consistent across all the repo contents.  
  
Keys and values must be ordered a-z.
```
---
emails:                  # required
- user.email@netguru.co
- user.email@netguru.pl
external: false          # required
github: ghmention        # required
name: Member Name        # required
public_key: ssh-rsa ...  # required
```
