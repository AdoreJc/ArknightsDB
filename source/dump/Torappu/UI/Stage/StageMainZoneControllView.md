# StageMainZoneControllView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `TwoStateToggle _leftBar`

- `TwoStateToggle _rightBar`

- `Text _leftActiveText`

- `Text _leftUnActiveText`

- `Text _rightActiveText`

- `Text _rightUnActiveText`

- `Text _leftActiveTitle`

- `Text _leftUnActiveTitle`

- `Text _rightActiveTitle`

- `Text _rightUnActiveTitle`

- `Text _middleTitle`

- `Text _middleText`

- `CanvasGroup _canvasGroup`

- `StageStateBean _stateBean`

- `StageZoneSelectState _state`

- `UIStringEvent _eventZoneClick`

- `String m_cacheLeft`

- `String m_cacheRight`

- `FadeSwitchTween m_fadeSwitch`


## Methods

- `Void OnLeft()`

- `Void OnRight()`

- `Void _SetVisibility(Boolean)`

- `Boolean _CheckZoneRetroValid(ZoneViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageMainZoneControllView : DataBinder`1
{
	private TwoStateToggle _leftBar; // 0x20
	private TwoStateToggle _rightBar; // 0x28
	private Text _leftActiveText; // 0x30
	private Text _leftUnActiveText; // 0x38
	private Text _rightActiveText; // 0x40
	private Text _rightUnActiveText; // 0x48
	private Text _leftActiveTitle; // 0x50
	private Text _leftUnActiveTitle; // 0x58
	private Text _rightActiveTitle; // 0x60
	private Text _rightUnActiveTitle; // 0x68
	private Text _middleTitle; // 0x70
	private Text _middleText; // 0x78
	private CanvasGroup _canvasGroup; // 0x80
	private StageStateBean _stateBean; // 0x88
	private StageZoneSelectState _state; // 0x90
	private UIStringEvent _eventZoneClick; // 0x98
	private String m_cacheLeft; // 0xa0
	private String m_cacheRight; // 0xa8
	private FadeSwitchTween m_fadeSwitch; // 0xb0
	private static DelegateBridge __Hotfix0_OnLeft; // 0x0
	private static DelegateBridge __Hotfix0_OnRight; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__SetVisibility; // 0x18
	private static DelegateBridge __Hotfix0__CheckZoneRetroValid; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2fa6bf8 VA: 0x75955bebf8
	public Void OnLeft() { }
	// RVA: 0x2fa6ca0 VA: 0x75955beca0
	public Void OnRight() { }
	// RVA: 0x2fa6d48 VA: 0x75955bed48
	public override Void OnValueChanged(ZoneViewProperty property) { }
	// RVA: 0x2fa7290 VA: 0x75955bf290
	private Void _SetVisibility(Boolean isVisible) { }
	// RVA: 0x2fa7390 VA: 0x75955bf390
	private Boolean _CheckZoneRetroValid(ZoneViewModel zone) { }
	// RVA: 0x2fa7530 VA: 0x75955bf530
	public Void .ctor() { }
}
```