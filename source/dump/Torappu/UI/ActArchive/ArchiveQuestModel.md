# ArchiveQuestModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Int32 focusIndex`

- `Boolean isFullScreen`

- `SandboxV2ArchiveQuestType m_selectedType`

- `String m_archiveId`

- `Boolean m_isFastMode`


## Properties

- `String archiveId`

- `SandboxV2ArchiveQuestType selectedType`


## Methods

- `String get_archiveId()`

- `SandboxV2ArchiveQuestType get_selectedType()`

- `Void LoadData(String, Dictionary`2, Dictionary`2)`

- `Void ChangeQuestType(SandboxV2ArchiveQuestType, Boolean)`

- `Void ResetDetailData()`

- `Void _InitFirstUnlockedItemIndex()`

- `Boolean SetFocusIndex(Int32)`

- `ArchiveQuestItemModel GetSelectedItemModel()`

- `Boolean CheckIfIsFastModeAndConsume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveQuestModel : IHotfixable
{
	public const Int32 INDEX_NOT_FOUND; // 0x0
	public Dictionary`2 questGroupDict; // 0x10
	public Int32 focusIndex; // 0x18
	public Boolean isFullScreen; // 0x1c
	private SandboxV2ArchiveQuestType m_selectedType; // 0x20
	private String m_archiveId; // 0x28
	private Boolean m_isFastMode; // 0x30
	private static DelegateBridge __Hotfix0_get_archiveId; // 0x0
	private static DelegateBridge __Hotfix0_get_selectedType; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_ChangeQuestType; // 0x18
	private static DelegateBridge __Hotfix0_ResetDetailData; // 0x20
	private static DelegateBridge __Hotfix0__InitFirstUnlockedItemIndex; // 0x28
	private static DelegateBridge __Hotfix0_SetFocusIndex; // 0x30
	private static DelegateBridge __Hotfix0_GetSelectedItemModel; // 0x38
	private static DelegateBridge __Hotfix0_GetItemModelList; // 0x40
	private static DelegateBridge __Hotfix0_CheckIfIsFastModeAndConsume; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public String archiveId { get; }
	public SandboxV2ArchiveQuestType selectedType { get; }

	// RVA: 0x3071220 VA: 0x7595689220
	public String get_archiveId() { }
	// RVA: 0x3071288 VA: 0x7595689288
	public SandboxV2ArchiveQuestType get_selectedType() { }
	// RVA: 0x3075e84 VA: 0x759568de84
	public Void LoadData(String archiveId, Dictionary`2 questData, Dictionary`2 questTypeData) { }
	// RVA: 0x30766f0 VA: 0x759568e6f0
	public Void ChangeQuestType(SandboxV2ArchiveQuestType type, Boolean isFastMode) { }
	// RVA: 0x30768b4 VA: 0x759568e8b4
	public Void ResetDetailData() { }
	// RVA: 0x30767a8 VA: 0x759568e7a8
	private Void _InitFirstUnlockedItemIndex() { }
	// RVA: 0x307692c VA: 0x759568e92c
	public Boolean SetFocusIndex(Int32 toIndex) { }
	// RVA: 0x3076abc VA: 0x759568eabc
	public ArchiveQuestItemModel GetSelectedItemModel() { }
	// RVA: 0x307140c VA: 0x759568940c
	public List`1 GetItemModelList() { }
	// RVA: 0x30712f0 VA: 0x75956892f0
	public Boolean CheckIfIsFastModeAndConsume() { }
	// RVA: 0x3076cbc VA: 0x759568ecbc
	public Void .ctor() { }
}
```