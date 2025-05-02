# Act9D0MapZoneView

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `String _zoneId`

- `Text _textTitle`

- `Button _buttonSelf`

- `GameObject _imageSelected`

- `GameObject _imageIcon`

- `GameObject _panelTimeout`

- `GameObject _panelLocked`

- `UIStringEvent _onClicked`

- `Boolean _needDisableImageIcon`


## Properties

- `String zoneId`


## Methods

- `String get_zoneId()`

- `Void Render(Act9D0ZoneDescViewModel, Boolean)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0MapZoneView : MonoBehaviour, IHotfixable
{
	private String _zoneId; // 0x18
	private Text _textTitle; // 0x20
	private Button _buttonSelf; // 0x28
	private GameObject _imageSelected; // 0x30
	private GameObject _imageIcon; // 0x38
	private GameObject _panelTimeout; // 0x40
	private GameObject _panelLocked; // 0x48
	private UIStringEvent _onClicked; // 0x50
	private Boolean _needDisableImageIcon; // 0x58
	private static DelegateBridge __Hotfix0_get_zoneId; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public String zoneId { get; }

	// RVA: 0x31a5b04 VA: 0x75957bdb04
	public String get_zoneId() { }
	// RVA: 0x31a5b6c VA: 0x75957bdb6c
	public Void Render(Act9D0ZoneDescViewModel viewModel, Boolean isSelected) { }
	// RVA: 0x31a5df0 VA: 0x75957bddf0
	public Void EventOnClicked() { }
	// RVA: 0x31a5e9c VA: 0x75957bde9c
	public Void .ctor() { }
}
```