# LinkedPool

**Namespace:** `UnityEngine.UIElements.UIR`


## Fields

- `T m_PoolFirst`

- `Int32 <Count>k__BackingField`


## Properties

- `Int32 Count`


## Methods

- `Int32 get_Count()`

- `Void set_Count(Int32)`

- `Void Clear()`

- `T Get()`

- `Void Return(T)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.UIR
internal class LinkedPool`1
{
	private readonly Func`1 m_CreateFunc; // 0x0
	private readonly Action`1 m_ResetAction; // 0x0
	private readonly Int32 m_Limit; // 0x0
	private T m_PoolFirst; // 0x0
	private Int32 <Count>k__BackingField; // 0x0

	public Int32 Count { get; set; }

	// RVA: 0x VA: 0x0
	public Void .ctor(Func`1 createFunc, Action`1 resetAction, Int32 limit) { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	private Void set_Count(Int32 value) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public T Get() { }
	// RVA: 0x VA: 0x0
	public Void Return(T item) { }
}
```