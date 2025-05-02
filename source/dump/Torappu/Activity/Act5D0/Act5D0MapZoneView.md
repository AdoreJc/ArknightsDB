# Act5D0MapZoneView

**Namespace:** `Torappu.Activity.Act5D0`


## Fields

- `String _zoneId`

- `Image _panelContent`

- `GameObject _panelLocked`

- `GameObject _panelSelected`

- `GameObject _panelTrackPoint`

- `Color _lockColor`


## Methods

- `Void OnZoneDescModelUpdated(List`1, String)`

- `Void EventOnBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D0
public class Act5D0MapZoneView : MonoBehaviour, IHotfixable
{
	public String _zoneId; // 0x18
	private Image _panelContent; // 0x20
	private GameObject _panelLocked; // 0x28
	private GameObject _panelSelected; // 0x30
	private GameObject _panelTrackPoint; // 0x38
	private Color _lockColor; // 0x40
	public Action`1 onZoneClicked; // 0x50
	private static DelegateBridge __Hotfix0_OnZoneDescModelUpdated; // 0x0
	private static DelegateBridge __Hotfix0_EventOnBtnClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31bf7fc VA: 0x75957d77fc
	public Void OnZoneDescModelUpdated(List`1 descModels, String selectedZoneId) { }
	// RVA: 0x31bfc14 VA: 0x75957d7c14
	public Void EventOnBtnClicked() { }
	// RVA: 0x31bfc9c VA: 0x75957d7c9c
	public Void .ctor() { }
}
```