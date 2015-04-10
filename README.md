Site web de Vincent Fribault
============================

Récupération des sources :

```sh
git clone git@github.com:vincent-fribault/website.git vincent-fribault
cd vincent-fribault
```

Installation des dépendances :

```sh
bundle install
```

Faire ses ajouts ou modifications puis tester en lancant le serveur :

```sh
bundle exec middleman
```

Faire un commit (git ou github app) :

```sh
git commit -am "Ce que j'ai fait"
```

Pousser les sources sur la branche master

```sh
git push
```

et déployer :

```sh
bundle exec rake publish ALLOW_DIRTY=true
```
