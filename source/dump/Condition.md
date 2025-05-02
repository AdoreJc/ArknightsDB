# Condition

**Namespace:** ` `


## Fields

- `Int32 minProgress`

- `Int32 maxProgress`

- `Int32 minPlayerLevel`


## Methods

- `Boolean Check(PlayerDataModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Condition
{
	public Int32 minProgress; // 0x10
	public Int32 maxProgress; // 0x14
	public Int32 minPlayerLevel; // 0x18
	public String[] requiredFlags; // 0x20
	public String[] excludedFlags; // 0x28
	public StageCondition[] requiredStages; // 0x30
	private static DelegateBridge __Hotfix0_Check; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x34f7a5c VA: 0x7595b0fa5c
	public Boolean Check(PlayerDataModel model, Boolean ignoreStageCond) { }
	// RVA: 0x34f7e24 VA: 0x7595b0fe24
	public Void .ctor() { }
}
```