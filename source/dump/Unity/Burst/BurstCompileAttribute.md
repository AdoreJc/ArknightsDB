# BurstCompileAttribute

**Namespace:** `Unity.Burst`


## Fields

- `FloatMode <FloatMode>k__BackingField`

- `FloatPrecision <FloatPrecision>k__BackingField`


## Properties

- `FloatMode FloatMode`

- `FloatPrecision FloatPrecision`

- `Boolean CompileSynchronously`


## Methods

- `Void set_FloatMode(FloatMode)`

- `Void set_FloatPrecision(FloatPrecision)`

- `Void set_CompileSynchronously(Boolean)`


## Dump
```C#
// Dll : Unity.Burst.dll
// Namespace : Unity.Burst
public class BurstCompileAttribute : Attribute
{
	private FloatMode <FloatMode>k__BackingField; // 0x10
	private FloatPrecision <FloatPrecision>k__BackingField; // 0x14
	internal Nullable`1 _compileSynchronously; // 0x18
	private String[] <Options>k__BackingField; // 0x20

	public FloatMode FloatMode { set; }
	public FloatPrecision FloatPrecision { set; }
	public Boolean CompileSynchronously { set; }
	internal String[] Options { set; }

	// RVA: 0x67e7600 VA: 0x7598dff600
	public Void set_FloatMode(FloatMode value) { }
	// RVA: 0x67e7608 VA: 0x7598dff608
	public Void set_FloatPrecision(FloatPrecision value) { }
	// RVA: 0x67e7610 VA: 0x7598dff610
	public Void set_CompileSynchronously(Boolean value) { }
	// RVA: 0x67e7678 VA: 0x7598dff678
	internal Void set_Options(String[] value) { }
	// RVA: 0x67e7680 VA: 0x7598dff680
	public Void .ctor() { }
	// RVA: 0x67e7688 VA: 0x7598dff688
	public Void .ctor(FloatPrecision floatPrecision, FloatMode floatMode) { }
}
```