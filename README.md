# git_github_test
This is test repository I want to keep text git from my PC

## Git comands used: 
git config --global user.email "you@example.com"

git config --global user.name "Your Name"

git init

> Powinen pojawić nam się nowy folder .git (folder ukryty, na widowsie nie będzie domyślnie widoczny, należy włączyć pokazywanie ukrytych plików).

> Następnie chcemy dodać nasz plik do utworzonego repozytorium:

git add index.html

> Jeśli w twoim folderze jest więcej niż jeden plik i nie chcesz dodawać ich pojedynczo po nazwie możesz użyć komendy git add . – kropka oznacza dodanie wszystkich plików w folderze.

> Następnie dodajemy nasz pierwszy commit oraz krótki komentarz co się dzieje w danym commicie – zamiany jakie dokonaliśmy. To informuje nas (oraz naszych współpracowników) czego zmiana dotyczy. W tym wypadku tylko nas, dajemy więc sobie zrozumiałą wiadomość:

git commit -m "my first repository"

> Nazwanie swojego branch main:

git branch -M main

> Teraz musimy się połączyć z naszym zdalnym repozytorium (tylko poraz pierwszy):

git remote add origin (url repozytorium)

git push -u origin main

* The instruction has been used from URL: [Git i GitHub dla zielonych: tworzymy pierwsze repozytorium] (https://www.flynerd.pl/2018/02/github-dla-zielonych-pierwsze-repozytorium.html) * 
