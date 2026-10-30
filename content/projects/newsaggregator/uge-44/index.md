---
title: "Uge 44: Ai, summaries og JWT"
date: 2026-10-18
description: "AI, summaries og JWT"
series: ["NewsAggregator"]
series_order: 10
draft: false
---

## Hvad lavede jeg
- Jeg har fået alt AI op at køre, vi kan nu sende batches af artikler afsted og få JSON tilbage med en opsumering af artiklen såvel som en bedømmelse af artiklerne opdelt efter deres id, med fejlhåndtering.
- Jeg kan også få AI'en til at tage alle artikler inden for en periode og emne og give bullet point tekst tilbage som opsummere den mængde artikler der blev givet i bullet points.
- Jeg har også tilføjet 2 andre scheduler klasser som håndtere at køre de her AI kald løbene.
- Til alt det har vi fået en del DAO metoder og 2 ekstra DAO klasser, til at hjælpe med at søge i databasen.
- Jeg har lavet 3 controllers og opdateret den 4, til at kunne håndtere alt det nye som er blevet tilføjet. skal jo kunne bruge det i min javalinServer routes så man kan tilgå mine REST api endpoint /api/....
- har tilføjet en hel del DTO'er til at håndtere hvordan og hvor data må komme hen.

- Jeg har også fået opsat JWT og bruger
- Jeg giver nogle tokens når en bruger logger ind og de tokens beholder man et hvis antal tid efter man forlader hjemmesiden.


## Udfordringer
- Jeg havde meget svært ved at tilføje JWT, da jeg ikke var der ugen vi blev undervist i det, havde gevaldigt undervurderet hvor svært det var.

## Næste uge
- Eksamen