# Act10D5EntryZoneView

**Namespace:** `Torappu.Activity.Act10D5`


## Fields

- `String _zoneId`

- `Button _buttonSelf`

- `Text _textInfo`

- `GameObject _imageNew`

- `GameObject _panelAccessible`

- `GameObject _panelTimeout`

- `GameObject _panelLocked`

- `UIStringEvent _onClicked`


## Properties

- `String zoneId`


## Methods

- `String get_zoneId()`

- `Void Render(Act10D5ZoneDescViewModel, Boolean)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act10D5
public class Act10D5EntryZoneView : MonoBehaviour, IHotfixable
{
	private String _zoneId; // 0x18
	private Button _buttonSelf; // 0x20
	private Text _textInfo; // 0x28
	private GameObject _imageNew; // 0x30
	private GameObject _panelAccessible; // 0x38
	private GameObject _panelTimeout; // 0x40
	private GameObject _panelLocked; // 0x48
	private UIStringEvent _onClicked; // 0x50
	private static DelegateBridge __Hotfix0_get_zoneId; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public String zoneId { get; }

	// RVA: 0x3486334 VA: 0x7595a9e334
	public String get_zoneId() { }
	// RVA: 0x348639c VA: 0x7595a9e39c
	public Void Render(Act10D5ZoneDescViewModel viewModel, Boolean isAllTimeout) { }
	// RVA: 0x3486ab8 VA: 0x7595a9eab8
	public Void EventOnClicked() { }
	// RVA: 0x3486b64 VA: 0x7595a9eb64
	public Void .ctor() { }
}
```