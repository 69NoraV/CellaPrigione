# CellaPrigione
Verifica arduino

Cosa fare?
- Sensori:
  + Fumo (incendio)
  + Suono
  + Movimento
- Allarmi:
  + Sirena
  + Luci Led
- Ambiente:
  + Serrande
  + Luci
  + Porta
- Comportamento:
  + 6:30:
    | Sveglia
    | Serranda
  + 6:45:
    | Porta (il prigioniero fa colazione)
  + 7:00:
    | La colazione scompare
  + 10:00:
    | Porta (Il prigioniero esce)
  + 13:00:
    | Porta (Il prigioniero rientra)
  + 14:00:
    | Porta (Il prigioniero pranza)
  
- Eventi ciclici:
  + Prigioniero cerca di scappare
    | Ogni 2 giorni
  + Incendio
    | Ogni 5 giorni
  + Lettera
    | Ogni mattina
