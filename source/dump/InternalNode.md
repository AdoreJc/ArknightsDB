# InternalNode

**Namespace:** ` `


## Fields

- `Node node`

- `Int32 distance`

- `Int32 fScore`

- `InternalNode prevNode`

- `Int32 heapIndex`


## Methods

- `Int32 CompareTo(InternalNode)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class InternalNode : IComparable`1
{
	public Node node; // 0x10
	public Int32 distance; // 0x18
	public Int32 fScore; // 0x1c
	public InternalNode prevNode; // 0x20
	public Int32 heapIndex; // 0x28


	// RVA: 0x3783380 VA: 0x7595d9b380
	public Int32 CompareTo(InternalNode other) { }
	// RVA: 0x378289c VA: 0x7595d9a89c
	public Void .ctor(Node node) { }
}
```