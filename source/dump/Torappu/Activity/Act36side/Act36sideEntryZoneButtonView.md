# Act36sideEntryZoneButtonView

**Namespace:** `Torappu.Activity.Act36side`


## Fields

- `String _zoneId`

- `Button _buttonSelf`

- `GameObject _imageNew`

- `GameObject _panelAccessible`

- `GameObject _panelTimeout`

- `GameObject _panelLocked`

- `GameObject _panelTimeLocked`

- `GameObject _panelStageLocked`

- `UIStringEvent _onClicked`

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
// Namespace : Torappu.Activity.Act36side
public class Act36sideEntryZoneButtonView : MonoBehaviour, IHotfixable
{
	private String _zoneId; // 0x18
	private Button _buttonSelf; // 0x20
	private GameObject _imageNew; // 0x28
	private GameObject _panelAccessible; // 0x30
	private GameObject _panelTimeout; // 0x38
	private GameObject _panelLocked; // 0x40
	private GameObject _panelTimeLocked; // 0x48
	private GameObject _panelStageLocked; // 0x50
	private UIStringEvent _onClicked; // 0x58
	private Boolean m_hasInited; // 0x60
	private GameObject m_trackPoint; // 0x68
	private static DelegateBridge __Hotfix0_get_zoneId; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public String zoneId { get; }

	// RVA: 0x3244a50 VA: 0x759585ca50
	public String get_zoneId() { }
	// RVA: 0x3244ab8 VA: 0x759585cab8
	public Void Render(ZoneViewModel viewModel, Boolean isAllTimeout) { }
	// RVA: 0x3244d94 VA: 0x759585cd94
	public Void EventOnClicked() { }
	// RVA: 0x3244ee4 VA: 0x759585cee4
	public Void .ctor() { }
}
```