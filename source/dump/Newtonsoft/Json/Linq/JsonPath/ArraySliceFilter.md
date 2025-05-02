# ArraySliceFilter

**Namespace:** `Newtonsoft.Json.Linq.JsonPath`


## Methods

- `Void set_Start(Nullable`1)`

- `Void set_End(Nullable`1)`

- `Void set_Step(Nullable`1)`

- `Boolean IsValid(Int32, Int32, Boolean)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Linq.JsonPath
internal class ArraySliceFilter : PathFilter
{
	private Nullable`1 <Start>k__BackingField; // 0x10
	private Nullable`1 <End>k__BackingField; // 0x18
	private Nullable`1 <Step>k__BackingField; // 0x20

	public Nullable`1 Start { get; set; }
	public Nullable`1 End { get; set; }
	public Nullable`1 Step { get; set; }

	// RVA: 0x619ece8 VA: 0x75987b6ce8
	public Nullable`1 get_Start() { }
	// RVA: 0x619ecf0 VA: 0x75987b6cf0
	public Void set_Start(Nullable`1 value) { }
	// RVA: 0x619ecf8 VA: 0x75987b6cf8
	public Nullable`1 get_End() { }
	// RVA: 0x619ed00 VA: 0x75987b6d00
	public Void set_End(Nullable`1 value) { }
	// RVA: 0x619ed08 VA: 0x75987b6d08
	public Nullable`1 get_Step() { }
	// RVA: 0x619ed10 VA: 0x75987b6d10
	public Void set_Step(Nullable`1 value) { }
	// RVA: 0x619ed18 VA: 0x75987b6d18
	public override IEnumerable`1 ExecuteFilter(IEnumerable`1 current, Boolean errorWhenNoMatch) { }
	// RVA: 0x619edf4 VA: 0x75987b6df4
	private Boolean IsValid(Int32 index, Int32 stopIndex, Boolean positiveStep) { }
	// RVA: 0x619ee0c VA: 0x75987b6e0c
	public Void .ctor() { }
}
```