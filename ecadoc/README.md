# MC-OL12A31-06
Schema quadro elettrico per ascensore serie `mcpx`, Impianto oleodinamico, emergenza con valvola 12VDC, gestione movimento incontrollato secondo emndamento A3. Taglie S40-60-70.

Puoi trovare il repository dello schema su
<a href="https://github.com/eca-automs/MC-OL12A31-06" target="_blank">GitHub</a>.

### Scheda controllo
MCPX2015-SMD - PER16B-SMD
###### Firmware
[P](https://docs.ecaq.in/it/info/mcpx-board-manual-p).

### Tipo impianto
Oleodinamico.

### Manovra
Universale.

### Collegamento vano / cabina
| Vano     | Cabina     |
| :------------- | :------------- |
| parallelo | parallelo |

### Operatore porte
* manule
* automatico trifase
* automatico elettronico.

### Avviamento / controllo motore
* diretto
* soft-starter (con SMS-Start)
* stella-triangolo.

### Potenza massima motore / taglie compatibili
#### Avviamento diretto
Taglia|Potenza
---|---
S40|14CV-230VAC/22CV-400VAC

#### Avviamento stella-triangolo
Taglia|Potenza
---|---
S70|24CV-230VAC/43CV-400VAC

#### Avviamento soft-starter
Taglia|Potenza
---|---
S60|17CV-230VAC/35CV-400VAC

### Allarme
* 12VDC
* legge 13
* allarme porte aperte fuori piano

### Emergenza
Riporto al piano estremo basso con valvola 12VDC senza apertura porte.

### Emendamento A3
Gestione con doppia valvola discesa controllata con boxA3 (SMS).
