# RoguelikeMenuRelicItemData

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `IRoguelikeRelicViewModel relicViewModel`

- `Int32 viewIndex`

- `Boolean showFullIcon`

- `String indexId`


## Methods

- `String GetId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuRelicItemData : IHotfixable
{
	public const String INDEX_ID_FORMAT; // 0x0
	public IRoguelikeRelicViewModel relicViewModel; // 0x10
	public Int32 viewIndex; // 0x18
	public Boolean showFullIcon; // 0x1c
	public String indexId; // 0x20
	private static DelegateBridge __Hotfix0_GetId; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2a41e6c VA: 0x7595059e6c
	public String GetId() { }
	// RVA: 0x2a41ed4 VA: 0x7595059ed4
	public Void .ctor() { }
}
```