# VisualElementFocusChangeTarget

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Focusable <target>k__BackingField`


## Properties

- `Focusable target`


## Methods

- `Focusable get_target()`

- `Void set_target(Focusable)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class VisualElementFocusChangeTarget : FocusChangeDirection
{
	private static readonly ObjectPool`1 Pool; // 0x0
	private Focusable <target>k__BackingField; // 0x18

	public Focusable target { get; set; }

	// RVA: 0x6994b00 VA: 0x7598facb00
	public static VisualElementFocusChangeTarget GetPooled(Focusable target) { }
	// RVA: 0x6994b98 VA: 0x7598facb98
	protected override Void Dispose() { }
	// RVA: 0x6994c28 VA: 0x7598facc28
	internal override Void ApplyTo(FocusController focusController, Focusable f) { }
	// RVA: 0x6994c4c VA: 0x7598facc4c
	public Void .ctor() { }
	// RVA: 0x6994cec VA: 0x7598faccec
	public Focusable get_target() { }
	// RVA: 0x6994cf4 VA: 0x7598faccf4
	private Void set_target(Focusable value) { }
	// RVA: 0x6994cfc VA: 0x7598faccfc
	private static Void .cctor() { }
}
```