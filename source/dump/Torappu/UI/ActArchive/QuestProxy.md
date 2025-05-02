# QuestProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void OnSelectQuestType(SandboxV2ArchiveQuestType)`

- `Void _OnItemSelect(Int32)`

- `Void StartAvgAndBackToArchiveAvg(StoryData)`

- `DataBundle _GenerateDataBundleToAvg()`

- `UIPageControllerParam _SceneParamToState(DataBundle)`

- `Void _OnFullscreenToggled(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class QuestProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefabPath; // 0x8
	private static DelegateBridge __Hotfix0_InitComp; // 0x10
	private static DelegateBridge __Hotfix0_OnSelectQuestType; // 0x18
	private static DelegateBridge __Hotfix0__OnItemSelect; // 0x20
	private static DelegateBridge __Hotfix0_StartAvgAndBackToArchiveAvg; // 0x28
	private static DelegateBridge __Hotfix0__GenerateDataBundleToAvg; // 0x30
	private static DelegateBridge __Hotfix0__SceneParamToState; // 0x38
	private static DelegateBridge __Hotfix0__OnFullscreenToggled; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	protected override String compType { get; }

	// RVA: 0x3011d74 VA: 0x7595629d74
	protected override String get_compType() { }
	// RVA: 0x3011df0 VA: 0x7595629df0
	protected override String GetPrefabPath() { }
	// RVA: 0x3011e60 VA: 0x7595629e60
	protected override Void InitComp() { }
	// RVA: 0x3012164 VA: 0x759562a164
	private Void OnSelectQuestType(SandboxV2ArchiveQuestType type) { }
	// RVA: 0x30122c8 VA: 0x759562a2c8
	private Void _OnItemSelect(Int32 index) { }
	// RVA: 0x301242c VA: 0x759562a42c
	public Void StartAvgAndBackToArchiveAvg(StoryData targetStory) { }
	// RVA: 0x301260c VA: 0x759562a60c
	private DataBundle _GenerateDataBundleToAvg() { }
	// RVA: 0x30127e8 VA: 0x759562a7e8
	private UIPageControllerParam _SceneParamToState(DataBundle bundleToState) { }
	// RVA: 0x3012a6c VA: 0x759562aa6c
	private Void _OnFullscreenToggled(Boolean isFullScreen) { }
	// RVA: 0x3012bc0 VA: 0x759562abc0
	public Void .ctor() { }
}
```