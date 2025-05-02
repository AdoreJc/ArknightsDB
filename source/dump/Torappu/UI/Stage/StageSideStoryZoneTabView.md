# StageSideStoryZoneTabView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `String _zoneId`

- `GameObject _panelUnlocked`

- `GameObject _panelLocked`

- `GameObject _panelSelected`

- `GameObject _panelUnselected`

- `Text _zoneName`

- `StageSideStoryZoneTabViewPlugin m_tabViewPlugin`

- `Boolean m_hasInited`

- `ZoneViewModel m_zoneViewModel`


## Methods

- `Void OnZoneDescModelUpdated(List`1, String)`

- `Void EventOnBtnClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageSideStoryZoneTabView : MonoBehaviour, IHotfixable
{
	public String _zoneId; // 0x18
	private GameObject _panelUnlocked; // 0x20
	private GameObject _panelLocked; // 0x28
	private GameObject _panelSelected; // 0x30
	private GameObject _panelUnselected; // 0x38
	private Text _zoneName; // 0x40
	private StageSideStoryZoneTabViewPlugin m_tabViewPlugin; // 0x48
	private Boolean m_hasInited; // 0x50
	public Action`1 onZoneClicked; // 0x58
	private ZoneViewModel m_zoneViewModel; // 0x60
	private static DelegateBridge __Hotfix0_OnZoneDescModelUpdated; // 0x0
	private static DelegateBridge __Hotfix0_EventOnBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f19b0c VA: 0x7595531b0c
	public Void OnZoneDescModelUpdated(List`1 models, String selectedZoneId) { }
	// RVA: 0x2f1a0cc VA: 0x75955320cc
	public Void EventOnBtnClicked() { }
	// RVA: 0x2f1a020 VA: 0x7595532020
	private Void _InitIfNot() { }
	// RVA: 0x2f1a1a8 VA: 0x75955321a8
	public Void .ctor() { }
}
```