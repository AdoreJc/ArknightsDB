# Act25sideEntryZoneButtonView

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `String _zoneId`

- `Button _buttonSelf`

- `Text _textInfo`

- `GameObject _imageNew`

- `GameObject _panelAccessible`

- `GameObject _panelTimeout`

- `GameObject _panelLocked`

- `UIStringEvent _onClicked`

- `RectTransform _trackPointContainer`

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
// Namespace : Torappu.Activity.Act25side
public class Act25sideEntryZoneButtonView : MonoBehaviour, IHotfixable
{
	private String _zoneId; // 0x18
	private Button _buttonSelf; // 0x20
	private Text _textInfo; // 0x28
	private GameObject _imageNew; // 0x30
	private GameObject _panelAccessible; // 0x38
	private GameObject _panelTimeout; // 0x40
	private GameObject _panelLocked; // 0x48
	private UIStringEvent _onClicked; // 0x50
	private RectTransform _trackPointContainer; // 0x58
	private Boolean m_hasInited; // 0x60
	private GameObject m_trackPoint; // 0x68
	private static DelegateBridge __Hotfix0_get_zoneId; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String zoneId { get; }

	// RVA: 0x3270250 VA: 0x7595888250
	public String get_zoneId() { }
	// RVA: 0x32702b8 VA: 0x75958882b8
	private Void _InitIfNot() { }
	// RVA: 0x32703fc VA: 0x75958883fc
	public Void Render(ZoneViewModel viewModel, Boolean isAllTimeout) { }
	// RVA: 0x3270964 VA: 0x7595888964
	public Void EventOnClicked() { }
	// RVA: 0x3270a10 VA: 0x7595888a10
	public Void .ctor() { }
}
```