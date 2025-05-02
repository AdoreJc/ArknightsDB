# NewsCommuItemModel

**Namespace:** ` `


## Fields

- `Int32 goldCount`

- `Boolean empty`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class NewsCommuItemModel : NewsItemModel
{
	public Int32 goldCount; // 0x10
	public Boolean empty; // 0x14

	public override NewsType type { get; }

	// RVA: 0x2b697cc VA: 0x75951817cc
	public override NewsType get_type() { }
	// RVA: 0x2b697d4 VA: 0x75951817d4
	public override Boolean LoadData(RL02EndingText endingText, Special newsData) { }
	// RVA: 0x2b695fc VA: 0x75951815fc
	public Void .ctor() { }
}
```