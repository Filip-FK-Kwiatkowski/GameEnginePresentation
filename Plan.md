# Silniki gier - co, gdzie, kiedy i dlaczego?

## O mnie

Kim jestem i dlaczego nikt nie powinien mnie słuchać?

- grałem dużo w gry
- nie podobało mi się w korpo
- freelancing
- praca dydaktyczna
- praca naukowa
- dużo studentów płakało i zmarnowało czas robiąc dla mnie gry, a ja ich oblewałem

## Co - czym jest silnik gier i co potrafi?

Programiści są leniwi, a napisanie kodu tak, żeby działa dobrze (i zawsze) jest bardzo trudne.

_Będziemy popełniać błędy, więc popełnijmy je szybko_

_Najlepiej się uczyć na błędach innych_

_Jak się nie ma co się lubi,_

_to się kradnie co popadnie_

## Gdzie - jaką częścią gry jest silnik?

Powtarzająca się logika, która nie jest unikalna do gry. Fizyka, kolizje, 

## Kiedy - w których momentach powstają silniki?

Teraz - często po prosty sięgamy po Unity, Unreal Engine czy Godota, bo _po prostu są_.

Kiedyś - nie używano silników. Robiono grę i gdy znajdywano powtarzającą się logikę, to ją wydzielano i dokumentowano. (pokazać refactoring na kodzie)

## Dlaczego - niektóre gry ich używają, a niektóre nie

Teraz większość gier używa silnika. Wyjątki są pojedyncze - np. gdy zasady działania gry są bardzo specyficzne (przykład, który pokazał Thor).

# GameDev - problemy i rozwiązania

## Framerate dependency

Więcej FPS = więcej update'ów logiki. To niedobrze, jeśli założymy, że framerate jest słaby. Używamy delta-time albo tickrate'u.

## Networking injection

Gra (klient) odbiera informacje, ale nie zawsze je wyświetla. Co z tego?

- Wallhack
- Oszukiwanie w pokerze
- Przykład praktyczny
