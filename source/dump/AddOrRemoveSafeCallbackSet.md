# AddOrRemoveSafeCallbackSet

**Namespace:** ` `


## Fields

- `UInt16 m_iterCounter`


## Methods

- `Void Add(EventCallbackDelegate)`

- `Void Remove(EventCallbackDelegate)`

- `Void Emit(Object)`

- `Void Reset()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
protected class AddOrRemoveSafeCallbackSet
{
	private UInt16 m_iterCounter; // 0x10
	private HashSet`1 m_internalSet; // 0x18
	private List`1 m_pendingAddOrRemove; // 0x20


	// RVA: 0x678d83c VA: 0x7598da583c
	public Void Add(EventCallbackDelegate cb) { }
	// RVA: 0x678cef4 VA: 0x7598da4ef4
	public Void Remove(EventCallbackDelegate cb) { }
	// RVA: 0x678d960 VA: 0x7598da5960
	public Void Emit(Object arg) { }
	// RVA: 0x678d29c VA: 0x7598da529c
	public Void Reset() { }
	// RVA: 0x678d4a8 VA: 0x7598da54a8
	public Void .ctor() { }
}
```