# ha-tpower-card

Home Assistant Simple Power Card

A Home Assistant lovelace card to display bar chart  oriented to display power sensors

![Sun Card 2](https://img.shields.io/github/v/release/trollix/ha-tpower-card)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg?style=flat)](https://github.com/custom-components/hacs)

## Options

| Name              | Type    | Requirement  | Default             | Description                                 |
| ----------------- | ------- | ------------ | ------------------- | ------------------------------------------- |
| type              | string  | **Required** |                     | `custom:tdv-bar-card`
| title             | string  | **Optional** |                     | Optional header title for the card
| height            | number  | **Optional** |                     | The height of the card in pixels
| rangemax          | number  | **Optional** | 2000                | Maximum bar scale range
| scaletype         | string  | **Optional** | log10               | Scale type (linear or log10 )
| entities          | object  | **Required** |                     | Displayed entities. See [Entities](#Entities)

### Entities

| Name              | Type    | Requirement  | Default              | Description                                 |
| ----------------- | ------- | ------------ | -------------------- | ------------------------------------------- |
| entity            | string  | **Required** |                      | Entity id of the sensor
| icon              | string  | **Optional** |                      | Icon for this entity
| name              | string  | **Optional** |                      | Custom label for this entity
| state             | string  | **Optional** |                      | Change state entity id (e.g. switch)
| barcolor          | string  | **Optional** | Prymary system color | Individual bar color

[![releases-shield](https://img.shields.io/github/release-date/trollix/ha-tpower-card)](https://img.shields.io/github/release-date/trollix/ha-tpower-card)
[![License-schield](https://img.shields.io/github/license/trollix/ha-tpower-card)](https://img.shields.io/github/license/trollix/ha-tpower-card)