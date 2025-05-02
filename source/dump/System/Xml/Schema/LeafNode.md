# LeafNode

**Namespace:** `System.Xml.Schema`


## Fields

- `Int32 pos`


## Properties

- `Int32 Pos`


## Methods

- `Int32 get_Pos()`

- `Void set_Pos(Int32)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class LeafNode : SyntaxTreeNode
{
	private Int32 pos; // 0x10

	public Int32 Pos { get; set; }
	public override Boolean IsNullable { get; }

	// RVA: 0x62d4598 VA: 0x75988ec598
	public Void .ctor(Int32 pos) { }
	// RVA: 0x62d45c0 VA: 0x75988ec5c0
	public Int32 get_Pos() { }
	// RVA: 0x62d45c8 VA: 0x75988ec5c8
	public Void set_Pos(Int32 value) { }
	// RVA: 0x62d45d0 VA: 0x75988ec5d0
	public override Void ExpandTree(InteriorNode parent, SymbolsDictionary symbols, Positions positions) { }
	// RVA: 0x62d45d4 VA: 0x75988ec5d4
	public override Void ConstructPos(BitSet firstpos, BitSet lastpos, BitSet[] followpos) { }
	// RVA: 0x62d4614 VA: 0x75988ec614
	public override Boolean get_IsNullable() { }
}
```