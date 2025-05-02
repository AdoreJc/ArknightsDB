# Act29sideEntryTuningPlugin

**Namespace:** `Torappu.Activity.Act29side`


## Fields

- `String m_actId`

- `Boolean m_hasInited`

- `String m_toastDesc`

- `Status m_cachedCurrStatus`

- `String m_cachedCrossDayTrackId`

- `TrackPointViewProperty m_trackPointLockProp`

- `TrackPointViewProperty m_trackPointProp`

- `UICommonTrackPoint _trackPointLock`

- `UIActTrackPoint _trackPoint`

- `GameObject _buttonClick`

- `Text _textUnlockDesc`

- `GameObject _panelLocked`


## Methods

- `Void OnClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29side
public class Act29sideEntryTuningPlugin : TemplateActivityCommonPlugin, IHotfixable
{
	private String m_actId; // 0x28
	private Boolean m_hasInited; // 0x30
	private String m_toastDesc; // 0x38
	private Status m_cachedCurrStatus; // 0x40
	private String m_cachedCrossDayTrackId; // 0x48
	private TrackPointViewProperty m_trackPointLockProp; // 0x50
	private TrackPointViewProperty m_trackPointProp; // 0x58
	private UICommonTrackPoint _trackPointLock; // 0x60
	private UIActTrackPoint _trackPoint; // 0x68
	private GameObject _buttonClick; // 0x70
	private Text _textUnlockDesc; // 0x78
	private GameObject _panelLocked; // 0x80
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3263940 VA: 0x759587b940
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x3263cec VA: 0x759587bcec
	public Void OnClick() { }
	// RVA: 0x3263c0c VA: 0x759587bc0c
	private Void _InitIfNot() { }
	// RVA: 0x3263ea8 VA: 0x759587bea8
	public Void .ctor() { }
}
```