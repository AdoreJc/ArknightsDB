# SandboxV2RiftDifficultySelectViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Int32 canSelectDifficultyLevel`

- `Int32 completedDifficultyLevel`

- `Int32 selectDifficultyLevel`

- `Int32 sequenceNum`

- `Boolean m_isRandomRift`

- `Boolean m_isPreyRift`


## Properties

- `String selectDifficultyId`


## Methods

- `String get_selectDifficultyId()`

- `Void LoadData(String, String)`

- `Void UpdateSelectDifficulty(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RiftDifficultySelectViewModel : IHotfixable
{
	private const Int32 DEFAULT_DISPLAY_ITEM_COUNT; // 0x0
	public List`1 difficultyItems; // 0x10
	public Int32 canSelectDifficultyLevel; // 0x18
	public Int32 completedDifficultyLevel; // 0x1c
	public Int32 selectDifficultyLevel; // 0x20
	public Int32 sequenceNum; // 0x24
	private Boolean m_isRandomRift; // 0x28
	private Boolean m_isPreyRift; // 0x29
	private static DelegateBridge __Hotfix0_get_selectDifficultyId; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_UpdateSelectDifficulty; // 0x10
	private static DelegateBridge __Hotfix0__GetRewardGroupById; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String selectDifficultyId { get; }

	// RVA: 0x25f7930 VA: 0x7594c0f930
	public String get_selectDifficultyId() { }
	// RVA: 0x25f737c VA: 0x7594c0f37c
	public Void LoadData(String topicId, String riftId) { }
	// RVA: 0x25f8230 VA: 0x7594c10230
	public Void UpdateSelectDifficulty(Int32 selectLevel) { }
	// RVA: 0x2600f00 VA: 0x7594c18f00
	private List`1 _GetRewardGroupById(String groupId, SandboxV2Data gameData) { }
	// RVA: 0x2601510 VA: 0x7594c19510
	public Void .ctor() { }
}
```