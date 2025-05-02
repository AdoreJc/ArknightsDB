# TNodeBaseData

**Namespace:** ` `


## Fields

- `String _iD`

- `Vector2 _pos`


## Properties

- `String ID`


## Methods

- `String get_ID()`

- `Void set_ID(String)`

- `Void OnAfterCopy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TNodeBaseData : ICopyable
{
	private String _iD; // 0x10
	private Vector2 _pos; // 0x18
	private Dictionary`2 m_portIDPairDict; // 0x20
	private TNodePortIDPair[] _portIDPair; // 0x28

	public String ID { get; set; }
	public Dictionary`2 portIDPairDict { get; }

	// RVA: 0x1fef454 VA: 0x7594607454
	public String get_ID() { }
	// RVA: 0x1fef45c VA: 0x759460745c
	public Void set_ID(String value) { }
	// RVA: 0x1fec59c VA: 0x759460459c
	public Dictionary`2 get_portIDPairDict() { }
	// RVA: 0x1fef464 VA: 0x7594607464
	public virtual Void ParseTNode(TNodeBase node) { }
	// RVA: 0x1fecb40 VA: 0x7594604b40
	public virtual Void FetchDataRef(IDToTNodeDataActionMap nodeDataActionDict, ref List`1 output) { }
	// RVA: 0x1fef514 VA: 0x7594607514
	public virtual Void SerializeTNodeBasic(TNodeBase node) { }
	// RVA: 0x1fefa50 VA: 0x7594607a50
	public Void OnAfterCopy() { }
	// RVA: 0x1fec6c4 VA: 0x75946046c4
	public Void .ctor() { }
}
```