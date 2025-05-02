# RedSpotButtonView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Image _redSpot`

- `Boolean _highlightedOnAwake`

- `Button m_button`

- `Boolean m_highlighted`


## Properties

- `Boolean interactable`

- `Boolean highlighted`


## Methods

- `Boolean get_interactable()`

- `Void set_interactable(Boolean)`

- `Boolean get_highlighted()`

- `Void set_highlighted(Boolean)`

- `Void _UpdateRedSpot()`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class RedSpotButtonView : MonoBehaviour
{
	private Image _redSpot; // 0x18
	private Boolean _highlightedOnAwake; // 0x20
	private Button m_button; // 0x28
	private Boolean m_highlighted; // 0x30

	public Boolean interactable { get; set; }
	public Boolean highlighted { get; set; }

	// RVA: 0x2849344 VA: 0x7594e61344
	public Boolean get_interactable() { }
	// RVA: 0x2849360 VA: 0x7594e61360
	public Void set_interactable(Boolean value) { }
	// RVA: 0x28493d0 VA: 0x7594e613d0
	public Boolean get_highlighted() { }
	// RVA: 0x2849404 VA: 0x7594e61404
	public Void set_highlighted(Boolean value) { }
	// RVA: 0x284938c VA: 0x7594e6138c
	private Void _UpdateRedSpot() { }
	// RVA: 0x2849410 VA: 0x7594e61410
	private Void Awake() { }
	// RVA: 0x2849478 VA: 0x7594e61478
	public Void .ctor() { }
}
```