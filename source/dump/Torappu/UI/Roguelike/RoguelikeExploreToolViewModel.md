# RoguelikeExploreToolViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `String topicId`

- `String itemId`

- `String name`

- `String usage`

- `String subIcon`

- `Int64 ts`


## Methods

- `String GetItemId()`

- `String GetId()`

- `RoguelikeMenuRelicItemType GetRelicItemType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeExploreToolViewModel : IRoguelikeRelicViewModel, IHotfixable
{
	public String topicId; // 0x10
	public String itemId; // 0x18
	public String name; // 0x20
	public String usage; // 0x28
	public String subIcon; // 0x30
	public Int64 ts; // 0x38
	private static DelegateBridge __Hotfix0_GetItemId; // 0x0
	private static DelegateBridge __Hotfix0_GetId; // 0x8
	private static DelegateBridge __Hotfix0_GetRelicItemType; // 0x10
	private static DelegateBridge __Hotfix0_Create; // 0x18
	private static DelegateBridge __Hotfix1_Create; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x29f7c18 VA: 0x759500fc18
	public String GetItemId() { }
	// RVA: 0x29f7c80 VA: 0x759500fc80
	public String GetId() { }
	// RVA: 0x29f7ce8 VA: 0x759500fce8
	public RoguelikeMenuRelicItemType GetRelicItemType() { }
	// RVA: 0x29f7d50 VA: 0x759500fd50
	public static RoguelikeExploreToolViewModel Create(String topicId, ExploreTool exploreTool) { }
	// RVA: 0x29f7f30 VA: 0x759500ff30
	public static RoguelikeExploreToolViewModel Create(String topicId, String exploreToolId, Int64 ts) { }
	// RVA: 0x29f7ec0 VA: 0x759500fec0
	public Void .ctor() { }
}
```