# 📌 Linux Cheat-Sheet: Base Command

## 🔹 Navigazione tra directory
| Comando       | Descrizione |
|--------------|------------|
| `pwd`       | Mostra il percorso della directory corrente |
| `ls`        | Elenca i file nella directory |
| `ls -l`     | Elenco dettagliato |
| `ls -a`     | Mostra anche i file nascosti |
| `cd <dir>`  | Cambia directory |
| `cd ..`     | Torna alla directory superiore |
| `cd ~`      | Torna alla home dell'utente |
| `cd -`      | Torna alla directory precedente |

## 📂 Gestione file e directory
| Comando               | Descrizione |
|----------------------|-------------|
| `touch <file>`       | Crea un file vuoto |
| `mkdir <dir>`        | Crea una directory |
| `rm <file>`          | Cancella un file |
| `rm -r <dir>`        | Cancella una directory e il suo contenuto |
| `cp <file1> <file2>` | Copia un file |
| `cp -r <dir1> <dir2>`| Copia una directory |
| `mv <sorg> <dest>`   | Sposta o rinomina un file/directory |
| `du -sh <dir>`       | Mostra lo spazio occupato da una directory |
| Comando               | Descrizione |
|----------------------|-------------|
| `touch <file>`       | Crea un file vuoto |
| `mkdir <dir>`        | Crea una directory |
| `rm <file>`          | Cancella un file |
| `rm -r <dir>`        | Cancella una directory e il suo contenuto |
| `cp <file1> <file2>` | Copia un file |
| `cp -r <dir1> <dir2>`| Copia una directory |
| `mv <sorg> <dest>`   | Sposta o rinomina un file/directory |

## 🔍 Visualizzazione e modifica file
| Comando           | Descrizione |
|------------------|-------------|
| `cat <file>`     | Mostra il contenuto di un file |
| `tac <file>`     | Mostra il contenuto al contrario |
| `less <file>`    | Permette la lettura di file grandi |
| `head <file>`    | Mostra le prime 10 righe |
| `tail <file>`    | Mostra le ultime 10 righe |
| `tail -f <file>` | Segue in tempo reale l'output del file |
| `nano <file>`    | Editor di testo nano |
| `vim <file>`     | Editor di testo vim |

## 🔎 Ricerca
| Comando                    | Descrizione |
|---------------------------|-------------|
| `find <path> -name <file>` | Cerca un file per nome |
| `grep "testo" <file>`     | Cerca una parola in un file |
| `grep -r "testo" <dir>`   | Cerca ricorsivamente in una directory |

## 🛠️ Permessi e proprietà
| Comando                    | Descrizione |
|---------------------------|-------------|
| `chmod 755 <file>`        | Cambia i permessi di un file |
| `chown user:group <file>` | Cambia il proprietario di un file |

## 📦 Gestione processi
| Comando          | Descrizione |
|-----------------|-------------|
| `ps aux`       | Mostra i processi in esecuzione |
| `kill <PID>`   | Termina un processo con il suo PID |
| `killall <nome>`| Termina tutti i processi con un dato nome |
| `top`          | Mostra i processi attivi in tempo reale |
| `htop`         | Versione avanzata di top |

## 📡 Rete
| Comando            | Descrizione |
|-------------------|-------------|
| `ping <host>`     | Controlla la connettività con un host |
| `ifconfig`        | Mostra le informazioni di rete (deprecato, usa ip addr) |
| `ip addr show`    | Mostra gli indirizzi IP |
| `netstat -tulnp`  | Mostra porte aperte e servizi in ascolto |

## 💾 Gestione pacchetti
### Debian/Ubuntu
| Comando                | Descrizione |
|-----------------------|-------------|
| `apt update`         | Aggiorna l'indice dei pacchetti |
| `apt upgrade`        | Aggiorna i pacchetti installati |
| `apt install <pkg>`  | Installa un pacchetto |
| `apt remove <pkg>`   | Rimuove un pacchetto |

### CentOS/RHEL
| Comando                | Descrizione |
|-----------------------|-------------|
| `yum install <pkg>`  | Installa un pacchetto |
| `yum remove <pkg>`   | Rimuove un pacchetto |

## 🛠️ Gestione dischi
| Comando            | Descrizione |
|-------------------|-------------|
| `df -h`         | Mostra lo spazio libero su disco in modo leggibile |
| `du -sh <dir>`  | Mostra lo spazio occupato da una directory |
| `fdisk -l`      | Mostra le informazioni sulle partizioni del disco |
| `mount <dev> <mnt>` | Monta un dispositivo su un punto di mount |
| `umount <mnt>`  | Smonta un dispositivo |

## 🏁 Uscita
| Comando    | Descrizione |
|-----------|-------------|
| `exit`   | Esce dalla sessione terminale |
| `logout` | Disconnette l'utente |
