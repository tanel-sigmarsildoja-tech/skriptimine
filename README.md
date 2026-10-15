# Rakendusserverite halduse autoriseerimine
## git
### paigaldamine
git paigaldamiseks tuleb teostada järgmised käsud (debian 13)
---
apt install git      #NB ole root
---
### seadistamine
git seadistamiseks on vaja konfigureerida kasutaja nimi ja email, samuti seostada ka redaktor:
---
git config --global user.name "Ees Perenimi"
git config --global user.email email@domeen.com
git config --global core.editor nano
---
