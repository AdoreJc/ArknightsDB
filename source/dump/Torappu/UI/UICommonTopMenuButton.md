# UICommonTopMenuButton

**Namespace:** `Torappu.UI`


## Fields

- `UIRouteTarget _routeTarget`

- `Button m_button`


## Properties

- `Button button`


## Methods

- `Void set_onRouteButtonClicked(Action`1)`

- `Button get_button()`

- `Void Start()`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICommonTopMenuButton : MonoBehaviour
{
	private UIRouteTarget _routeTarget; // 0x18
	private Action`1 <onRouteButtonClicked>k__BackingField; // 0x20
	private Button m_button; // 0x28

	private Action`1 onRouteButtonClicked { get; set; }
	protected Button button { get; }

	// RVA: 0x2246000 VA: 0x759485e000
	private Action`1 get_onRouteButtonClicked() { }
	// RVA: 0x2246008 VA: 0x759485e008
	public Void set_onRouteButtonClicked(Action`1 value) { }
	// RVA: 0x2246010 VA: 0x759485e010
	protected Button get_button() { }
	// RVA: 0x22460b8 VA: 0x759485e0b8
	protected Void Start() { }
	// RVA: 0x22461a8 VA: 0x759485e1a8
	public Void EventOnClicked() { }
	// RVA: 0x22461e8 VA: 0x759485e1e8
	public Void .ctor() { }
}
```