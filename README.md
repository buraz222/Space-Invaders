# Space Invaders

## Opis projekta

Space Invaders je klasična arkadna igra u kojoj igrač kontrolira svemirski brod i puca na neprijateljske brodove koji se kreću prema dolje. Cilj igre je eliminirati sve neprijatelje prije nego što stignu do dna ekrana, izbjegavajući neprijateljske projektile.

## Pokretanje igre

### Zahtjevi:

- Python 3.x
- Pygame biblioteka

### Instalacija Pygame-a:

Ako Pygame nije instaliran, možete ga instalirati pomoću sljedeće naredbe:

```bash
pip install pygame
```

### Pokretanje igre:

1. Klonirajte repozitorij ili preuzmite kod.
2. U terminalu, navigirajte do direktorija projekta.
3. Pokrenite igru pomoću naredbe:

```bash
python game.py
```

## Kontrole

- **Lijeva strelica** - pomicanje ulijevo
- **Desna strelica** - pomicanje udesno
- **Razmak (SPACE)** - pucanje

## UML Dijagram

Dijagram klasa možete izraditi pomoću alata poput [draw.io](https://app.diagrams.net/). Preporučeni dijagram uključuje:

- **Player** - klasa koja predstavlja igrača
- **Enemy** - klasa za neprijatelje
- **Bullet** - klasa za metke igrača
- **EnemyBullet** - klasa za metke neprijatelja
- **Explosion** - klasa za eksplozije

&#x20;*(Dodajte stvarnu sliku UML dijagrama ovdje)*

## Struktura Projekta

```
/space_invaders
│── game.py  # Glavna skripta igre
│── README.md  # Dokumentacija projekta
│── player.png  # Slika igrača
│── enemy.png  # Slika neprijatelja
│── explosion1.png - explosion5.png  # Animacije eksplozije
```

## Autori

- **Dinko Čavrag**


