# RelicItemModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String relicId`

- `Int32 sortId`

- `Int32 groupId`

- `String name`

- `String usage`

- `String description`

- `Boolean isSpRelic`

- `RoguelikeArchiveItemUnlockStatus status`

- `String orderId`

- `String difficultyDesc`

- `Int32 m_defaultDifficultyIndex`


## Properties

- `Int32 defaultDifficultyIndex`


## Methods

- `Int32 get_defaultDifficultyIndex()`

- `Void SetAsRootItem(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class RelicItemModel : ArchiveItemModel
{
	public String relicId; // 0x30
	public Int32 sortId; // 0x38
	public Int32 groupId; // 0x3c
	public String name; // 0x40
	public String usage; // 0x48
	public String description; // 0x50
	public Boolean isSpRelic; // 0x58
	public RoguelikeArchiveItemUnlockStatus status; // 0x5c
	public String orderId; // 0x60
	public String difficultyDesc; // 0x68
	private List`1 m_difficultyItems; // 0x70
	private Int32 m_defaultDifficultyIndex; // 0x78
	private static DelegateBridge __Hotfix0_get_difficultyItems; // 0x0
	private static DelegateBridge __Hotfix0_get_defaultDifficultyIndex; // 0x8
	private static DelegateBridge __Hotfix0_GetFuncId; // 0x10
	private static DelegateBridge __Hotfix0_GetDesc; // 0x18
	private static DelegateBridge __Hotfix0_SetAsRootItem; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public List`1 difficultyItems { get; }
	public Int32 defaultDifficultyIndex { get; }

	// RVA: 0x307911c VA: 0x759569111c
	public List`1 get_difficultyItems() { }
	// RVA: 0x3079b14 VA: 0x7595691b14
	public Int32 get_defaultDifficultyIndex() { }
	// RVA: 0x307b244 VA: 0x7595693244
	public override String GetFuncId() { }
	// RVA: 0x307b2ac VA: 0x75956932ac
	public override String GetDesc() { }
	// RVA: 0x307b314 VA: 0x7595693314
	public Void SetAsRootItem(List`1 items) { }
	// RVA: 0x307b428 VA: 0x7595693428
	public Void .ctor() { }
}
```