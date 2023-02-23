# CellaPrigione
Verifica arduino

Cosa fare?
- Allarmi:
  + Sirena
  + Luce Led
- Ambiente:
  + Spruzzino
  + Serranda
  + Luce
  + Porta
- Comportamento:
  + 6:30:
    | Serranda
  + 6:45:
    | Porta (Apre)
  + 7:00:
    |  Porta (Chiude)
  + 10:00:
    | Porta (Apre)
    | Luce (Accende)
  + 10:30:
    | Porta (Chiude)
    | Serranda (Chiude)
  + 13:00:
    | Luce (Spegne)

  
- Eventi ciclici:
  + Prigioniero cerca di scappare
    | Ogni 2 giorni
    | 6:00:
      - Allarme (Accende)
      - Led (Accende)
    | 6:30:
      - Allarme (Spegne)
      - Led (Spegne)
    
  + Incendio
    | Ogni 5 giorni
    | 12:30:
      - Spruzzino (Accende)
      - Allarme (Accende)
    | 13:00:
      - Spruzzino (Spegne)
      - Allarme (Spegne)

