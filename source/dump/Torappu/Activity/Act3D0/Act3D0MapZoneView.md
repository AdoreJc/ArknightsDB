# Act3D0MapZoneView

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `String _zoneId`

- `GameObject _panelUnlocked`

- `GameObject _panelLocked`

- `GameObject _panelSelected`

- `GameObject _panelTrackPoint`


## Methods

- `Void OnZoneDescModelUpdated(List`1, String)`

- `Void EventOnBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0MapZoneView : MonoBehaviour, IHotfixable
{
	public String _zoneId; // 0x18
	private GameObject _panelUnlocked; // 0x20
	private GameObject _panelLocked; // 0x28
	private GameObject _panelSelected; // 0x30
	private GameObject _panelTrackPoint; // 0x38
	public Action`1 onZoneClicked; // 0x40
	private static DelegateBridge __Hotfix0_OnZoneDescModelUpdated; // 0x0
	private static DelegateBridge __Hotfix0_EventOnBtnClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3234d1c VA: 0x759584cd1c
	public Void OnZoneDescModelUpdated(List`1 descModels, String selectedZoneId) { }
	// RVA: 0x32350cc VA: 0x759584d0cc
	public Void EventOnBtnClicked() { }
	// RVA: 0x3235154 VA: 0x759584d154
	public Void .ctor() { }
}
```