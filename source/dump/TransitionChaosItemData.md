# TransitionChaosItemData

**Namespace:** ` `


## Fields

- `String chaosId`

- `String chaosName`

- `String chaosIconId`

- `Int32 sortId`

- `Int32 chaosLevel`


## Methods

- `Void LoadData(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TransitionChaosItemData : IHotfixable
{
	public String chaosId; // 0x10
	public String chaosName; // 0x18
	public String chaosIconId; // 0x20
	public Int32 sortId; // 0x28
	public Int32 chaosLevel; // 0x2c
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2bb19d0 VA: 0x75951c99d0
	public Void LoadData(String topicId, String chaosId) { }
	// RVA: 0x2bb1b74 VA: 0x75951c9b74
	public Void .ctor() { }
}
```