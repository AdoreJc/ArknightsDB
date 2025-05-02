# SandboxV2BasementUpgradeViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String <topicId>k__BackingField`

- `PlayerSandboxV2 playerData`

- `SandboxV2BaseUpdateData m_currentUpdateData`

- `Int32 m_currentBaseLevel`

- `Int32 m_nextBaseLevel`


## Properties

- `String topicId`

- `Int32 currentLevel`

- `Int32 nextBaseLevel`

- `SandboxV2BaseUpdateData currentUpdateData`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`

- `Int32 get_currentLevel()`

- `Int32 get_nextBaseLevel()`

- `SandboxV2BaseUpdateData get_currentUpdateData()`

- `Void LoadData(String)`

- `Void _GenUpgradeItemList()`

- `Void _GenUpgradePreviewGroupList()`

- `Void _GenUpgradeConditionList()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2BasementUpgradeViewModel : IHotfixable
{
	private String <topicId>k__BackingField; // 0x10
	public List`1 updateData; // 0x18
	public PlayerSandboxV2 playerData; // 0x20
	public List`1 updateItemList; // 0x28
	public List`1 updatePreviewGroupList; // 0x30
	public List`1 updateConditionList; // 0x38
	public Dictionary`2 updatePreviewDict; // 0x40
	private SandboxV2BaseUpdateData m_currentUpdateData; // 0x48
	private Int32 m_currentBaseLevel; // 0x50
	private Int32 m_nextBaseLevel; // 0x54
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_set_topicId; // 0x8
	private static DelegateBridge __Hotfix0_get_currentLevel; // 0x10
	private static DelegateBridge __Hotfix0_get_nextBaseLevel; // 0x18
	private static DelegateBridge __Hotfix0_get_currentUpdateData; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0__GenUpgradeItemList; // 0x30
	private static DelegateBridge __Hotfix0__GenUpgradePreviewGroupList; // 0x38
	private static DelegateBridge __Hotfix0__GenUpgradeConditionList; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public String topicId { get; set; }
	public Int32 currentLevel { get; }
	public Int32 nextBaseLevel { get; }
	public SandboxV2BaseUpdateData currentUpdateData { get; }

	// RVA: 0x250f5ac VA: 0x7594b275ac
	public String get_topicId() { }
	// RVA: 0x2510eb8 VA: 0x7594b28eb8
	public Void set_topicId(String value) { }
	// RVA: 0x251023c VA: 0x7594b2823c
	public Int32 get_currentLevel() { }
	// RVA: 0x25101d4 VA: 0x7594b281d4
	public Int32 get_nextBaseLevel() { }
	// RVA: 0x25100b8 VA: 0x7594b280b8
	public SandboxV2BaseUpdateData get_currentUpdateData() { }
	// RVA: 0x250cd08 VA: 0x7594b24d08
	public Void LoadData(String topic) { }
	// RVA: 0x2510f3c VA: 0x7594b28f3c
	private Void _GenUpgradeItemList() { }
	// RVA: 0x2511578 VA: 0x7594b29578
	private Void _GenUpgradePreviewGroupList() { }
	// RVA: 0x2511280 VA: 0x7594b29280
	private Void _GenUpgradeConditionList() { }
	// RVA: 0x2511b54 VA: 0x7594b29b54
	public Void .ctor() { }
}
```