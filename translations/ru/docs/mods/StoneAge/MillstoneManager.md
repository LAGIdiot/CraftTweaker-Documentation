# Millstone

## Пакет
`import mods.stone_age.MillstoneManager;`

## Методы
- **String name** Recipe name
- **[IItemStack](/Vanilla/Items/IItemStack/) output**
- **[Ingredient](/Vanilla/Variable_Types/IIngredient/) ввод**
- **int activateCount** Activate millstone count
- **String group** Recipe group

## Сложение

```zenscript
<recipetype:stone_age:millstone>.addRecipe(String name, IItemStack output, IIngredient input, int activateCount, @OptionalString String group)

<recipetype:stone_age:millstone>.addRecipe("sugar", <item:minecraft:sugar>, <item:minecraft:sugar_cane>, 2, "foods");
MillstoneManager.INSTANCE.addRecipe("sugar", <item:minecraft:sugar>, <item:minecraft:sugar_cane>, 2, "foods");
```