# Rl03OuterBuffSummaryMergedItemModel

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


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
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class Rl03OuterBuffSummaryMergedItemModel : IHotfixable
{
	public Int32 viewIndex; // 0x10
	public RoguelikeTopicDisplayItem displayItem; // 0x18
	private static DelegateBridge __Hotfix0_get_isLocked; // 0x0
	private static DelegateBridge __Hotfix0_GetId; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isLocked { get; }

	// RVA: 0x26ad740 VA: 0x7594cc5740
	public Boolean get_isLocked() { }
	// RVA: 0x26aeee4 VA: 0x7594cc6ee4
	public String GetId() { }
	// RVA: 0x26aef78 VA: 0x7594cc6f78
	public Void .ctor() { }
}
```