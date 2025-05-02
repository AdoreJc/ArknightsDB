# StageZoneHomeThemeSandboxPermView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Image _imgMain`

- `Sprite _imgLogo`

- `ZoneHomeSandboxPermItemModel m_viewModel`


## Methods

- `Void EventOnThemeClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeThemeSandboxPermView : Plugin, IHotfixable
{
	private Image _imgMain; // 0x20
	private Sprite _imgLogo; // 0x28
	private ZoneHomeSandboxPermItemModel m_viewModel; // 0x30
	private static DelegateBridge __Hotfix0_GetThemeLogo; // 0x0
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x8
	private static DelegateBridge __Hotfix0_EventOnThemeClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f0e208 VA: 0x7595526208
	public override Sprite GetThemeLogo() { }
	// RVA: 0x2f0e270 VA: 0x7595526270
	protected override Void OnDataUpdated(Param param) { }
	// RVA: 0x2f0e438 VA: 0x7595526438
	public Void EventOnThemeClicked() { }
	// RVA: 0x2f0e4a4 VA: 0x75955264a4
	public Void .ctor() { }
}
```