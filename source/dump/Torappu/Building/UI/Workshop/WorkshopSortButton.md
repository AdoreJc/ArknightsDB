# WorkshopSortButton

**Namespace:** `Torappu.Building.UI.Workshop`


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
// Namespace : Torappu.Building.UI.Workshop
public class WorkshopSortButton : MonoBehaviour
{
	private GameObject[] _inactiveObjects; // 0x18
	private GameObject[] _ascentObjects; // 0x20
	private GameObject[] _descentObjects; // 0x28
	private Action`1 onButtonPressed; // 0x30
	private State m_currentState; // 0x38

	public State currentState { get; }

	// RVA: 0x3d74420 VA: 0x759638c420
	public Void add_onButtonPressed(Action`1 value) { }
	// RVA: 0x3d744d0 VA: 0x759638c4d0
	public Void remove_onButtonPressed(Action`1 value) { }
	// RVA: 0x3d74580 VA: 0x759638c580
	public Void SetState(State state) { }
	// RVA: 0x3d746c0 VA: 0x759638c6c0
	public State get_currentState() { }
	// RVA: 0x3d746c8 VA: 0x759638c6c8
	public Void OnButtonPressed() { }
	// RVA: 0x3d746e8 VA: 0x759638c6e8
	public Void .ctor() { }
}
```