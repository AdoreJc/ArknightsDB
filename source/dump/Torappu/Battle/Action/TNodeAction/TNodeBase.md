# TNodeBase

**Namespace:** `Torappu.Battle.Action.TNodeAction`


## Fields

- `TNodeBase from`

- `TNodeBase next`

- `ActionNode _action`

- `TNodeBaseData _data`

- `String <ID>k__BackingField`

- `Boolean <guiInited>k__BackingField`


## Properties

- `ActionNode Action`

- `String ID`

- `Boolean guiInited`


## Methods

- `ActionNode get_Action()`

- `Void set_Action(ActionNode)`

- `String get_ID()`

- `Void set_ID(String)`

- `Boolean get_guiInited()`

- `Void set_guiInited(Boolean)`

- `Boolean <Init>b__20_0(Node)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Action.TNodeAction
public class TNodeBase : Node
{
	public TNodeBase from; // 0x30
	public TNodeBase next; // 0x38
	private ActionNode _action; // 0x40
	protected TNodeBaseData _data; // 0x48
	private String <ID>k__BackingField; // 0x50
	private Boolean <guiInited>k__BackingField; // 0x58

	public ActionNode Action { get; set; }
	public virtual TNodeBaseData Data { get; set; }
	public String ID { get; set; }
	public Boolean guiInited { get; set; }

	// RVA: 0x1feeb74 VA: 0x7594606b74
	public ActionNode get_Action() { }
	// RVA: 0x1feeb7c VA: 0x7594606b7c
	public Void set_Action(ActionNode value) { }
	// RVA: 0x1feeb84 VA: 0x7594606b84
	public virtual TNodeBaseData get_Data() { }
	// RVA: 0x1feebfc VA: 0x7594606bfc
	public virtual Void set_Data(TNodeBaseData value) { }
	// RVA: 0x1feec04 VA: 0x7594606c04
	public String get_ID() { }
	// RVA: 0x1feec0c VA: 0x7594606c0c
	private Void set_ID(String value) { }
	// RVA: 0x1feec14 VA: 0x7594606c14
	public Boolean get_guiInited() { }
	// RVA: 0x1feec1c VA: 0x7594606c1c
	public Void set_guiInited(Boolean value) { }
	// RVA: 0x1feec28 VA: 0x7594606c28
	public virtual ActionNode SerializeAction() { }
	// RVA: 0x1feec30 VA: 0x7594606c30
	public virtual TNodeBaseData SerializeData() { }
	// RVA: 0x1feecbc VA: 0x7594606cbc
	protected override Void Init() { }
	// RVA: 0x1fef1c8 VA: 0x75946071c8
	public override Object GetValue(NodePort port) { }
	// RVA: 0x1fef1d0 VA: 0x75946071d0
	public static Type GetTNodeType(TNodeBaseData nodeData) { }
	// RVA: 0x1fec4a4 VA: 0x75946044a4
	public Void .ctor() { }
	// RVA: 0x1fef34c VA: 0x759460734c
	private Boolean <Init>b__20_0(Node n) { }
}
```