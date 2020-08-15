# Millstone

## パッケージ
`import mods.stone_age.MillstoneManager;`

## メソッド
- **String name** Recipe name
- **[IItemStack](/Vanilla/Items/IItemStack/) output**
- **[IIngredient](/Vanilla/Variable_Types/IIngredient/) の入力**
- **int activateCount** Activate millstone count
- **String group** Recipe group

## 加算

```zenscript
<recipetype:stone_age:millstone>.addRecipe(String name, IItemStack output, IIngredient input, int activateCount, @OptionalString String group)

<recipetype:stone_age:millstone>.addRecipe("sugar", <item:minecraft:sugar>, <item:minecraft:sugar_cane>, 2, "foods");
MillstoneManager.INSTANCE.addRecipe("sugar", <item:minecraft:sugar>, <item:minecraft:sugar_cane>, 2, "foods");
```