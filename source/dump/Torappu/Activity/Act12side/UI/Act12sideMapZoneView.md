# Act12sideMapZoneView

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `ActZoneClass _zoneClass`

- `GameObject _objIcon`

- `GameObject _objSelected`

- `GameObject _objLocked`

- `Single _normalWidth`

- `Single _selectedWidth`

- `Single _lockWidth`

- `LayoutElement _zoneLayout`

- `UIStringEvent _onClicked`

- `GameObject _objNew`

- `RectTransform _trackPointContainer`

- `String m_zoneId`

- `Boolean m_hasInited`

- `GameObject m_trackPoint`


## Properties

- `ActZoneClass zoneClass`


## Methods

- `ActZoneClass get_zoneClass()`

- `Void Render(Act12sideZoneDescViewModel, Boolean)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideMapZoneView : MonoBehaviour, IHotfixable
{
	private ActZoneClass _zoneClass; // 0x18
	private GameObject _objIcon; // 0x20
	private GameObject _objSelected; // 0x28
	private GameObject _objLocked; // 0x30
	private Single _normalWidth; // 0x38
	private Single _selectedWidth; // 0x3c
	private Single _lockWidth; // 0x40
	private LayoutElement _zoneLayout; // 0x48
	private UIStringEvent _onClicked; // 0x50
	protected GameObject _objNew; // 0x58
	private RectTransform _trackPointContainer; // 0x60
	private String m_zoneId; // 0x68
	protected Boolean m_hasInited; // 0x70
	private GameObject m_trackPoint; // 0x78
	private static DelegateBridge __Hotfix0_get_zoneClass; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public ActZoneClass zoneClass { get; }

	// RVA: 0x3464080 VA: 0x7595a7c080
	public ActZoneClass get_zoneClass() { }
	// RVA: 0x34640e8 VA: 0x7595a7c0e8
	public Void Render(Act12sideZoneDescViewModel viewModel, Boolean isSelected) { }
	// RVA: 0x3464308 VA: 0x7595a7c308
	protected virtual Void _InitIfNot() { }
	// RVA: 0x346444c VA: 0x7595a7c44c
	public Void EventOnClicked() { }
	// RVA: 0x34644ec VA: 0x7595a7c4ec
	public Void .ctor() { }
}
```