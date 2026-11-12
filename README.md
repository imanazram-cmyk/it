# log-analyzer

Laver et hurtigt overblik over en adgangslog fra Apache eller Nginx (combined-format): antal requests, datamængde, statuskoder, de mest aktive IP-adresser, mest besøgte stier og stier der giver fejl (4xx/5xx).

## Brug

```bash
python logsum.py /var/log/nginx/access.log
python logsum.py access.log -n 10      # vis top 10 i stedet for top 5
```

Linjer, der ikke kan læses, bliver sprunget over og talt med til sidst.

## Krav

Python 3.8 eller nyere.

## Licens

MIT
