# Act36sideEntryFoodHandbookPlugin

**Namespace:** `Torappu.Activity.Act36side`


## Fields

- `GameObject _hasRewardGo`

- `UICommonTrackPoint _newTrackPoint`

- `TrackPointViewProperty m_trackPointProp`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void OpenFoodHandbookPage()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act36side
public class Act36sideEntryFoodHandbookPlugin : TemplateActivityCommonPlugin, IHotfixable
{
	private GameObject _hasRewardGo; // 0x28
	private UICommonTrackPoint _newTrackPoint; // 0x30
	private TrackPointViewProperty m_trackPointProp; // 0x38
	private Boolean m_hasInited; // 0x40
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OpenFoodHandbookPage; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x32441f0 VA: 0x759585c1f0
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x324430c VA: 0x759585c30c
	private Void _InitIfNot() { }
	// RVA: 0x32443b4 VA: 0x759585c3b4
	public Void OpenFoodHandbookPage() { }
	// RVA: 0x324455c VA: 0x759585c55c
	public Void .ctor() { }
}
```