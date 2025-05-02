# LocationData

**Namespace:** ` `


## Fields

- `String groupId`

- `Int32 sortId`

- `Boolean isComplete`

- `Single location`


## Methods

- `Int32 CompareTo(LocationData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class LocationData : IHotfixable, IComparable`1
{
	public String groupId; // 0x10
	public Int32 sortId; // 0x18
	public Boolean isComplete; // 0x1c
	public Single location; // 0x20
	private static DelegateBridge __Hotfix0_CompareTo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x26b12ac VA: 0x7594cc92ac
	public Int32 CompareTo(LocationData other) { }
	// RVA: 0x26b0cd8 VA: 0x7594cc8cd8
	public Void .ctor() { }
}
```