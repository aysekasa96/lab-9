# lab-9
# Data Laden in een Dedicated SQL Pool

Deze repository bevat de instructies en SQL-scripts voor het laden van gegevens in een **Dedicated SQL Pool** binnen Azure Synapse Analytics. Dit project demonstreert hoe staging tabellen kunnen worden gebruikt om gegevens te valideren en te transformeren voordat ze worden ingeladen in dimensie- en facttabellen.

## Stappen:

1. **Voorbereiden**: Maak een Synapse Analytics workspace met toegang tot de data lake storage en Dedicated SQL Pool.
2. **Gegevens laden**:
   - Gebruik de `COPY` statement om gegevens efficiënt te laden van CSV-bestanden in de data lake.
   - Foutieve rijen worden automatisch omgeleid naar een `_rejectedrows` map.
3. **Dimensietabellen beheren**:
   - Type 1 (update bestaande rij) en Type 2 (voeg een nieuwe rij toe) Slowly Changing Dimensions worden geïmplementeerd.
4. **Optimalisatie**: Rebuild indexen en update statistieken voor betere query prestaties.

Bekijk de scripts in deze repository en probeer ze uit in jouw Azure Synapse Analytics omgeving!

## Aan de slag
- Clone deze repository: `git clone <repository-url>`
- Volg de stappen in de instructies om gegevens te laden.

Veel succes! 😊
