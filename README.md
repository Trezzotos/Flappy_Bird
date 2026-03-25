# Flappy Bird UE
## Informazioni generali

**Titolo**: Flappy Bird UE
**Genere**: Arcade / Endless Runner
**Piattaforma**: PC
**Motore**: Unreal Engine
**Stato**: Completo

## Descrizione

Flappy Bird UE è un progetto sviluppato in Unreal Engine che implementa un gameplay loop minimale basato su input discreti e gestione fisica semplificata.
L’obiettivo è massimizzare lo score attraversando ostacoli generati proceduralmente.

Il progetto è focalizzato su performance, reattività dell’input e modularità della logica di gioco.

## Architettura

Il sistema è strutturato in componenti indipendenti:

**Player Controller**: gestione input e applicazione forza verticale
**Game Loop Manager**: controllo stato partita (start, running, game over)
**Obstacle System**: spawning procedurale e gestione lifecycle dei tubi
**Collision System**: gestione eventi di impatto e trigger di fine partita
**Score System**: incremento e persistenza del punteggio

La logica è implementata tramite Blueprint e/o C++.

## Gameplay

Il gameplay si basa su:

- Input singolo per il controllo del salto
- Gravità costante applicata al player
- Generazione dinamica degli ostacoli
- Incremento progressivo della difficoltà tramite variazione di velocità e spacing

## Aspetti Tecnici
- Spawn procedurale con parametri configurabili
- Collision detection basata su bounding volumes
- Sistema di stato centralizzato (FSM semplificata)
- Separazione logica / rendering
- Persistenza high score
- Build e utilizzo

Il progetto è apribile tramite Unreal Engine.
È possibile eseguire direttamente in editor o generare una build standalone per Windows.

## Contesto

Progetto sviluppato come dimostrazione tecnica di:
- Gestione di un gameplay loop realtime
- Progettazione modulare in Unreal Engine
- Implementazione di sistemi base riutilizzabili in contesti arcade
