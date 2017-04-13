# Zadanie domowe Git - Instrukcja obsługi
Polega na grupowym opracowaniu krótkiego opisu kluczowych komend Gita.


Wymagania:
 * opracowanie ma mieć formę jednoplikowej strony HTML
 * wszystkie komendy z poniższej listy muszą zostać opisane (co robią i do czego mogą być przydatne + przykład użycia)
 * całość powinna być poprawna pod kątem językowym
 
Sposób pracy:
 * Każdy student tworzy własną kopię repozytorium (fork)
 * Dokonuje tam zmian (najlepiej w modelu branch per feature)
 * Następnie wysyła zgłoszenie Pull Request do oryginalnego repozytorium
 
Zadanie zaliczą te osoby, które łącznie:
 * dokonają istotnego wkładu merytorycznego w opracowanie (dodanie opisu komendy, modyfikacja istniejącego pisu, code review)
 * stworzą własne repozytorium (fork)
 * prześlą Pull Request do oryginalnego repozytorium
 * ich Pull Request zostanie włączony do głównego branch (master)
 
 
 Lista komend do opisania:
 
  * Grupa CC
    * git config --global user.name ""
    * git add .
    * git reset HEAD
    * git checkout "branch"
    * gitk -all
    * git branch --merged
    * git branch "branch" "commit hash"
    * git pull "remote" "branch"
    
  * Grupa CE
    * git config --global user.email ""
    * git commit -a -m ""
    * git diff --staged
    * git checkout -b "branch"
    * git log --graph --all
    * git branch -d "branch"
    * git remote add "remote_name" "git url"
    * git fetch "remote" "branch"
  
  * Grupa CF
    * git config --global color.ui true
    * git commit "filename"
    * git branch "name"
    * git branch -v
    * git push "remote" "branch"
    * git log "branch" --not "branch"
    * git blame -C "filename"
    * git bisect (start, bad, good, reset)
