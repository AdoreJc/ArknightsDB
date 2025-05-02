# HomeCheckInCountDownView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Text _textCountDown`

- `GameObject _panelBtnNormal`

- `GameObject _panelBtnAlreadyCheckIn`

- `GameObject _panelBtnUnclickable`

- `CountDownTask m_countDownTask`


## Methods

- `Void _ProcessCountDown()`

- `Int64 _GetRemainSeconds()`

- `Void _OnTimeTick(TickValue)`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCheckInCountDownView : DataBinder`1, IHotfixable
{
	private Text _textCountDown; // 0x20
	private GameObject _panelBtnNormal; // 0x28
	private GameObject _panelBtnAlreadyCheckIn; // 0x30
	private GameObject _panelBtnUnclickable; // 0x38
	private CountDownTask m_countDownTask; // 0x40
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__ProcessCountDown; // 0x8
	private static DelegateBridge __Hotfix0__GetRemainSeconds; // 0x10
	private static DelegateBridge __Hotfix0__OnTimeTick; // 0x18
	private static DelegateBridge __Hotfix0_Update; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x282f414 VA: 0x7594e47414
	public override Void OnValueChanged(HomeCheckInProperty property) { }
	// RVA: 0x282f530 VA: 0x7594e47530
	private Void _ProcessCountDown() { }
	// RVA: 0x282f708 VA: 0x7594e47708
	private Int64 _GetRemainSeconds() { }
	// RVA: 0x282f7c0 VA: 0x7594e477c0
	private Void _OnTimeTick(TickValue value) { }
	// RVA: 0x282f95c VA: 0x7594e4795c
	private Void Update() { }
	// RVA: 0x282f9d8 VA: 0x7594e479d8
	public Void .ctor() { }
}
```