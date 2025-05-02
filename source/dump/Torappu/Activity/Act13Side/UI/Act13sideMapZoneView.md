# Act13sideMapZoneView

**Namespace:** `Torappu.Activity.Act13Side.UI`


## Fields

- `ActZoneClass _zoneClass`

- `GameObject _panelSelected`

- `GameObject _panelIcon`

- `CanvasGroup _canvasGroupIcon`

- `GameObject _panelLocked`

- `GameObject _panelNew`

- `UIStringEvent _onClicked`

- `RectTransform _trackPointContainer`

- `GameObject _trackPointPrefab`

- `Boolean m_hasInited`

- `GameObject m_trackPoint`

- `String m_zoneId`


## Properties

- `ActZoneClass zoneClass`


## Methods

- `ActZoneClass get_zoneClass()`

- `Void Render(Act13sideZoneDescViewModel, Boolean)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side.UI
public class Act13sideMapZoneView : MonoBehaviour, IHotfixable
{
	private ActZoneClass _zoneClass; // 0x18
	private GameObject _panelSelected; // 0x20
	private GameObject _panelIcon; // 0x28
	private CanvasGroup _canvasGroupIcon; // 0x30
	private GameObject _panelLocked; // 0x38
	private GameObject _panelNew; // 0x40
	private UIStringEvent _onClicked; // 0x48
	private RectTransform _trackPointContainer; // 0x50
	private GameObject _trackPointPrefab; // 0x58
	private Boolean m_hasInited; // 0x60
	private GameObject m_trackPoint; // 0x68
	private String m_zoneId; // 0x70
	private static DelegateBridge __Hotfix0_get_zoneClass; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public ActZoneClass zoneClass { get; }

	// RVA: 0x3447fac VA: 0x7595a5ffac
	public ActZoneClass get_zoneClass() { }
	// RVA: 0x3448014 VA: 0x7595a60014
	public Void Render(Act13sideZoneDescViewModel viewModel, Boolean isSelected) { }
	// RVA: 0x3448224 VA: 0x7595a60224
	protected virtual Void _InitIfNot() { }
	// RVA: 0x344835c VA: 0x7595a6035c
	public Void EventOnClicked() { }
	// RVA: 0x34483fc VA: 0x7595a603fc
	public Void .ctor() { }
}
```