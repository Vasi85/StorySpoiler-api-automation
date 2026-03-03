# StorySpoiler — Back-End API Automation

This repository contains automated API tests for the StorySpoiler system.

The project demonstrates REST API testing using RestSharp and NUnit within a .NET test framework.

## Covered Functionalities

- User login & token handling
- Create entity
- Edit entity
- Retrieve all entities
- Delete entity
- Negative scenarios (invalid input / non-existing ID)

## Tech Stack

- C#
- .NET
- NUnit
- RestSharp
- GitHub Actions

## Key Implementation Details

- RestClient with Base URL configuration
- JWT authentication via Authenticator
- DTO models for clean request/response mapping
- Test ordering using [Order()]
- Reusable test setup

## CI Workflow

On every push to main:

- Checkout repository
- Install .NET SDK
- Restore packages
- Build solution
- Execute tests

## Running the Tests

1. Clone repository
2. Open in Visual Studio
3. Restore packages
4. Run all tests
