# Act20sideEntryCartCompButtonPlugin

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `GameObject _panelLocked`

- `GameObject _panelAccessible`

- `Text _txtUnlockInfo`

- `UICommonTrackPoint _trackPoint`

- `GameObject _panelNew`

- `Boolean m_hasInited`

- `TrackPointViewProperty m_trackPoint`


## Methods

- `Void _InitIfNot()`

- `Void EventOnCartCompBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideEntryCartCompButtonPlugin : TemplateActivityCommonPlugin
{
	private GameObject _panelLocked; // 0x28
	private GameObject _panelAccessible; // 0x30
	private Text _txtUnlockInfo; // 0x38
	private UICommonTrackPoint _trackPoint; // 0x40
	private GameObject _panelNew; // 0x48
	private Boolean m_hasInited; // 0x50
	private TrackPointViewProperty m_trackPoint; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x8
	private static DelegateBridge __Hotfix0_EventOnCartCompBtnClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x32ef278 VA: 0x7595907278
	private Void _InitIfNot() { }
	// RVA: 0x32ef320 VA: 0x7595907320
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x32ef4e0 VA: 0x75959074e0
	public Void EventOnCartCompBtnClicked() { }
	// RVA: 0x32ef664 VA: 0x7595907664
	public Void .ctor() { }
}
```