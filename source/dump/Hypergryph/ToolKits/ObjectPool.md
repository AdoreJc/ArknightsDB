# ObjectPool

**Namespace:** `Hypergryph.ToolKits`


## Properties

- `Int32 countInactive`


## Methods

- `Int32 get_countInactive()`

- `Object Get()`

- `Void Release(Object)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Hypergryph.ToolKits
internal class ObjectPool
{
	private const Int32 DEFAULT_POOL_SIZE; // 0x0
	private readonly Stack`1 m_Stack; // 0x10
	private readonly Func`1 m_ActionNew; // 0x18
	private readonly Action`1 m_ActionOnGet; // 0x20
	private readonly Action`1 m_ActionOnRelease; // 0x28
	private readonly Int32 m_poolSize; // 0x30

	public Int32 countInactive { get; }

	// RVA: 0x66ca024 VA: 0x7598ce2024
	public Int32 get_countInactive() { }
	// RVA: 0x66ca06c VA: 0x7598ce206c
	public Void .ctor(Func`1 actionNew, Int32 poolSize, Action`1 actionOnGet, Action`1 actionOnRelease) { }
	// RVA: 0x66ca1b0 VA: 0x7598ce21b0
	public Object Get() { }
	// RVA: 0x66ca258 VA: 0x7598ce2258
	public Void Release(Object element) { }
}
```