# MaterialPartColorSupplier

You can create a MaterialPartColorSupplier form a [MaterialPart](/Mods/ContentTweaker/Materials/Materials/MaterialPart/) object, which will then be used whenever requested.

## Импорт класса

Should you need to import he class, here you go:

```zenscript
import mods.contenttweaker.MaterialPartColorSupplier;
```

## Static methods

Static methods can be called upon the package, not upon instances of the class.

```zenscript
//mods.contenttweaker.MaterialPartColorSupplier.create(IMaterialPart materialPart);
mods.contenttweaker.MaterialPartColorSupplier.create(myMaterialPart);
```