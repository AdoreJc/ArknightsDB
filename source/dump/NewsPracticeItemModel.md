# NewsPracticeItemModel

**Namespace:** ` `


## Fields

- `Int32 count`

- `Boolean heavyCost`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class NewsPracticeItemModel : NewsItemModel
{
	public Int32 count; // 0x10
	public Boolean heavyCost; // 0x14

	public override NewsType type { get; }

	// RVA: 0x2b69930 VA: 0x7595181930
	public override NewsType get_type() { }
	// RVA: 0x2b69938 VA: 0x7595181938
	public override Boolean LoadData(RL02EndingText endingText, Special newsData) { }
	// RVA: 0x2b69750 VA: 0x7595181750
	public Void .ctor() { }
}
```