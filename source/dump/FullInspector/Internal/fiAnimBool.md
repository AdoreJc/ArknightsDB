# fiAnimBool

**Namespace:** `FullInspector.Internal`


## Fields

- `Single m_Value`


## Properties

- `Single faded`


## Methods

- `Single get_faded()`

- `Single Fade(Single, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector.Internal
public class fiAnimBool : fiBaseAnimValue`1
{
	private Single m_Value; // 0x2c

	public Single faded { get; }

	// RVA: 0x34d5ea4 VA: 0x7595aedea4
	public Single get_faded() { }
	// RVA: 0x34d95e0 VA: 0x7595af15e0
	public Void .ctor() { }
	// RVA: 0x34d5e20 VA: 0x7595aede20
	public Void .ctor(Boolean value) { }
	// RVA: 0x34d962c VA: 0x7595af162c
	protected override Boolean GetValue() { }
	// RVA: 0x34d96d4 VA: 0x7595af16d4
	public Single Fade(Single from, Single to) { }
}
```