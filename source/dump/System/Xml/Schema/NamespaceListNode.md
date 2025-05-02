# NamespaceListNode

**Namespace:** `System.Xml.Schema`


## Fields

- `NamespaceList namespaceList`

- `Object particle`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class NamespaceListNode : SyntaxTreeNode
{
	protected NamespaceList namespaceList; // 0x10
	protected Object particle; // 0x18

	public override Boolean IsNullable { get; }

	// RVA: 0x62d461c VA: 0x75988ec61c
	public Void .ctor(NamespaceList namespaceList, Object particle) { }
	// RVA: 0x62d4660 VA: 0x75988ec660
	public virtual ICollection GetResolvedSymbols(SymbolsDictionary symbols) { }
	// RVA: 0x62d4680 VA: 0x75988ec680
	public override Void ExpandTree(InteriorNode parent, SymbolsDictionary symbols, Positions positions) { }
	// RVA: 0x62d4b54 VA: 0x75988ecb54
	public override Void ConstructPos(BitSet firstpos, BitSet lastpos, BitSet[] followpos) { }
	// RVA: 0x62d4b94 VA: 0x75988ecb94
	public override Boolean get_IsNullable() { }
}
```