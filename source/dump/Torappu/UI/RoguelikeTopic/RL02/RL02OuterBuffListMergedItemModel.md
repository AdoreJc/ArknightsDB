# RL02OuterBuffListMergedItemModel

**Namespace:** `Torappu.UI.RoguelikeTopic.RL02`


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
// Namespace : Torappu.UI.RoguelikeTopic.RL02
public class RL02OuterBuffListMergedItemModel : IHotfixable
{
	public Int32 viewIndex; // 0x10
	public RoguelikeTopicDisplayItem displayItem; // 0x18
	private static DelegateBridge __Hotfix0_get_isLocked; // 0x0
	private static DelegateBridge __Hotfix0_GetId; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isLocked { get; }

	// RVA: 0x26c4838 VA: 0x7594cdc838
	public Boolean get_isLocked() { }
	// RVA: 0x26c64ac VA: 0x7594cde4ac
	public String GetId() { }
	// RVA: 0x26c6540 VA: 0x7594cde540
	public Void .ctor() { }
}
```