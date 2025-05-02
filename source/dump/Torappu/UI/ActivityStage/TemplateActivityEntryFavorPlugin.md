# TemplateActivityEntryFavorPlugin

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `UICommonTrackPoint _trackPoint`

- `GameObject _favorItem`

- `TemplateActivityFavorViewModel m_cacheViewModel`


## Methods

- `Void OnFavorClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityEntryFavorPlugin : TemplateActivityCommonPlugin
{
	private UICommonTrackPoint _trackPoint; // 0x28
	private GameObject _favorItem; // 0x30
	private TemplateActivityFavorViewModel m_cacheViewModel; // 0x38
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge __Hotfix0_OnFavorClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3095378 VA: 0x75956ad378
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x3095574 VA: 0x75956ad574
	public Void OnFavorClick() { }
	// RVA: 0x309565c VA: 0x75956ad65c
	public Void .ctor() { }
}
```