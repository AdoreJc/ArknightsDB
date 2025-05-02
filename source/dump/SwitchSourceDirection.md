# SwitchSourceDirection

**Namespace:** ` `


## Fields

- `TNodeBase rightNodes`

- `TNodeBase leftNodes`

- `TNodeBase upNodes`

- `TNodeBase downNodes`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SwitchSourceDirection : TNodeBase
{
	public TNodeBase rightNodes; // 0x60
	public TNodeBase leftNodes; // 0x68
	public TNodeBase upNodes; // 0x70
	public TNodeBase downNodes; // 0x78

	public override TNodeBaseData Data { get; set; }

	// RVA: 0x1fedf98 VA: 0x7594605f98
	public override TNodeBaseData get_Data() { }
	// RVA: 0x1fee018 VA: 0x7594606018
	public override Void set_Data(TNodeBaseData value) { }
	// RVA: 0x1fee020 VA: 0x7594606020
	public override TNodeBaseData SerializeData() { }
	// RVA: 0x1fee0ac VA: 0x75946060ac
	public Void .ctor() { }
}
```