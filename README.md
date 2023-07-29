# steam-rs

[![Crate at crates.io](https://img.shields.io/crates/v/steam-rs.svg)](https://crates.io/crates/steam-rs)
[![Documentation at docs.rs](https://docs.rs/steam-rs/badge.svg)](https://docs.rs/steam-rs)
[![MIT licensed](https://img.shields.io/crates/l/steam-rs.svg)](./LICENSE)
[![CI](https://github.com/garhow/steam-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/garhow/steam-rs/actions/workflows/ci.yml)

A wrapper for the Steam Web API in Rust.

This is based on the [Steam Web API documentation](https://developer.valvesoftware.com/wiki/Steam_Web_API) that can be found at the Valve Developer Community.

This crate is highly experimental and unfinished so you are advised to be cautious when using it in your projects.

## Supported API endpoints
- [x] IPlayerService
  - [x] GetOwnedGames
  - [x] GetRecentlyPlayedGames
- [x] ISteamNews
  - [x] GetNewsForApp
- [ ] ISteamUser
  - [x] GetPlayerSummaries
  - [x] GetFriendList
  - [ ] GetPlayerAchievements
  - [ ] GetUserStatsForGame
  - [ ] GetOwnedGames
- [x] ISteamUserStats
  - [x] GetGlobalAchievementPercentagesForApp

## Contributing
This project is in early stages of development, so bug reports, suggestions, and pull requests are highly appreciated!

## License
This project is licensed under the [MIT License](./LICENSE).
