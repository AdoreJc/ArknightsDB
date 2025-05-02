# ArchiveQuestController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `UIAnimationLocation _animEnterPanelToSelect`

- `ArchiveQuestDataBinder _questDataBinder`

- `ArchiveQuestFullScreenDataBinder _fullScreenDataBinder`


## Methods

- `Void set_actionOnSelectQuestType(Action`1)`

- `Void set_onFullscreenToggled(Action`1)`

- `Void set_itemSelectEvent(Action`1)`

- `Void OnSelectQuestType(SandboxV2ArchiveQuestType)`

- `Void OnItemSelectEvent(Int32)`

- `Void OnPicClicked()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveQuestController : ActArchiveController
{
	private UIAnimationLocation _animEnterPanelToSelect; // 0x38
	private ArchiveQuestDataBinder _questDataBinder; // 0x48
	private ArchiveQuestFullScreenDataBinder _fullScreenDataBinder; // 0x50
	private Action`1 m_onFullscreenToggled; // 0x58
	private Action`1 <actionOnSelectQuestType>k__BackingField; // 0x60
	private Action`1 <itemSelectEvent>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_actionOnSelectQuestType; // 0x0
	private static DelegateBridge __Hotfix0_set_actionOnSelectQuestType; // 0x8
	private static DelegateBridge __Hotfix0_get_onFullscreenToggled; // 0x10
	private static DelegateBridge __Hotfix0_set_onFullscreenToggled; // 0x18
	private static DelegateBridge __Hotfix0_InitAndAchieveDataBinders; // 0x20
	private static DelegateBridge __Hotfix0_get_itemSelectEvent; // 0x28
	private static DelegateBridge __Hotfix0_set_itemSelectEvent; // 0x30
	private static DelegateBridge __Hotfix0_OnSelectQuestType; // 0x38
	private static DelegateBridge __Hotfix0_OnEnter; // 0x40
	private static DelegateBridge __Hotfix0_OnItemSelectEvent; // 0x48
	private static DelegateBridge __Hotfix0_OnPicClicked; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Action`1 actionOnSelectQuestType { get; set; }
	public Action`1 onFullscreenToggled { get; set; }
	private Action`1 itemSelectEvent { get; set; }

	// RVA: 0x30701e0 VA: 0x75956881e0
	public Action`1 get_actionOnSelectQuestType() { }
	// RVA: 0x3070248 VA: 0x7595688248
	public Void set_actionOnSelectQuestType(Action`1 value) { }
	// RVA: 0x30702cc VA: 0x75956882cc
	public Action`1 get_onFullscreenToggled() { }
	// RVA: 0x3070334 VA: 0x7595688334
	public Void set_onFullscreenToggled(Action`1 value) { }
	// RVA: 0x3070470 VA: 0x7595688470
	public List`1 InitAndAchieveDataBinders() { }
	// RVA: 0x3070884 VA: 0x7595688884
	private Action`1 get_itemSelectEvent() { }
	// RVA: 0x30708ec VA: 0x75956888ec
	public Void set_itemSelectEvent(Action`1 value) { }
	// RVA: 0x3070970 VA: 0x7595688970
	public Void OnSelectQuestType(SandboxV2ArchiveQuestType type) { }
	// RVA: 0x3070a28 VA: 0x7595688a28
	public override Void OnEnter() { }
	// RVA: 0x3070b18 VA: 0x7595688b18
	public Void OnItemSelectEvent(Int32 index) { }
	// RVA: 0x3070bd0 VA: 0x7595688bd0
	public Void OnPicClicked() { }
	// RVA: 0x3070c70 VA: 0x7595688c70
	public Void .ctor() { }
	// RVA: 0x3070ce0 VA: 0x7595688ce0
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```