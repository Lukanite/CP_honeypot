# CP_honeypot
Results from using dionaea and glastopf for a day.

## Which honeypots were deployed
 - [Dionaea](https://github.com/rep/dionaea)
 - [Glastopf](https://github.com/mushorg/glastopf)

## Issues encountered

Installing glastopf from the deploy script actually broke, since setuptools was too old for part of the setup to continue. Manually upgrading it via pip

```bash
sudo pip install setuptools --no-use-wheel --upgrade
```

fixed the issue.

## Summary of Collected Data
 - ~630 total attacks logged
 - ~180 request URL's logged (Glastopf)

Last 24 Hours:
<img src="https://github.com/Lukanite/CP_honeypot/raw/master/last24.png" />

## Unresolved questions
None
