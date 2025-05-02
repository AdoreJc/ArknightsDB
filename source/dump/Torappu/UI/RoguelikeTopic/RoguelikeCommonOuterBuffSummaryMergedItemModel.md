# RoguelikeCommonOuterBuffSummaryMergedItemModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Int32 viewIndex`

- `RoguelikeTopicDisplayItem displayItem`


## Properties

- `Boolean isLocked`


## Methods

- `Boolean get_isLocked()`

- `String GetId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeCommonOuterBuffSummaryMergedItemModel : IHotfixable
{
	public Int32 viewIndex; // 0x10
	public RoguelikeTopicDisplayItem displayItem; // 0x18
	private static DelegateBridge __Hotfix0_get_isLocked; // 0x0
	private static DelegateBridge __Hotfix0_GetId; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isLocked { get; }

	// RVA: 0x26643a8 VA: 0x7594c7c3a8
	public Boolean get_isLocked() { }
	// RVA: 0x2665a6c VA: 0x7594c7da6c
	public String GetId() { }
	// RVA: 0x2665b00 VA: 0x7594c7db00
	public Void .ctor() { }
}
```