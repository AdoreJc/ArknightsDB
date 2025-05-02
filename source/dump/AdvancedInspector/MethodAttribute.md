# MethodAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `MethodDisplay display`

- `String undoMessageOnClick`

- `Boolean isCoroutine`


## Properties

- `MethodDisplay Display`

- `String UndoMessageOnClick`

- `Boolean IsCoroutine`


## Methods

- `MethodDisplay get_Display()`

- `Void set_Display(MethodDisplay)`

- `String get_UndoMessageOnClick()`

- `Void set_UndoMessageOnClick(String)`

- `Boolean get_IsCoroutine()`

- `Void set_IsCoroutine(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class MethodAttribute : Attribute
{
	private MethodDisplay display; // 0x10
	private String undoMessageOnClick; // 0x18
	private Boolean isCoroutine; // 0x20

	public MethodDisplay Display { get; set; }
	public String UndoMessageOnClick { get; set; }
	public Boolean IsCoroutine { get; set; }

	// RVA: 0x1b18244 VA: 0x7594130244
	public MethodDisplay get_Display() { }
	// RVA: 0x1b1824c VA: 0x759413024c
	public Void set_Display(MethodDisplay value) { }
	// RVA: 0x1b18254 VA: 0x7594130254
	public String get_UndoMessageOnClick() { }
	// RVA: 0x1b1825c VA: 0x759413025c
	public Void set_UndoMessageOnClick(String value) { }
	// RVA: 0x1b18264 VA: 0x7594130264
	public Boolean get_IsCoroutine() { }
	// RVA: 0x1b1826c VA: 0x759413026c
	public Void set_IsCoroutine(Boolean value) { }
	// RVA: 0x1b18278 VA: 0x7594130278
	public Void .ctor() { }
	// RVA: 0x1b182d0 VA: 0x75941302d0
	public Void .ctor(MethodDisplay display) { }
	// RVA: 0x1b1833c VA: 0x759413033c
	public Void .ctor(Boolean isCoroutine) { }
	// RVA: 0x1b1841c VA: 0x759413041c
	public Void .ctor(String undoMessageOnClick) { }
	// RVA: 0x1b18394 VA: 0x7594130394
	public Void .ctor(Boolean isCoroutine, String undoMessageOnClick) { }
}
```