# aeroportos-br
Um banco de dados em JSON de 300 aeroportos, aeroclubes e bases aéreas nacionais com códigos ICAO e IATA, nome, cidade, altitude em metros, latitude, longitude e um identificador de fuso horário. O código IATA é usado como chave primária de cada aeroporto.

```json
"CWB": {
        "icao": "SBCT",
        "iata": "CWB",
        "name": "Aeroporto Internacional Afonso Pena",
        "city": "Curitiba",
        "state": "Paraná",
        "elevation": 910.74,
        "lat": -25.5284996033,
        "lon": -49.1758003235,
        "tz": "America/Sao_Paulo",
        "uf": "PR"
    }
```

Dados retirados do repositório [mwgg/Airports](https://github.com/mwgg/Airports)