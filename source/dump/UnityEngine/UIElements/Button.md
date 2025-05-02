# Button

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Clickable m_Clickable`


## Properties

- `Clickable clickable`


## Methods

- `Clickable get_clickable()`

- `Void set_clickable(Clickable)`

- `Void OnNavigationSubmit(NavigationSubmitEvent)`

- `Void OnKeyDown(KeyDownEvent)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class Button : TextElement
{
	public static readonly String ussClassName; // 0x0
	private Clickable m_Clickable; // 0x478
	private static readonly String NonEmptyString; // 0x8

	public Clickable clickable { get; set; }

	// RVA: 0x69a9f90 VA: 0x7598fc1f90
	public Clickable get_clickable() { }
	// RVA: 0x69a9f98 VA: 0x7598fc1f98
	public Void set_clickable(Clickable value) { }
	// RVA: 0x69aa00c VA: 0x7598fc200c
	public Void .ctor() { }
	// RVA: 0x69aa014 VA: 0x7598fc2014
	public Void .ctor(Action clickEvent) { }
	// RVA: 0x69aa1dc VA: 0x7598fc21dc
	private Void OnNavigationSubmit(NavigationSubmitEvent evt) { }
	// RVA: 0x69aa214 VA: 0x7598fc2214
	private Void OnKeyDown(KeyDownEvent evt) { }
	// RVA: 0x69aa32c VA: 0x7598fc232c
	protected internal override Vector2 DoMeasure(Single desiredWidth, MeasureMode widthMode, Single desiredHeight, MeasureMode heightMode) { }
	// RVA: 0x69aa3e8 VA: 0x7598fc23e8
	private static Void .cctor() { }
}
```