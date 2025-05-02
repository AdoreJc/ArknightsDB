# NewsHiddenItemModel

**Namespace:** ` `


## Fields

- `Boolean passed`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class NewsHiddenItemModel : NewsItemModel
{
	public Int32[] count; // 0x10
	public Boolean passed; // 0x18

	public override NewsType type { get; }

	// RVA: 0x2b6980c VA: 0x759518180c
	public override NewsType get_type() { }
	// RVA: 0x2b69814 VA: 0x7595181814
	public override Boolean LoadData(RL02EndingText endingText, Special newsData) { }
	// RVA: 0x2b69738 VA: 0x7595181738
	public Void .ctor() { }
}
```