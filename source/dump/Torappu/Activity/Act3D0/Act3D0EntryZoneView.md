# Act3D0EntryZoneView

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `String _zoneId`

- `GameObject _panelUnlocked`

- `GameObject _panelLocked`

- `GameObject _panelTrackPoint`

- `Text _textLocked`

- `Act3D0ZoneDescModel m_cachedModel`

- `Boolean m_isInited`


## Methods

- `Void OnZoneDescModelUpdated(List`1)`

- `Void EventOnBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0EntryZoneView : MonoBehaviour, IHotfixable
{
	private String _zoneId; // 0x18
	private GameObject _panelUnlocked; // 0x20
	private GameObject _panelLocked; // 0x28
	private GameObject _panelTrackPoint; // 0x30
	private Text _textLocked; // 0x38
	public Action`1 onZoneClicked; // 0x40
	private Act3D0ZoneDescModel m_cachedModel; // 0x48
	private Boolean m_isInited; // 0x68
	private static DelegateBridge __Hotfix0_OnZoneDescModelUpdated; // 0x0
	private static DelegateBridge __Hotfix0_EventOnBtnClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3231924 VA: 0x7595849924
	public Void OnZoneDescModelUpdated(List`1 descModels) { }
	// RVA: 0x3231cfc VA: 0x7595849cfc
	public Void EventOnBtnClicked() { }
	// RVA: 0x3231d84 VA: 0x7595849d84
	public Void .ctor() { }
}
```