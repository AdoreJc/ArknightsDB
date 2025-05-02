# Act9D0EntryZoneView

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `String _zoneId`

- `Button _buttonSelf`

- `Text _textInfo`

- `GameObject _imageNew`

- `GameObject _panelAccessible`

- `GameObject _panelTimeout`

- `GameObject _panelLocked`

- `Boolean _stagePushAudio`

- `UIStringEvent _onClicked`


## Properties

- `String zoneId`


## Methods

- `Void set_onZoneClicked(Action`1)`

- `String get_zoneId()`

- `Void Render(Act9D0ZoneDescViewModel, Boolean)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0EntryZoneView : MonoBehaviour, IHotfixable
{
	private String _zoneId; // 0x18
	private Button _buttonSelf; // 0x20
	private Text _textInfo; // 0x28
	private GameObject _imageNew; // 0x30
	private GameObject _panelAccessible; // 0x38
	private GameObject _panelTimeout; // 0x40
	private GameObject _panelLocked; // 0x48
	private Boolean _stagePushAudio; // 0x50
	private UIStringEvent _onClicked; // 0x58
	private Action`1 <onZoneClicked>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_onZoneClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onZoneClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_zoneId; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onZoneClicked { get; set; }
	public String zoneId { get; }

	// RVA: 0x31a48f0 VA: 0x75957bc8f0
	private Action`1 get_onZoneClicked() { }
	// RVA: 0x31a4708 VA: 0x75957bc708
	public Void set_onZoneClicked(Action`1 value) { }
	// RVA: 0x31a4164 VA: 0x75957bc164
	public String get_zoneId() { }
	// RVA: 0x31a41cc VA: 0x75957bc1cc
	public Void Render(Act9D0ZoneDescViewModel viewModel, Boolean isAllTimeout) { }
	// RVA: 0x31a4958 VA: 0x75957bc958
	public Void EventOnClicked() { }
	// RVA: 0x31a4aa4 VA: 0x75957bcaa4
	public Void .ctor() { }
}
```