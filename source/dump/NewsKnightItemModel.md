# NewsKnightItemModel

**Namespace:** ` `


## Fields

- `Int32 battleCount`

- `Boolean passed`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class NewsKnightItemModel : NewsItemModel
{
	public Int32 battleCount; // 0x10
	public Boolean passed; // 0x14

	public override NewsType type { get; }

	// RVA: 0x2b698f0 VA: 0x75951818f0
	public override NewsType get_type() { }
	// RVA: 0x2b698f8 VA: 0x75951818f8
	public override Boolean LoadData(RL02EndingText endingText, Special newsData) { }
	// RVA: 0x2b69740 VA: 0x7595181740
	public Void .ctor() { }
}
```