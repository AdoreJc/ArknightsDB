# DIYSortButton

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `State m_currentState`


## Properties

- `State currentState`


## Methods

- `Void add_onButtonPressed(Action`1)`

- `Void remove_onButtonPressed(Action`1)`

- `Void SetState(State)`

- `State get_currentState()`

- `Void OnButtonPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYSortButton : MonoBehaviour
{
	private GameObject[] _inactiveObjects; // 0x18
	private GameObject[] _ascentObjects; // 0x20
	private GameObject[] _descentObjects; // 0x28
	private Action`1 onButtonPressed; // 0x30
	private State m_currentState; // 0x38

	public State currentState { get; }

	// RVA: 0x380c648 VA: 0x7595e24648
	public Void add_onButtonPressed(Action`1 value) { }
	// RVA: 0x380c6f8 VA: 0x7595e246f8
	public Void remove_onButtonPressed(Action`1 value) { }
	// RVA: 0x380c7a8 VA: 0x7595e247a8
	public Void SetState(State state) { }
	// RVA: 0x380c8e8 VA: 0x7595e248e8
	public State get_currentState() { }
	// RVA: 0x380c8f0 VA: 0x7595e248f0
	public Void OnButtonPressed() { }
	// RVA: 0x380c910 VA: 0x7595e24910
	public Void .ctor() { }
}
```