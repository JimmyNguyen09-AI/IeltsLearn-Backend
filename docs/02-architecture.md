# Architecture

## Style

Modular Monolith

## Structure

Controller → Service → Database

## Layers

- Common → shared code
- Domain → entities
- Features → business logic
- Infrastructure → DB, JWT, services

## Rule

- Controller = thin
- Logic = Service
- DB = Infrastructure