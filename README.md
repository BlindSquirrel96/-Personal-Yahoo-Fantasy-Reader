# Personal Yahoo Fantasy Reader

A personal, read-only tool for reading my own Yahoo Fantasy Football teams.

## What it does

It reads my rosters, matchups, standings, available players, and transactions, and uses them to produce lineup and waiver recommendations for my own use only.

All of this work can be, and today is, done by me manually. I already read my rosters, matchups, standings, available players, and transactions myself and make my own lineup and waiver decisions. This tool simply automates my own processes, in order to save time.

## What it does not do

- No writes of any kind: it does not set lineups, submit waiver claims, make drops, or make trades.
- No commercial use.
- No redistribution of Yahoo data.
- Single user: me.

## Status

Yahoo Fantasy Sports API access is currently being applied for. The connector is not built yet. This repository currently contains this description only; code will be added once access is approved.

## How it works

When built, the tool will use the Yahoo Fantasy Sports API, read-only, with OAuth 2.0. Credentials are stored securely outside this repository and are never committed here.

Player projections come from public consensus sources, scored under my league's scoring rules.

## Privacy and security

No secrets, tokens, passwords, personal data, or league or roster data are stored in this repository.

## Use

This is a personal project, not a product or a service.
