# Act17sideEntryZoneButtonView

**Namespace:** `Torappu.Activity.Act17side`


## Fields

- `String _zoneId`

- `UIStringEvent _onClicked`

- `Text _textInfo`

- `Button _buttonSelf`

- `GameObject _imgNew`

- `GameObject _panelAccessiable`

- `GameObject _panelTimeout`

- `GameObject _panelLocked`

- `RectTransform _trackPointContainer`

- `GameObject _trackPointPrefab`

- `Text _textProgress`

- `GameObject _panelComplete`

- `Image _progressBar`

- `Boolean m_hasInited`

- `GameObject m_trackPoint`


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
// Namespace : Torappu.Activity.Act17side
public class Act17sideEntryZoneButtonView : MonoBehaviour, IHotfixable
{
	private String _zoneId; // 0x18
	private UIStringEvent _onClicked; // 0x20
	private Text _textInfo; // 0x28
	private Button _buttonSelf; // 0x30
	private GameObject _imgNew; // 0x38
	private GameObject _panelAccessiable; // 0x40
	private GameObject _panelTimeout; // 0x48
	private GameObject _panelLocked; // 0x50
	private RectTransform _trackPointContainer; // 0x58
	private GameObject _trackPointPrefab; // 0x60
	private Text _textProgress; // 0x68
	private GameObject _panelComplete; // 0x70
	private Image _progressBar; // 0x78
	private Boolean m_hasInited; // 0x80
	private GameObject m_trackPoint; // 0x88
	private static DelegateBridge __Hotfix0_get_zoneId; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String zoneId { get; }

	// RVA: 0x341c078 VA: 0x7595a34078
	public String get_zoneId() { }
	// RVA: 0x341c0e0 VA: 0x7595a340e0
	private Void _InitIfNot() { }
	// RVA: 0x341c218 VA: 0x7595a34218
	public Void Render(ZoneViewModel viewModel, Boolean isAllTimeout) { }
	// RVA: 0x341d110 VA: 0x7595a35110
	public Void EventOnClicked() { }
	// RVA: 0x341d1bc VA: 0x7595a351bc
	public Void .ctor() { }
}
```