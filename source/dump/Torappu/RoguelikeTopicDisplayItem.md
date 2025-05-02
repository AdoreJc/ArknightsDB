# RoguelikeTopicDisplayItem

**Namespace:** `Torappu`


## Fields

- `String displayType`

- `Int32 displayNum`

- `RoguelikeTopicDevTokenDisplayForm displayForm`

- `String tokenDesc`

- `Int32 sortId`


## Methods

- `String GetDisplayStr()`

- `String GetDisplayValueStr()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RoguelikeTopicDisplayItem
{
	public String displayType; // 0x10
	public Int32 displayNum; // 0x18
	public RoguelikeTopicDevTokenDisplayForm displayForm; // 0x1c
	public String tokenDesc; // 0x20
	public Int32 sortId; // 0x28


	// RVA: 0x34ab284 VA: 0x7595ac3284
	public String GetDisplayStr() { }
	// RVA: 0x34ab334 VA: 0x7595ac3334
	public String GetDisplayValueStr() { }
	// RVA: 0x34ab3dc VA: 0x7595ac33dc
	public Void .ctor() { }
}
```