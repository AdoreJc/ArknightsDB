# Act24sideEntryZoneButtonView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `String _zoneId`

- `Button _buttonSelf`

- `CanvasGroup _normGroup`

- `GameObject _panelStageLock`

- `GameObject _panelTimeout`

- `GameObject _panelTimeLock`

- `UICommonTrackPoint _trackPointNew`

- `UIStringEvent _onClicked`

- `Single _alphaAccess`

- `Boolean m_hasInited`

- `GameObject m_trackPoint`

- `TrackPointViewProperty m_trackPointNew`


## Properties

- `String zoneId`


## Methods

- `String get_zoneId()`

- `Void _InitIfNot()`

- `Void Render(ZoneViewModel)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideEntryZoneButtonView : MonoBehaviour, IHotfixable
{
	private String _zoneId; // 0x18
	private Button _buttonSelf; // 0x20
	private CanvasGroup _normGroup; // 0x28
	private GameObject _panelStageLock; // 0x30
	private GameObject _panelTimeout; // 0x38
	private GameObject _panelTimeLock; // 0x40
	private UICommonTrackPoint _trackPointNew; // 0x48
	private UIStringEvent _onClicked; // 0x50
	private Single _alphaAccess; // 0x58
	private Boolean m_hasInited; // 0x5c
	private GameObject m_trackPoint; // 0x60
	private TrackPointViewProperty m_trackPointNew; // 0x68
	private static DelegateBridge __Hotfix0_get_zoneId; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String zoneId { get; }

	// RVA: 0x329e0b8 VA: 0x75958b60b8
	public String get_zoneId() { }
	// RVA: 0x329e3a8 VA: 0x75958b63a8
	private Void _InitIfNot() { }
	// RVA: 0x329e120 VA: 0x75958b6120
	public Void Render(ZoneViewModel viewModel) { }
	// RVA: 0x329e450 VA: 0x75958b6450
	public Void EventOnClicked() { }
	// RVA: 0x329e4f0 VA: 0x75958b64f0
	public Void .ctor() { }
}
```