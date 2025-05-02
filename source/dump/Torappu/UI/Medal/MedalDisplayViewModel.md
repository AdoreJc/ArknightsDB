# MedalDisplayViewModel

**Namespace:** `Torappu.UI.Medal`


## Fields

- `String medalGroupId`

- `MedalGroupData groupData`

- `Int32 availCount`


## Properties

- `Int32 totalCount`


## Methods

- `Int32 get_totalCount()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalDisplayViewModel
{
	public String medalGroupId; // 0x10
	public MedalGroupData groupData; // 0x18
	public Int32 availCount; // 0x20

	public Int32 totalCount { get; }

	// RVA: 0x27a8acc VA: 0x7594dc0acc
	public Int32 get_totalCount() { }
	// RVA: 0x27aa79c VA: 0x7594dc279c
	public Void .ctor() { }
}
```