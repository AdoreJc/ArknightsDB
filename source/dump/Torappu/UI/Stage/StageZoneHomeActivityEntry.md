# StageZoneHomeActivityEntry

**Namespace:** `Torappu.UI.Stage`


## Fields

- `GameObject _panelItem`

- `Text _textItemCount`

- `Image _imgItemIcon`

- `GameObject _panelStageLocked`

- `Sprite _iconSideStory`

- `Sprite _iconBranchline`

- `Sprite _iconMiniStory`

- `Sprite _iconDefault`

- `ZoneHomeEntryActivityModel m_viewModel`

- `String m_checkDirtyActId`


## Methods

- `Void _LoadActivityEntryResIfNeeded()`

- `Void _UpdateItemCount()`

- `Void _UpdateStageInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeActivityEntry : StageZoneHomeEntryItemPlugin
{
	private GameObject _panelItem; // 0x30
	private Text _textItemCount; // 0x38
	private Image _imgItemIcon; // 0x40
	private GameObject _panelStageLocked; // 0x48
	private Sprite _iconSideStory; // 0x50
	private Sprite _iconBranchline; // 0x58
	private Sprite _iconMiniStory; // 0x60
	private Sprite _iconDefault; // 0x68
	private ZoneHomeEntryActivityModel m_viewModel; // 0x70
	private String m_checkDirtyActId; // 0x78
	private static DelegateBridge __Hotfix0_GetFuncIcon; // 0x0
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x8
	private static DelegateBridge __Hotfix0__LoadActivityEntryResIfNeeded; // 0x10
	private static DelegateBridge __Hotfix0__UpdateItemCount; // 0x18
	private static DelegateBridge __Hotfix0__UpdateStageInfo; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2ef9758 VA: 0x7595511758
	protected override Sprite GetFuncIcon() { }
	// RVA: 0x2ef98b4 VA: 0x75955118b4
	protected override Void OnDataUpdated() { }
	// RVA: 0x2ef9aa0 VA: 0x7595511aa0
	private Void _LoadActivityEntryResIfNeeded() { }
	// RVA: 0x2ef9cc0 VA: 0x7595511cc0
	private Void _UpdateItemCount() { }
	// RVA: 0x2ef9df0 VA: 0x7595511df0
	private Void _UpdateStageInfo() { }
	// RVA: 0x2efa004 VA: 0x7595512004
	public Void .ctor() { }
}
```