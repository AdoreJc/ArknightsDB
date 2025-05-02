# Act12sideEntryZoneView

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `ActZoneClass _zoneClass`

- `Button _btnZone`

- `GameObject _goNewSign`

- `RectTransform _trackPointContainer`

- `Text _textLocked`

- `GameObject _normalPartGo`

- `GameObject _lockPartGo`

- `GameObject _timeoutPartGo`

- `Act12sideZoneDescViewModel m_viewModel`

- `Boolean m_hasInited`

- `GameObject m_trackPoint`


## Properties

- `ActZoneClass zoneClass`


## Methods

- `ActZoneClass get_zoneClass()`

- `Void set_onZoneClick(Action`1)`

- `Void Render(Act12sideZoneDescViewModel)`

- `Void _InitIfNot()`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideEntryZoneView : MonoBehaviour, IHotfixable
{
	private ActZoneClass _zoneClass; // 0x18
	private Button _btnZone; // 0x20
	private GameObject _goNewSign; // 0x28
	private RectTransform _trackPointContainer; // 0x30
	private Text _textLocked; // 0x38
	private GameObject _normalPartGo; // 0x40
	private GameObject _lockPartGo; // 0x48
	private GameObject _timeoutPartGo; // 0x50
	private GameObject[] _animObjs; // 0x58
	private Act12sideZoneDescViewModel m_viewModel; // 0x60
	private Boolean m_hasInited; // 0x68
	private GameObject m_trackPoint; // 0x70
	private Action`1 <onZoneClick>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_zoneClass; // 0x0
	private static DelegateBridge __Hotfix0_get_onZoneClick; // 0x8
	private static DelegateBridge __Hotfix0_set_onZoneClick; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public ActZoneClass zoneClass { get; }
	private Action`1 onZoneClick { get; set; }

	// RVA: 0x3462bfc VA: 0x7595a7abfc
	public ActZoneClass get_zoneClass() { }
	// RVA: 0x3463338 VA: 0x7595a7b338
	private Action`1 get_onZoneClick() { }
	// RVA: 0x3463224 VA: 0x7595a7b224
	public Void set_onZoneClick(Action`1 value) { }
	// RVA: 0x3462c64 VA: 0x7595a7ac64
	public Void Render(Act12sideZoneDescViewModel viewModel) { }
	// RVA: 0x34633a0 VA: 0x7595a7b3a0
	private Void _InitIfNot() { }
	// RVA: 0x34634e4 VA: 0x7595a7b4e4
	public Void EventOnClick() { }
	// RVA: 0x3463630 VA: 0x7595a7b630
	public Void .ctor() { }
}
```