# Act21sideEntryMapButtonPlugin

**Namespace:** `Torappu.Activity.Act21side`


## Fields

- `UICommonTrackPoint _trackPointMap`

- `GameObject _trackPointNew`

- `UICommonTrackPoint _trackPointOpera`

- `UICommonTrackPoint _trackPointLike`

- `GameObject _timeoutPanelMap`

- `GameObject _timeoutPanelOpera`

- `Text _textInfoMapNew`

- `Text _textInfoMapClose`

- `Text _textInfoOperaClose`

- `Button _buttonMap`

- `Button _buttonOpera`

- `Boolean m_hasInited`

- `TrackPointViewProperty m_trackPointMap`

- `TrackPointViewProperty m_trackPointOpera`

- `TrackPointViewProperty m_trackPointLike`


## Methods

- `Void _InitIfNot()`

- `Void EventOnMapBtnClicked()`

- `Void EventOnCommentBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act21side
public class Act21sideEntryMapButtonPlugin : TemplateActivityCommonPlugin
{
	private UICommonTrackPoint _trackPointMap; // 0x28
	private GameObject _trackPointNew; // 0x30
	private UICommonTrackPoint _trackPointOpera; // 0x38
	private UICommonTrackPoint _trackPointLike; // 0x40
	private GameObject _timeoutPanelMap; // 0x48
	private GameObject _timeoutPanelOpera; // 0x50
	private Text _textInfoMapNew; // 0x58
	private Text _textInfoMapClose; // 0x60
	private Text _textInfoOperaClose; // 0x68
	private Button _buttonMap; // 0x70
	private Button _buttonOpera; // 0x78
	private Boolean m_hasInited; // 0x80
	private TrackPointViewProperty m_trackPointMap; // 0x88
	private TrackPointViewProperty m_trackPointOpera; // 0x90
	private TrackPointViewProperty m_trackPointLike; // 0x98
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x8
	private static DelegateBridge __Hotfix0_EventOnMapBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnCommentBtnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x32e60a0 VA: 0x75958fe0a0
	private Void _InitIfNot() { }
	// RVA: 0x32e620c VA: 0x75958fe20c
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x32e6520 VA: 0x75958fe520
	public Void EventOnMapBtnClicked() { }
	// RVA: 0x32e673c VA: 0x75958fe73c
	public Void EventOnCommentBtnClicked() { }
	// RVA: 0x32e68bc VA: 0x75958fe8bc
	public Void .ctor() { }
}
```