# Projekt PaymentAPI

Witaj w repozytorium projektu PaymentAPI! Ten projekt został stworzony na podstawie kursu na platformie YouTube, obejmującego tworzenie pełnego stosu technologicznego, w którym backend został zbudowany przy użyciu ASP.NET Core API, a frontend przy użyciu Angulara. Aplikacja obsługuje operacje CRUD do zarządzania danymi dotyczącymi płatności..Ten projekt został stworzony, ucząc się z kursu na Youtube "Asp.Net Core Web API CRUD with Angular 16" Autorstwa "CodAffection". 
 
## Opis

Projekt PaymentAPI to aplikacja do dodawania, edytowania oraz usuwania informacji na temat kart bankowych. Aplikacja posiada panel zarządzania danymi napisany w Angularze.

## Technologie

- ASP.NET Core API

- Entity Framework
- C#
- Angular
- HTML/CSS
- TypeScript

## Struktura Projektu

-Controllers: Zawiera kontrolery API, takie jak PaymentDetailController.cs.
-Models: Definiuje modele danych, np. PaymentDetail.cs.
-ClientApp: Aplikacja Angulara znajduje się w katalogu Payment App.
-Views: Dodatkowe widoki, jeśli są używane.
-Services: Usługi lub narzędzia backendowe.

## Uruchamianie

1. Sklonuj repozytorium: `git clone https://github.com/KwasniakJakub/PaymentAPI.git`
2. Otwórz projekt w Visual Studio lub innym środowisku obsługującym ASP.NET Core.
3. Skonfiguruj połączenie z bazą danych w pliku `appsettings.json`.
4. Uruchom aplikację.

```bash
dotnet build
dotnet run
