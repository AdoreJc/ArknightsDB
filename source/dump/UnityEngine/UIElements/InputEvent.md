# InputEvent

**Namespace:** `UnityEngine.UIElements`


## Fields

- `String <previousData>k__BackingField`

- `String <newData>k__BackingField`


## Properties

- `String previousData`

- `String newData`


## Methods

- `Void set_previousData(String)`

- `Void set_newData(String)`

- `Void LocalInit()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class InputEvent : EventBase`1
{
	private String <previousData>k__BackingField; // 0x80
	private String <newData>k__BackingField; // 0x88

	protected String previousData { set; }
	protected String newData { set; }

	// RVA: 0x69e2780 VA: 0x7598ffa780
	protected Void set_previousData(String value) { }
	// RVA: 0x69e2788 VA: 0x7598ffa788
	protected Void set_newData(String value) { }
	// RVA: 0x69e2790 VA: 0x7598ffa790
	protected override Void Init() { }
	// RVA: 0x69e2800 VA: 0x7598ffa800
	private Void LocalInit() { }
	// RVA: 0x69e2830 VA: 0x7598ffa830
	public static InputEvent GetPooled(String previousData, String newData) { }
	// RVA: 0x69e28d4 VA: 0x7598ffa8d4
	public Void .ctor() { }
}
```