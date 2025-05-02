# Act5D0EntryZoneView

**Namespace:** `Torappu.Activity.Act5D0`


## Fields

- `String _zoneId`

- `Button _btn`

- `GameObject _notOpenLocked`

- `GameObject _timeOutLocked`

- `Text _textLocked`

- `GameObject _panelTrackPoint`

- `Act5D0ZoneDescModel m_cachedModel`

- `Boolean m_isInited`


## Methods

- `Void OnZoneDescModelUpdated(List`1)`

- `Void EventOnBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D0
public class Act5D0EntryZoneView : MonoBehaviour, IHotfixable
{
	private String _zoneId; // 0x18
	private Button _btn; // 0x20
	private GameObject _notOpenLocked; // 0x28
	private GameObject _timeOutLocked; // 0x30
	private Text _textLocked; // 0x38
	private GameObject _panelTrackPoint; // 0x40
	public Action`1 onZoneClicked; // 0x48
	private Act5D0ZoneDescModel m_cachedModel; // 0x50
	private Boolean m_isInited; // 0x70
	private static DelegateBridge __Hotfix0_OnZoneDescModelUpdated; // 0x0
	private static DelegateBridge __Hotfix0_EventOnBtnClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31bef90 VA: 0x75957d6f90
	public Void OnZoneDescModelUpdated(List`1 descModels) { }
	// RVA: 0x31bf458 VA: 0x75957d7458
	public Void EventOnBtnClicked() { }
	// RVA: 0x31bf4e0 VA: 0x75957d74e0
	public Void .ctor() { }
}
```