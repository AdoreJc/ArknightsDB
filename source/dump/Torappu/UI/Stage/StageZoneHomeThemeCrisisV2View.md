# StageZoneHomeThemeCrisisV2View

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Text _textPoint`

- `GameObject _panelNoRank`

- `Image _imgMain`

- `Image _imgMainMagnify`

- `ZoneHomeEntryCrisisV2Model m_viewModel`


## Methods

- `Void EventOnThemeClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeThemeCrisisV2View : Plugin, IHotfixable
{
	private Text _textPoint; // 0x20
	private GameObject _panelNoRank; // 0x28
	private Image _imgMain; // 0x30
	private Image _imgMainMagnify; // 0x38
	private ZoneHomeEntryCrisisV2Model m_viewModel; // 0x40
	private static DelegateBridge __Hotfix0_GetThemeLogo; // 0x0
	private static DelegateBridge __Hotfix0_EventOnThemeClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f0d1c4 VA: 0x75955251c4
	public override Sprite GetThemeLogo() { }
	// RVA: 0x2f0d228 VA: 0x7595525228
	public Void EventOnThemeClicked() { }
	// RVA: 0x2f0d294 VA: 0x7595525294
	protected override Void OnDataUpdated(Param param) { }
	// RVA: 0x2f0d5e4 VA: 0x75955255e4
	public Void .ctor() { }
}
```