---
title: Game Systems
description: Lonnies Fishtank GDD Game Systems
pubDate: 2025-01-08
---

## 4.1. Fish Affection Levels

When fish are cared for through eating quality food, spending time playing with the player, or going on walks, their affection increases. Affection increases in different ways based on the quality of interaction with the player. For example if the fish has a great walk with the player, their will gain a lot of affection points. Alternatively, if the fish has a bad walk with the player, they will barely gain any affection points. This can also be seen in the quality of the play experience with the fish. If the player and the fish have a good, high quality play session, they will gain many affection points, while if the play session is short, low quality, or hurts the fish, they will gain much fewer points.

Different fish have affection tiers with various sizes. When a fish gains enough affection points to reach the next tier, this is communicated to the player, and the player is rewarded with tokens. The number of tokens rewarded corresponds to the size of the affection tier. A large affection tier will reward the player with 3 tokens when it is filled, while a smaller affection tier may only reward the player with a single coin.

The concept is that players should be rewarded with fish that are more challenging to increase their affection points with; However, the intent is also to vary the affection tiers so that one fish isn't seen as the difficult fish.

- Goes up when fed or played with
- Slowly goes down over time?
	- Maybe a certain amount of time must pass before fish affection starts to decrease 
- Goes down when neglected
- Some fish have different affection curves
	- Basic fish: logarithmic
		- Not much time required
	- Medium fish: linear
		- Time proportional 
	- Hard: exponential
		- More time required, faster regression

### 4.1. caring for and playing with the fish
- Higher quality toys / interaction = more affection?
- Higher skilled / perfect training / interaction = more affection?
- Basic: just doing the thing leads to more affection
## 4.3. Gachapon Machine

The gachapon machine is a mechanic that allows the player to have the chance at getting more rare / unique fish. Each usage of the gachapon takes one currency (token? doubloon?). The following is a breakdown of the likelihood for obtaining fish with rare features from the gachapon


| Fish Type                      | Chance |
| ------------------------------ | ------ |
| Common Fish (No Rare Features) | 50%    |
| Fish with 1 rare feature       | 20%    |
| Fish with 2 rare features      | 15%    |
| Fish with 3 rare features      | 10%    |
| Fish with fully rare features  | 5%     |

Each successive use of the gachapon will increase the player's chances of getting a fish with rare features by 1% each time they attempt to use the machine. After obtaining a fish with any rare features, the probabilities reset back to normal. Alternatively, players can also increase their chances at getting a fish with rare features by inserting more money (tokens) into the machine. This will increase each of the probabilities for rare features by 1% for each coin inserted, and similar to the initial case, these probabilities will carry over in future uses of the gachapon machine.

## 4.4. Store

Generally there are three types of items available for purchase in the store: 
- Food to feed the fish. Higher quality food yields happier fish, which in turn produce more money.
- Tank decor that can be used to customize the appearance of the tank.
- Fish decor that can be used to customize certain aspects of the fish?

The cheapest items generally cost 1 token, while each increase in value is indicated by a higher token cost.

Fish can also be sold to the shop to get one token, and an additional token per rare feature that is shown on the fish. A fish with 2 rare features will provide 3 tokens when sold.

## 4.5. walking the fish
- Types of random encounters: 5
	- Items that can be received:
		- Money 
		- Fish
		- Negative or positive fish affection
- Places that can be discovered: 3
	- Fountain
	- Beach 
	- Aquarium
## 4.7. customizing fish
- Fin variations: 5
- Color variations: 10
	- Red, blue, green, yellow, pink
	- orange, purple, black, white
- Body Variations: 5
- Hat variations: 5
- Clothing variations: 5
- Shader variations: 5
	- Shiny
	- 
- Particle trail variations: 5
	- Bubbles
	- Sparkles
## 4.8. Customizing Fish Tank

The fish tank has one main area of customization: the decor that sits within the tank. As players progress throughout the game, they will earn money from caring for their fish and taking them on walks. This money can be spent on purchasing items from the store, or using the gachapon machine. One category of items that can be purchased from the store is fish tank decor.

Fish tank decor comes in two different types:
- decor that sits on the bottom of the tank and is more structural (large rocks, castles, mock buildings)
- decor that sits on the faces / walls of the tank and is more aesthetic based / visual (posters, coral patterns, various fish tank wall papers)

When the player would like to place decor, they can click on a button to activate this from the inventory screen. This then transitions the player to a fish tank customization scene.

The fish tank customization scene has two modes: the first mode allows them to place decor on the floor of the tank, while the second allows them to place decor on the tank walls.

When decor is selected to be placed, it is shown over top of a grid-like system. The grid system dictates which cell blocks within the tank already have some decor occupying them, and also indicates which cell blocks are free and can be used for placement. If a placement spot is invalid, the decor attempting to be placed will be highlighted red and won't permit the player to place it.

This is a similar case when placing wall decor: the decor cannot be placed if it is overlapping with existing decor that is already placed.

### Sample Decor / Themes
- Plants
- Rocks
- Beach decor
- Sunken / ancient city
- Lights?
## 4.9. customizing room

While playing the game, the player also has the opportunity to spend the money that they acquire from taking care of the fish to purchase a new house / property. This allows the room / scenery / environment in which the game / fish tank currently take place to change drastically. Rooms are generally a more expensive item to purchase than most things in the store and gachapon.


- Room variations: 3-5
	- Come with new music and aesthetic 