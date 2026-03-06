# remote-gaming-v1

Legacy codebase for the original **Remote Gaming** prototype.

This repository contains the first implementation of a multiplayer tabletop game engine built with **Ruby on Rails and Vue.js**. It supported games such as **Modern Art** and **Pandemic**, with game logic implemented primarily in Ruby service objects.

The project was developed around 2020–2021 using:

* Ruby on Rails (Rails 6 era)
* Webpacker
* Vue 2 + Vuex
* ActionCable for realtime updates
* PostgreSQL

The architecture separates **game logic (Ruby services)** from the **UI (Vue)**, allowing different games to plug into the same core framework.

## Status

This repository is **archived and read-only**.

Development has moved to the new implementation:

**https://github.com/harvj/remote-gaming**

The new version is being rebuilt with:

* **Rails 8**
* **Svelte**
* a simplified frontend architecture
* improved modular game support

## Purpose

This repo remains available for:

* historical reference
* gameplay logic examples
* migration reference for the new engine

It is not intended for active development.
