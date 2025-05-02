# SlotModel

**Namespace:** ` `


## Fields

- `State state`

- `DateTime startTs`

- `DateTime maxFinishTs`

- `DateTime realFinishTs`

- `Int32 durationInSec`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SlotModel
{
	public State state; // 0x10
	public Int32[] tags; // 0x18
	public TagItem[] selectTags; // 0x20
	public DateTime startTs; // 0x28
	public DateTime maxFinishTs; // 0x30
	public DateTime realFinishTs; // 0x38
	public Int32 durationInSec; // 0x40


	// RVA: 0x32d4e44 VA: 0x75958ece44
	public Void .ctor() { }
}
```