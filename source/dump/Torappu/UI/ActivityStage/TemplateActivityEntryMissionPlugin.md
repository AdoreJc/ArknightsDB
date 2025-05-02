# TemplateActivityEntryMissionPlugin

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `UICommonTrackPoint _trackPoint`

- `UIActTrackPoint _actTrackPoint`

- `Boolean m_hasInited`

- `TrackPointViewProperty m_trackPoint`


## Methods

- `Void _InitIfNot()`

- `Void OnMissionClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityEntryMissionPlugin : TemplateActivityCommonPlugin
{
	private UICommonTrackPoint _trackPoint; // 0x28
	private UIActTrackPoint _actTrackPoint; // 0x30
	private Boolean m_hasInited; // 0x38
	private TrackPointViewProperty m_trackPoint; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x8
	private static DelegateBridge __Hotfix0_OnMissionClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x30958e4 VA: 0x75956ad8e4
	private Void _InitIfNot() { }
	// RVA: 0x3095a18 VA: 0x75956ada18
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x3095b64 VA: 0x75956adb64
	public Void OnMissionClick() { }
	// RVA: 0x3095c4c VA: 0x75956adc4c
	public Void .ctor() { }
}
```