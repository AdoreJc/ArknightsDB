# AVGQuickPlay

**Namespace:** `Torappu.AVG`


## Fields

- `GameObject _slider`

- `GameObject _speedBtn`

- `Image _sliderFill`

- `Int32 _holdTime`

- `RectTransform _speedBtnBG`

- `CanvasGroup _btnsCanvasGroup`

- `DateTime m_startTime`

- `State m_state`

- `Int32 m_speed`


## Properties

- `State state`


## Methods

- `State get_state()`

- `Void OnDragAction(Vector2)`

- `Void SetSpeedBtn(String)`

- `Void _SetSpeedBtn()`

- `Void SetStatus(Boolean, Int32)`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGQuickPlay : MonoBehaviour
{
	private const Single X_POS; // 0x0
	private const Single DEFAULT_HEIGHT; // 0x0
	private const Single SMALL_HEIGHT; // 0x0
	private GameObject _slider; // 0x18
	private GameObject _speedBtn; // 0x20
	private Image _sliderFill; // 0x28
	private Int32 _holdTime; // 0x30
	private AVGQuickPlayBtn[] _speedBtns; // 0x38
	private RectTransform _speedBtnBG; // 0x40
	private CanvasGroup _btnsCanvasGroup; // 0x48
	private DateTime m_startTime; // 0x50
	private State m_state; // 0x58
	private Int32 m_speed; // 0x5c

	public State state { get; }

	// RVA: 0x3e72928 VA: 0x759648a928
	public State get_state() { }
	// RVA: 0x3e72930 VA: 0x759648a930
	public Void OnDragAction(Vector2 pos) { }
	// RVA: 0x3e72adc VA: 0x759648aadc
	public Void SetSpeedBtn(String name) { }
	// RVA: 0x3e729ec VA: 0x759648a9ec
	private Void _SetSpeedBtn() { }
	// RVA: 0x3e72b94 VA: 0x759648ab94
	public Void SetStatus(Boolean flag, Int32 pos) { }
	// RVA: 0x3e72cd8 VA: 0x759648acd8
	private Void Update() { }
	// RVA: 0x3e730e4 VA: 0x759648b0e4
	public Void .ctor() { }
}
```