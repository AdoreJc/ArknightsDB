# StageZoneHomeThemeRoguelikeView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Image _imgMain`

- `Image _imgMainMagnify`

- `Sprite _imgLogo`

- `ZoneHomeRoguelikeEntryItemModel m_viewModel`

- `ActivityThemeData m_themeData`


## Methods

- `Void EventOnThemeClicked()`

- `Void <>xLuaBaseProxy_OnInit(StageZoneHomeThemeView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeThemeRoguelikeView : Plugin
{
	private Image _imgMain; // 0x20
	private Image _imgMainMagnify; // 0x28
	private Sprite _imgLogo; // 0x30
	private ZoneHomeRoguelikeEntryItemModel m_viewModel; // 0x38
	private ActivityThemeData m_themeData; // 0x40
	private static DelegateBridge __Hotfix0_GetThemeLogo; // 0x0
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_EventOnThemeClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2f0ddd0 VA: 0x7595525dd0
	public override Sprite GetThemeLogo() { }
	// RVA: 0x2f0de38 VA: 0x7595525e38
	protected override Void OnDataUpdated(Param param) { }
	// RVA: 0x2f0e07c VA: 0x759552607c
	protected override Void OnInit(StageZoneHomeThemeView holder) { }
	// RVA: 0x2f0e100 VA: 0x7595526100
	public Void EventOnThemeClicked() { }
	// RVA: 0x2f0e16c VA: 0x759552616c
	public Void .ctor() { }
	// RVA: 0x2f0e200 VA: 0x7595526200
	private Void <>xLuaBaseProxy_OnInit(StageZoneHomeThemeView P0) { }
}
```