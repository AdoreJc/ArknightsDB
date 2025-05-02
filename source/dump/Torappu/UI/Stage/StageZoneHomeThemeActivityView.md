# StageZoneHomeThemeActivityView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `GameObject _panelItem`

- `Text _textItemCount`

- `Image _imgItem`

- `Image _imgMain`

- `Image _imgMainMagnify`

- `ZoneHomeEntryActivityModel m_viewModel`

- `ActivityThemeData m_themeData`

- `UIItemViewModel m_itemModel`


## Methods

- `Void _UpdateActivityItemInfo()`

- `Void EventOnThemeClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeThemeActivityView : Plugin
{
	private GameObject _panelItem; // 0x20
	private Text _textItemCount; // 0x28
	private Image _imgItem; // 0x30
	private Image _imgMain; // 0x38
	private Image _imgMainMagnify; // 0x40
	private ZoneHomeEntryActivityModel m_viewModel; // 0x48
	private ActivityThemeData m_themeData; // 0x50
	private UIItemViewModel m_itemModel; // 0x58
	private static DelegateBridge __Hotfix0_GetThemeLogo; // 0x0
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x8
	private static DelegateBridge __Hotfix0__UpdateActivityItemInfo; // 0x10
	private static DelegateBridge __Hotfix0_EventOnThemeClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2f0cb54 VA: 0x7595524b54
	public override Sprite GetThemeLogo() { }
	// RVA: 0x2f0cbb8 VA: 0x7595524bb8
	protected override Void OnDataUpdated(Param param) { }
	// RVA: 0x2f0ce40 VA: 0x7595524e40
	private Void _UpdateActivityItemInfo() { }
	// RVA: 0x2f0d078 VA: 0x7595525078
	public Void EventOnThemeClicked() { }
	// RVA: 0x2f0d0e4 VA: 0x75955250e4
	public Void .ctor() { }
}
```