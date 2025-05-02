# ClimbTowerControllerBridge

**Namespace:** ` `


## Fields

- `ClimbTowerController m_closure`


## Properties

- `String towerId`

- `StateEngine stateEngine`

- `Boolean isTutorialTower`

- `Boolean squadEditStateForceOpen`

- `UIPage bindPage`


## Methods

- `String get_towerId()`

- `StateEngine get_stateEngine()`

- `Boolean get_isTutorialTower()`

- `Boolean get_squadEditStateForceOpen()`

- `Void set_squadEditStateForceOpen(Boolean)`

- `UIPage get_bindPage()`

- `Void SetEffectActive(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ClimbTowerControllerBridge
{
	private ClimbTowerController m_closure; // 0x10

	public EventPool`1 eventPool { get; }
	public String towerId { get; }
	public StateEngine stateEngine { get; }
	public Boolean isTutorialTower { get; }
	public List`1 predefinedCharList { get; }
	public Boolean squadEditStateForceOpen { get; set; }
	public UIPage bindPage { get; }

	// RVA: 0x2c61978 VA: 0x7595279978
	public Void .ctor(ClimbTowerController closure) { }
	// RVA: 0x2c62224 VA: 0x759527a224
	public EventPool`1 get_eventPool() { }
	// RVA: 0x2c62240 VA: 0x759527a240
	public String get_towerId() { }
	// RVA: 0x2c6225c VA: 0x759527a25c
	public StateEngine get_stateEngine() { }
	// RVA: 0x2c62278 VA: 0x759527a278
	public Boolean get_isTutorialTower() { }
	// RVA: 0x2c62294 VA: 0x759527a294
	public List`1 get_predefinedCharList() { }
	// RVA: 0x2c622b0 VA: 0x759527a2b0
	public Boolean get_squadEditStateForceOpen() { }
	// RVA: 0x2c622c8 VA: 0x759527a2c8
	public Void set_squadEditStateForceOpen(Boolean value) { }
	// RVA: 0x2c622e4 VA: 0x759527a2e4
	public UIPage get_bindPage() { }
	// RVA: 0x2c62300 VA: 0x759527a300
	public Void SetEffectActive(Boolean show) { }
}
```