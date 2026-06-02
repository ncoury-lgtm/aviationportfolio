# Commercial Aviation Lookup API ADS-B

A public portfolio API hosted through Cloudflare Pages Functions and GitHub.

## Purpose

This project demonstrates a serverless REST API that can look up commercial aviation information by flight number or aircraft tail number.

## Public Endpoints

```txt
GET /api/aviation/status
GET /api/aviation/search?q=AA123
GET /api/aviation/flight/:flightNumber
GET /api/aviation/tail/:tailNumber

Currently in Demo mode while being built
