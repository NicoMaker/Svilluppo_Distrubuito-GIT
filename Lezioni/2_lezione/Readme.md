[Vai al file principale](../../README.md)

# Lezione 2 21 Marzo 2025

## Branching e Merging

Git offre la possibilità di lavorare su funzionalità separate, creando **rami** e **merging** le funzionalità nel codice principale.

---

## Comandi PULL e PUSH

```bash
git pull <repository_url> <branch_name> # scarica le modifiche da un repository remoto
git push <repository_url> <branch_name> # invia le modifiche al repository remoto
```

## Clone

```bash
git clone <repository_url> # clona un repository remoto
```

## Merge repository da un branch ad un altro

```bash
git merge <branch_name> # unisce un ramo con il ramo attuale
```

## Sposto di branch (change branch) Chechout

```bash
git checkout <branch_name> # cambia la branch attuale
git checkout -b <branch_name> # crea una nuova branch e cambia la branch attuale
git checkout - # torna alla branch precedente
```

## Log

```bash
git log # visualizza le modifiche nella directory corrente
git log --oneline # visualizza le modifiche nella directory corrente in una riga
git log --all # visualizza tutte le modifiche nella directory corrente
git log --oneline --all # visualizza tutte le modifiche nella directory corrente in una riga
```

# Progetti

- [1 Progetto](Progetti/1_Progetto)
