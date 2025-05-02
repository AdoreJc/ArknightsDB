# TemplateActivityEntryZoneButtonView

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `String _zoneId`

- `Button _buttonSelf`

- `Text _textInfo`

- `Text _textExtraInfo`

- `GameObject _imageNew`

- `GameObject _panelAccessible`

- `GameObject _panelTimeout`

- `GameObject _panelLocked`

- `UIStringEvent _onClicked`

- `RectTransform _trackPointContainer`

- `GameObject _trackPointPrefab`

- `UICommonTrackPoint _trackPointNew`

- `Boolean _playStagePushAudio`

- `Boolean m_hasInited`

- `GameObject m_trackPoint`

- `TrackPointViewProperty m_trackPointNew`


## Properties

- `String zoneId`


## Methods

- `String get_zoneId()`

- `Void _InitIfNot()`

- `Void Render(ZoneViewModel, Boolean)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityEntryZoneButtonView : MonoBehaviour, IHotfixable
{
	private String _zoneId; // 0x18
	private Button _buttonSelf; // 0x20
	private Text _textInfo; // 0x28
	private Text _textExtraInfo; // 0x30
	private GameObject _imageNew; // 0x38
	private GameObject _panelAccessible; // 0x40
	private GameObject _panelTimeout; // 0x48
	private GameObject _panelLocked; // 0x50
	private UIStringEvent _onClicked; // 0x58
	private RectTransform _trackPointContainer; // 0x60
	private GameObject _trackPointPrefab; // 0x68
	private UICommonTrackPoint _trackPointNew; // 0x70
	private Boolean _playStagePushAudio; // 0x78
	private Boolean m_hasInited; // 0x79
	private GameObject m_trackPoint; // 0x80
	private TrackPointViewProperty m_trackPointNew; // 0x88
	private static DelegateBridge __Hotfix0_get_zoneId; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String zoneId { get; }

	// RVA: 0x3096174 VA: 0x75956ae174
	public String get_zoneId() { }
	// RVA: 0x30961dc VA: 0x75956ae1dc
	private Void _InitIfNot() { }
	// RVA: 0x3096340 VA: 0x75956ae340
	public Void Render(ZoneViewModel viewModel, Boolean isAllTimeout) { }
	// RVA: 0x30969c4 VA: 0x75956ae9c4
	public Void EventOnClicked() { }
	// RVA: 0x3096b0c VA: 0x75956aeb0c
	public Void .ctor() { }
}
```