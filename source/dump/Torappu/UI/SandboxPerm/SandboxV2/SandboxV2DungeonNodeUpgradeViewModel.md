# SandboxV2DungeonNodeUpgradeViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String m_topicId`


## Properties

- `String topicId`


## Methods

- `String get_topicId()`

- `Void LoadData(String, Dictionary`2, List`1)`

- `Void RefreshPlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonNodeUpgradeViewModel : IHotfixable
{
	private readonly List`1 m_items; // 0x10
	private String m_topicId; // 0x18
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_items; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x18
	private static DelegateBridge __Hotfix0__SearchItemInBackpack; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String topicId { get; }
	public List`1 items { get; }

	// RVA: 0x25b6e48 VA: 0x7594bcee48
	public String get_topicId() { }
	// RVA: 0x25b6eb0 VA: 0x7594bceeb0
	public List`1 get_items() { }
	// RVA: 0x25b6f18 VA: 0x7594bcef18
	public Void LoadData(String topicId, Dictionary`2 upgrades, List`1 completedUpgrades) { }
	// RVA: 0x25b7688 VA: 0x7594bcf688
	public Void RefreshPlayerData() { }
	// RVA: 0x25b7444 VA: 0x7594bcf444
	private static Int32 _SearchItemInBackpack(SandboxV2Data gameData, PlayerSandboxV2 playerData, SandboxPermItemType itemType, SandboxV2ItemTrapTag itemTag, Int32 rarity) { }
	// RVA: 0x25b79bc VA: 0x7594bcf9bc
	public Void .ctor() { }
}
```