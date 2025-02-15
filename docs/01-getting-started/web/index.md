---
title: Web
hide_title: false
hide_table_of_contents: true
sidebar_position: 3
---

In this tutorial, you will build your own app from the ground up, gaining experience with the typical development process when working with the MapsIndoors Software Development Kit (SDK). Furthermore, you should be able to gain an understanding of the basic concepts, tools and terminology commonly used when interacting with the SDK. The goal of this guide is to enable you to develop a basic app, that is able to display a map, and incorporate a few basic features such as searching, directions and Live Data integration.

Parts of this guide rely on having access to a MapsIndoors Solution which supports Live Data Integration. If you do not have access to this through your own Solution, we recommend using our demo API key to access one: `d876ff0e60bb430b8fabb145`.

> During this tutorial, you can choose between initializing the JavaScript SDK and its classes manually, or implementing the [MapsIndoors Web Components](https://www.npmjs.com/package/@mapsindoors/components) which internally handles much of SDK initializations. All steps in the tutorial will be explained for both paths.

### Take-Away Skills

* Display an interactive map with MapsIndoors
* Implementing search functionality to interact with the displayed map
* Generate and show directions between two points on the map
* Display one type of Live Data on the map
