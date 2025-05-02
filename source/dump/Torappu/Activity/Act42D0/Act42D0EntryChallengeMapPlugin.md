# Act42D0EntryChallengeMapPlugin

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `GameObject _objAllClear`

- `UICommonTrackPoint _objTrackPoint`

- `GameObject _objClosed`

- `Boolean m_isInited`

- `TrackPointViewProperty m_challengeTrackPointProperty`


## Methods

- `Void _InitIfNot()`

- `Void OnChallengeClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0EntryChallengeMapPlugin : TemplateActivityCommonPlugin
{
	private GameObject _objAllClear; // 0x28
	private UICommonTrackPoint _objTrackPoint; // 0x30
	private GameObject _objClosed; // 0x38
	private Boolean m_isInited; // 0x40
	private TrackPointViewProperty m_challengeTrackPointProperty; // 0x48
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnChallengeClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3215458 VA: 0x759582d458
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x32155d4 VA: 0x759582d5d4
	private Void _InitIfNot() { }
	// RVA: 0x32156c4 VA: 0x759582d6c4
	public Void OnChallengeClick() { }
	// RVA: 0x3215848 VA: 0x759582d848
	public Void .ctor() { }
}
```