# NfoSync AI Instructions

## Projekt

NfoSync je framework pro správu lokálních NFO metadat.

## Architektura

- NFO je jediný zdroj pravdy.
- Repository vlastní XML.
- Business logika nikdy nesmí manipulovat XML.
- Providery vrací pouze doménové modely.
- Sync Engine vytváří patch mezi NFO a providerem.

## Kód

- Python 3.13+
- dataclasses
- type hints
- Ruff
- MyPy
- PyTest

## XML

- Nikdy negeneruj nové NFO.
- Zachovej všechny neznámé XML elementy.
- Přepisuj pouze změněné uzly.

## Vývoj

- Nejprve analyzuj.
- Poté navrhni řešení.
- Teprve nakonec napiš kód.