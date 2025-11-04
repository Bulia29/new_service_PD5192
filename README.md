# Dokumentacja

## Opis usługi medycznej

Projekt pakietu medycznego dla klientów, który polega na okresowych wpłatach w celu otrzymania niemilitowanego dostępu do usług medycznych.  

**Dokumenty:**
1. opis_usługi.txt
2. plan_wdrożenia.txt
3. moje_notatki.txt
4. ryzyka.txt
5. kampania_marketingowa.txt
6. ankieta_pacjentów.txt
7. logo.png


## Jak pracować w repozytorium
 - **jak pobrać repozytorium**
   
   `git clone <URL_zdalnego_repo>`
   
 - **nawigowanie po gałęziach**
   
   `git checkout <nazwa_gałezi>` (pozwala przejść na daną gałąź)

   `git branch` (pozwala zobaczyć listę dostępnych gałęzi)
   
 - **jak przywrócić wcześniejsze wersje dokumentów**
   
   `git checkout <numer_commita>` (przechodzimy w tryb detached HEAD, w którym możemy z dawniejszego commita utworzyć nową gałąź, którą następnie można scalić z główną gałęzią)

## Wykorzystane polecenia GIT

- `git init` - utworzenie nowego reporytorium
- `touch <nazwa pliku>` - dodanie pliku
- `mkdir <nazwa folderu>` - dodanie folderu
- `nano <nazwa pliku>` - wprowadzanie zmian w pliku tekstowym poprzez nano
- `ls -a` - sprawdzenie list dostępnych plików w danym folderze (również ukrytych) 
- `git status` - sprawdzenie status plików
- `git add .` - dodanie wszystkich plików do working area
- `git commit -m "<wiadomość>"` - zcommitowanie
- `git checkout -b <nazwa gałęzi>` - dodanie i przejście na nową gałąź
- `git checkout <nazwa gałęzi>` - przejście na daną gałąź
- `git merge <nazwa gałęzi>` - scalenie gałęzi (wykonywane z poziomu gałęzi na której jestem)
- `git remote add origin <URL zdalnego repo>` - połączenie repozytorium lokalnego ze zdalnym na platformie GitHub
- `git push` - przesłanie zmian z repo lokalnego na zdalne
- `git tag` - pozwala zobaczyć wszystkie tagi
- `git tag -a <numer wersji> -m <wiadomość>`- dodanie taga wraz z wiadomością
- `git push --tags` - dodanie tagów do repo zdalnego

## Napotkane problemy

Przy scalaniu gałęzi na etapie 9. nie mogłam nadać wiadomości do commita scalajacego, ponieważ GIT wykonał operację fast forward (zmianę z brancha marketing zostały przekazane bezpośrednio na brnch master)
 

