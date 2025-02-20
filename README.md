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

1. Klonirajte repozitorij ili preuzmite
2. Raspakirajte ZIP
3. Navigirajte do direktorija projekta u VSCode.
4. Pokrenite igru u terminalu pomoću naredbe:

```bash
python game.py
```

## Kontrole

- **Lijeva strelica** - pomicanje ulijevo
- **Desna strelica** - pomicanje udesno
- **Razmak (SPACE)** - pucanje

## UML Dijagram

![{FA3277F7-CC44-4963-BE4E-521B5A860154}](https://github.com/user-attachments/assets/3bcb26dc-1ab8-4ba0-a961-50d6f82b199e)


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

## Autor

- **Dinko Čavrag**


