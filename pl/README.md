# Parasolowa aplikacja README

Aplikacja Parasolowa jest bezmyślną i intuicyjną aplikacją, której celem jest dostarczanie użytkownikom prognoz pogody w czasie rzeczywistym i inteligentnych sugestii pomagających im pozostać przygotowani na wszelkie warunki pogodowe. Bez względu na to, czy jest to słońcowy dzień, deszcz popołudnie, czy śnieg wieczorem, aplikacja parasolowa została Ci przykryta!

## Spis treści

- [Funkcje](#features)
- [Instalacja](#installation)
- [Użycie](#usage)
- [Użyte technologie](#technologies-used)
- [Przyczynianie się](#contributing)

## Funkcje

- **Prognozy pogodowe w czasie rzeczywistym:** Uzyskaj aktualne informacje o pogodzie dla bieżącej lokalizacji lub wybranej lokalizacji.
- **Prognoza godzinowa i dzienna:** Zobacz prognozy godzinowe i 7-dniowe, aby zaplanować swoje działania przed upływem czasu.
- **Inteligentne sugestie:** Otrzymuj zalecenia oparte na warunkach pogodowych, takie jak noszenie parasoli w dni deszczu lub noszenie filtra przeciwsłonecznego w dniu słońca.
- **Dostosowywalne alerty:** Ustaw spersonalizowane alerty dla określonych warunków pogodowych, aby nigdy nie dostać się do strażnika.
- **Interaktywne mapy:** Wizualizuj wzory pogody i śledź burze z interaktywnymi mapami.
- **Minimalistyczny projekt:** Ciesz się czystym i przyjaznym dla użytkownika interfejsem dostarczającym podstawowe informacje pogodowe na pierwszy rzut oka.

## Instalacja

1. Sklonuj repozytorium: `git clone https://github.com/yourusername/umbrella-app.git`
2. Przejdź do katalogu projektu: `cd parasola-app`
3. Zainstaluj zależności: `npm install`
4. Skonfiguruj klucze API:
   - Zmień nazwę `.env.przykład` na `.env`
   - Uzyskaj klucze API od [Weather API Provider](https://weatherapi.com) i [Map Service](https://mapsapi.com)
   - Zastąp `YOUR_WEATHER_API_KEY` i `YOUR_MAPS_API_KEY` w pliku `.env` swoimi rzeczywistymi kluczami API.
5. Uruchom aplikację: `npm start`

## Użycie

1. Otwórz Aplikację Parasolową na swoim urządzeniu.
2. Zezwalaj na dostęp do lokalizacji dla dokładnej lokalnej pogody lub ręcznie wprowadź lokalizację.
3. Poznaj bieżącą pogodę, godzinowe prognozy i tygodniową prognozę.
4. Otrzymuj inteligentne sugestie w oparciu o warunki pogodowe.
5. Skonfiguruj niestandardowe alarmy dla konkretnych scenariuszy pogody.
6. Współdziałanie z mapami w celu wizualizacji wzorów pogody i incydentów.

## Użyte technologie

- React: Biblioteka Frontend do tworzenia interfejsów użytkownika.
- Zmniejszy: Zarządzanie państwami dla aplikacji React.
- Axios: Klient HTTP oparty na ofertach do składania żądań API.
- Ulotka: biblioteka JavaScript dla interaktywnych map.
- Moduły CSS: Organizacja arkuszy stylów i kapsułki.

## Przyczynianie się

Wkłady są mile widziane! Oto jak możesz się zaangażować:

1. Forkuj repozytorium.
2. Utwórz nową gałąź dla swojej funkcji: `git checkout -b feature-new-feature`.
3. Dokonaj zmian i zatwierdzaj je: `git commit -m "Dodaj nową funkcję"`.
4. Naciśnij do gałęzi: `git push początek funkcji`.
5. Utwórz Pull Request z wyszczególnieniem zmian.
