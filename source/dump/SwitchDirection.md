# SwitchDirection

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
public class SwitchDirection : TNodeBase
{
	public TNodeBase rightNodes; // 0x60
	public TNodeBase leftNodes; // 0x68
	public TNodeBase upNodes; // 0x70
	public TNodeBase downNodes; // 0x78

	public override TNodeBaseData Data { get; set; }

	// RVA: 0x1fed9e4 VA: 0x75946059e4
	public override TNodeBaseData get_Data() { }
	// RVA: 0x1feda64 VA: 0x7594605a64
	public override Void set_Data(TNodeBaseData value) { }
	// RVA: 0x1feda6c VA: 0x7594605a6c
	public override TNodeBaseData SerializeData() { }
	// RVA: 0x1fedaf8 VA: 0x7594605af8
	public Void .ctor() { }
}
```