# RoguelikeTrapViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `String topicId`

- `String itemId`

- `String name`

- `String usage`

- `String subIcon`

- `Boolean canSacrifice`

- `Int64 ts`


## Methods

- `String GetItemId()`

- `String GetId()`

- `RoguelikeMenuRelicItemType GetRelicItemType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeTrapViewModel : IRoguelikeRelicViewModel, IHotfixable
{
	private const String TRAP_ID; // 0x0
	public String topicId; // 0x10
	public String itemId; // 0x18
	public String name; // 0x20
	public String usage; // 0x28
	public String subIcon; // 0x30
	public Boolean canSacrifice; // 0x38
	public Int64 ts; // 0x40
	private static DelegateBridge __Hotfix0_GetItemId; // 0x0
	private static DelegateBridge __Hotfix0_GetId; // 0x8
	private static DelegateBridge __Hotfix0_GetRelicItemType; // 0x10
	private static DelegateBridge __Hotfix0_Create; // 0x18
	private static DelegateBridge __Hotfix1_Create; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x29f67e0 VA: 0x759500e7e0
	public String GetItemId() { }
	// RVA: 0x29f6848 VA: 0x759500e848
	public String GetId() { }
	// RVA: 0x29f68c4 VA: 0x759500e8c4
	public RoguelikeMenuRelicItemType GetRelicItemType() { }
	// RVA: 0x29f692c VA: 0x759500e92c
	public static RoguelikeTrapViewModel Create(String topicId, Trap trap) { }
	// RVA: 0x29f6b0c VA: 0x759500eb0c
	public static RoguelikeTrapViewModel Create(String topicId, String trapId, Int64 ts) { }
	// RVA: 0x29f6a9c VA: 0x759500ea9c
	public Void .ctor() { }
}
```