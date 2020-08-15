# MCFood

This class was added by a mod with mod-id `crafttweaker`. So you need to have this mod installed if you want to use this feature.

## Importation de la classe
It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import.
```zenscript
crafttweaker.api.food.MCFood
```

## Constructors
```zenscript
new crafttweaker.api.food.MCFood(healing as int, saturation as float);
```
| Paramètre  | Type de texte | Libellé                 |
| ---------- | ------------- | ----------------------- |
| healing    | Indice        | No description provided |
| saturation | flottant      | No description provided |



## Méthodes
### addEffect

Returns [crafttweaker.api.food.MCFood](/vanilla/api/food/MCFood)

```zenscript
myMCFood.addEffect(effect as crafttweaker.api.potion.MCPotionEffectInstance, probability as float);
```

| Paramètre   | Type de texte                                                                                 | Libellé                 |
| ----------- | --------------------------------------------------------------------------------------------- | ----------------------- |
| effect      | [crafttweaker.api.potion.MCPotionEffectInstance](/vanilla/api/potions/MCPotionEffectInstance) | No description provided |
| probability | flottant                                                                                      | No description provided |


### clearEffects

```zenscript
myMCFood.clearEffects();
```

### removeEffect

Returns [crafttweaker.api.food.MCFood](/vanilla/api/food/MCFood)

```zenscript
myMCFood.removeEffect(effect as crafttweaker.api.potion.MCPotionEffectInstance);
```

| Paramètre | Type de texte                                                                                 | Libellé                 |
| --------- | --------------------------------------------------------------------------------------------- | ----------------------- |
| effect    | [crafttweaker.api.potion.MCPotionEffectInstance](/vanilla/api/potions/MCPotionEffectInstance) | No description provided |


### setCanEatWhenFull

Returns [crafttweaker.api.food.MCFood](/vanilla/api/food/MCFood)

```zenscript
myMCFood.setCanEatWhenFull(canEatWhenFull as boolean);
```

| Paramètre      | Type de texte | Libellé                 |
| -------------- | ------------- | ----------------------- |
| canEatWhenFull | boolean       | No description provided |


### setFastEating

Returns [crafttweaker.api.food.MCFood](/vanilla/api/food/MCFood)

```zenscript
myMCFood.setFastEating(fastEating as boolean);
```

| Paramètre  | Type de texte | Libellé                 |
| ---------- | ------------- | ----------------------- |
| fastEating | boolean       | No description provided |


### setHealing

Returns [crafttweaker.api.food.MCFood](/vanilla/api/food/MCFood)

```zenscript
myMCFood.setHealing(healing as int);
```

| Paramètre | Type de texte | Libellé                 |
| --------- | ------------- | ----------------------- |
| healing   | Indice        | No description provided |


### setMeat

Returns [crafttweaker.api.food.MCFood](/vanilla/api/food/MCFood)

```zenscript
myMCFood.setMeat(meat as boolean);
```

| Paramètre | Type de texte | Libellé                 |
| --------- | ------------- | ----------------------- |
| meat      | boolean       | No description provided |


### setSaturation

Returns [crafttweaker.api.food.MCFood](/vanilla/api/food/MCFood)

```zenscript
myMCFood.setSaturation(saturation as float);
```

| Paramètre  | Type de texte | Libellé                 |
| ---------- | ------------- | ----------------------- |
| saturation | flottant      | No description provided |



## Propriétés

| Nom            | Type de texte | Has Getter | Has Setter |
| -------------- | ------------- | ---------- | ---------- |
| canEatWhenFull | boolean       | vrai       | Faux       |
| healing        | Indice        | vrai       | Faux       |
| isFastEating   | boolean       | vrai       | Faux       |
| meat           | boolean       | vrai       | Faux       |
| saturation     | flottant      | vrai       | Faux       |
