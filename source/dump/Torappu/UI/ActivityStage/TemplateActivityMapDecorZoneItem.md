# TemplateActivityMapDecorZoneItem

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `String _zoneId`

- `GameObject _panelSelected`

- `GameObject _panelUnselected`

- `GameObject _panelIcon`

- `CanvasGroup _canvasGroupIcon`

- `GameObject _panelLocked`

- `GameObject _panelNew`

- `UIStringEvent _onClicked`

- `RectTransform _trackPointContainer`

- `GameObject _trackPointPrefab`

- `Boolean _playStagePushAudio`

- `Boolean m_hasInited`

- `GameObject m_trackPoint`


## Properties

- `String zoneId`


## Methods

- `String get_zoneId()`

- `Void Render(ZoneViewModel, Boolean)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityMapDecorZoneItem : MonoBehaviour, IHotfixable
{
	private String _zoneId; // 0x18
	private GameObject _panelSelected; // 0x20
	private GameObject _panelUnselected; // 0x28
	private GameObject _panelIcon; // 0x30
	private CanvasGroup _canvasGroupIcon; // 0x38
	private GameObject _panelLocked; // 0x40
	private GameObject _panelNew; // 0x48
	private UIStringEvent _onClicked; // 0x50
	private RectTransform _trackPointContainer; // 0x58
	private GameObject _trackPointPrefab; // 0x60
	private Boolean _playStagePushAudio; // 0x68
	private Boolean m_hasInited; // 0x69
	private GameObject m_trackPoint; // 0x70
	private static DelegateBridge __Hotfix0_get_zoneId; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String zoneId { get; }

	// RVA: 0x3097594 VA: 0x75956af594
	public String get_zoneId() { }
	// RVA: 0x30975fc VA: 0x75956af5fc
	public Void Render(ZoneViewModel viewModel, Boolean isSelected) { }
	// RVA: 0x30977c8 VA: 0x75956af7c8
	protected virtual Void _InitIfNot() { }
	// RVA: 0x3097900 VA: 0x75956af900
	public Void EventOnClicked() { }
	// RVA: 0x3097a3c VA: 0x75956afa3c
	public Void .ctor() { }
}
```