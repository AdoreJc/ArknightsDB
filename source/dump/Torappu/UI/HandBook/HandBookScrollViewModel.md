# HandBookScrollViewModel

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Boolean m_zoomFlag`

- `Single m_zoomValue`

- `Boolean m_dirtyFlag`

- `Vector2 m_scrollPos`

- `Boolean m_onScroll`

- `HandBookCardView SelectedCardData`

- `Boolean lastSelected`

- `Boolean quickAnim`

- `String m_selectedChar`


## Properties

- `Boolean zoomFlag`

- `Single zoomValue`

- `Boolean dirtyFlag`

- `Vector2 scrollPos`

- `Boolean onScroll`

- `String selectedChar`


## Methods

- `Boolean get_zoomFlag()`

- `Void set_zoomFlag(Boolean)`

- `Single get_zoomValue()`

- `Void set_zoomValue(Single)`

- `Boolean get_dirtyFlag()`

- `Void set_dirtyFlag(Boolean)`

- `Vector2 get_scrollPos()`

- `Void set_scrollPos(Vector2)`

- `Boolean get_onScroll()`

- `Void set_onScroll(Boolean)`

- `String get_selectedChar()`

- `Void set_selectedChar(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookScrollViewModel
{
	private Boolean m_zoomFlag; // 0x10
	private Single m_zoomValue; // 0x14
	private Boolean m_dirtyFlag; // 0x18
	private Vector2 m_scrollPos; // 0x1c
	private Boolean m_onScroll; // 0x24
	public HandBookCardView SelectedCardData; // 0x28
	public Boolean lastSelected; // 0x30
	public Boolean quickAnim; // 0x31
	private String m_selectedChar; // 0x38

	public Boolean zoomFlag { get; set; }
	public Single zoomValue { get; set; }
	public Boolean dirtyFlag { get; set; }
	public Vector2 scrollPos { get; set; }
	public Boolean onScroll { get; set; }
	public String selectedChar { get; set; }

	// RVA: 0x2ec04e8 VA: 0x75954d84e8
	public Boolean get_zoomFlag() { }
	// RVA: 0x2ec04f0 VA: 0x75954d84f0
	public Void set_zoomFlag(Boolean value) { }
	// RVA: 0x2eb2704 VA: 0x75954ca704
	public Single get_zoomValue() { }
	// RVA: 0x2eb6a90 VA: 0x75954cea90
	public Void set_zoomValue(Single value) { }
	// RVA: 0x2ec04fc VA: 0x75954d84fc
	public Boolean get_dirtyFlag() { }
	// RVA: 0x2ec0504 VA: 0x75954d8504
	public Void set_dirtyFlag(Boolean value) { }
	// RVA: 0x2ec0510 VA: 0x75954d8510
	public Vector2 get_scrollPos() { }
	// RVA: 0x2ec0518 VA: 0x75954d8518
	public Void set_scrollPos(Vector2 value) { }
	// RVA: 0x2ec0520 VA: 0x75954d8520
	public Boolean get_onScroll() { }
	// RVA: 0x2ec0528 VA: 0x75954d8528
	public Void set_onScroll(Boolean value) { }
	// RVA: 0x2ec0534 VA: 0x75954d8534
	public String get_selectedChar() { }
	// RVA: 0x2eb2ae4 VA: 0x75954caae4
	public Void set_selectedChar(String value) { }
	// RVA: 0x2eb6994 VA: 0x75954ce994
	public Void .ctor() { }
}
```