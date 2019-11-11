# Git
[Podstawowe komendy Git (en)](https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html)

## Podstawowe zmiany
* `git status` - pokaż status repozytorium 
* `git add <plik>` - dodaj pliki do gałęzi
* `git add *` - dodaj wszystkie pliki do gałęzi
* `git commit -m "Komentarz"` - wprowadź zmiany do gałęzi
* `git commit -a` - wprowadź wszystkie pliki oraz zmiany do gałęzi
* `git push origin master` - wyślij gałąź ze zmianami do gałęzi *master* zdalnego repozytorium
* `git pull` - odbierz zmiany na zdalnym repozytorium do swojego lokalnego repozytorium
* `git clone /ścieżka/do/repo` - wykonaj kopię danego repozytorium
* `git clone username@host:/ścieżka/do/repo` - wykonaj kopię danego zdalnego repozytorium

## Gałęzie
* `git branch` - wyświetl wszystkie gałęzie i zaznacz tą, w której operujesz
* `git checkout <nazwa>` - przejdź do gałęzi
* `git checkout -b <nazwa>` - utwórz gałąź i przejdź do niej
* `git branch -d <nazwa>` - usuń gałąź
* `git push origin <nazwa>` - wyślij gałąź do zdalnego repozytorium
* `git push -all origin` - wyślij wszystkie gałęzie do zdalnego repozytorium

## Lokalne repozytorium
* `git init` - nowe lokalne repozytorium

## Konfiguracja Git
* `git config --global user.name "nazwa użytkownika"` - dodaj swoją nazwę użytkownika
* `git config --global user.email email@example.com` - dodaj swój adres e-mail
