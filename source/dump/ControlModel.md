# ControlModel

**Namespace:** ` `


## Fields

- `Int32 startLevel`

- `Int32 startExp`

- `Int32 maxLevel`


## Methods

- `LevelModel GetLevelModel(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ControlModel : IHotfixable
{
	public Int32 startLevel; // 0x10
	public Int32 startExp; // 0x14
	public Int32 maxLevel; // 0x18
	public Dictionary`2 levelMap; // 0x20
	private static DelegateBridge __Hotfix0_GetLevelModel; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x22475b8 VA: 0x759485f5b8
	public LevelModel GetLevelModel(Int32 level) { }
	// RVA: 0x2246eb4 VA: 0x759485eeb4
	public Void .ctor() { }
}
```