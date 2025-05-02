# Act12D6OuterBuffDetailStateBean

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `PlayerOuterBuffData <BuffData>k__BackingField`


## Properties

- `PlayerOuterBuffData BuffData`


## Methods

- `PlayerOuterBuffData get_BuffData()`

- `Void set_BuffData(PlayerOuterBuffData)`

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6OuterBuffDetailStateBean : IStateBean, IHotfixable
{
	private PlayerOuterBuffData <BuffData>k__BackingField; // 0x10
	private static DelegateBridge __Hotfix0_get_BuffData; // 0x0
	private static DelegateBridge __Hotfix0_set_BuffData; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public PlayerOuterBuffData BuffData { get; set; }

	// RVA: 0x347785c VA: 0x7595a8f85c
	public PlayerOuterBuffData get_BuffData() { }
	// RVA: 0x347cf38 VA: 0x7595a94f38
	public Void set_BuffData(PlayerOuterBuffData value) { }
	// RVA: 0x347cfbc VA: 0x7595a94fbc
	public Void LoadData() { }
	// RVA: 0x347d0d8 VA: 0x7595a950d8
	public Void .ctor() { }
}
```