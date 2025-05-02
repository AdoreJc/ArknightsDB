# QuestCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Boolean m_needClosePageOnBack`

- `ArchiveQuestProperty quest`


## Methods

- `Boolean <>xLuaBaseProxy_NeedClosePageOnBack()`

- `Boolean <>xLuaBaseProxy_HasNewItem()`

- `Boolean <>xLuaBaseProxy_OnBackBtnPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class QuestCompInfo : ActArchiveCompInfo
{
	public const String KEY_ARCHIVE_QUEST_TYPE; // 0x0
	public const String KEY_ARCHIVE_QUEST_FOCUS_INDEX; // 0x0
	public const String KEY_CLOSE_PAGE_ON_BACK; // 0x0
	private Boolean m_needClosePageOnBack; // 0x18
	public ArchiveQuestProperty quest; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x10
	private static DelegateBridge __Hotfix0_NeedClosePageOnBack; // 0x18
	private static DelegateBridge __Hotfix0_IsValid; // 0x20
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x28
	private static DelegateBridge __Hotfix0_HasNewItem; // 0x30
	private static DelegateBridge __Hotfix0_OnBackBtnPressed; // 0x38


	// RVA: 0x3076dec VA: 0x759568edec
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x3076e74 VA: 0x759568ee74
	public override Void LoadData(String archiveId) { }
	// RVA: 0x307704c VA: 0x759568f04c
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x30771a0 VA: 0x759568f1a0
	public override Boolean NeedClosePageOnBack() { }
	// RVA: 0x3077208 VA: 0x759568f208
	public override Boolean IsValid() { }
	// RVA: 0x3077294 VA: 0x759568f294
	public override Void NotifyUpdate() { }
	// RVA: 0x307733c VA: 0x759568f33c
	public override Boolean HasNewItem() { }
	// RVA: 0x30775cc VA: 0x759568f5cc
	public override Boolean OnBackBtnPressed() { }
	// RVA: 0x30776a8 VA: 0x759568f6a8
	private Boolean <>xLuaBaseProxy_NeedClosePageOnBack() { }
	// RVA: 0x30776b0 VA: 0x759568f6b0
	private Boolean <>xLuaBaseProxy_HasNewItem() { }
	// RVA: 0x30776b8 VA: 0x759568f6b8
	private Boolean <>xLuaBaseProxy_OnBackBtnPressed() { }
}
```