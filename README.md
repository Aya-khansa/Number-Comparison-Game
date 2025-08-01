# Number Comparison Game – .NET Core 8 Web App

A .NET Core 8 web application where a player competes against a bot in a number comparison game. The game uses Razor Pages, a minimal API, and Entity Framework Core with an InMemory database.

## Features

- Form input validation (A < B, values between 1–10, B is a multiple of 2)
- Random number generation for the bot
- Game logic: player wins if A + B > X + Y
- Result page showing current outcome and full game history
- Real-time score tracking for Player and Bot
- Razor Pages for user interface
- Minimal API with validation and JSON result
- Server-side validation and feedback summary
- Clean architecture (ViewModel, BindingModel, DataModel)
- Service layer for business logic and data persistence

## Technologies Used

- .NET Core 8
- Razor Pages
- Minimal APIs
- Entity Framework Core (InMemory provider)
- C#
- HTML/CSS

## Minimal API Endpoint
A minimal API endpoint is included to process game logic programmatically.
