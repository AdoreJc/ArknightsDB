# Heap

**Namespace:** ` `


## Properties

- `Int32 count`

- `Boolean isEmpty`


## Methods

- `Int32 get_count()`

- `Boolean get_isEmpty()`

- `Void Push(InternalNode)`

- `InternalNode Pop()`

- `InternalNode Peek()`

- `Boolean Update(InternalNode)`

- `Void Clear()`

- `Boolean Contains(InternalNode)`

- `Void PushOrUpdate(InternalNode)`

- `Void _Up(Int32)`

- `Void _Down(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class Heap
{
	private List`1 m_list; // 0x10
	private HashSet`1 m_hashSet; // 0x18

	public Int32 count { get; }
	public Boolean isEmpty { get; }

	// RVA: 0x3782f74 VA: 0x7595d9af74
	public Int32 get_count() { }
	// RVA: 0x3782884 VA: 0x7595d9a884
	public Boolean get_isEmpty() { }
	// RVA: 0x37821a4 VA: 0x7595d9a1a4
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x3782508 VA: 0x7595d9a508
	public Void Push(InternalNode node) { }
	// RVA: 0x37825d4 VA: 0x7595d9a5d4
	public InternalNode Pop() { }
	// RVA: 0x3783288 VA: 0x7595d9b288
	public InternalNode Peek() { }
	// RVA: 0x3783324 VA: 0x7595d9b324
	public Boolean Update(InternalNode node) { }
	// RVA: 0x37822c0 VA: 0x7595d9a2c0
	public Void Clear() { }
	// RVA: 0x3783360 VA: 0x7595d9b360
	public Boolean Contains(InternalNode node) { }
	// RVA: 0x378285c VA: 0x7595d9a85c
	public Void PushOrUpdate(InternalNode node) { }
	// RVA: 0x3782fc0 VA: 0x7595d9afc0
	private Void _Up(Int32 index) { }
	// RVA: 0x37830e4 VA: 0x7595d9b0e4
	private Void _Down(Int32 index) { }
}
```