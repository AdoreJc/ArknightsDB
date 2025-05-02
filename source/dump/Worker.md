# Worker

**Namespace:** ` `


## Fields

- `CustomYieldInstruction m_curWork`

- `Boolean <isCancelled>k__BackingField`

- `Boolean <isDisposed>k__BackingField`

- `Node <curNode>k__BackingField`


## Properties

- `Boolean isCancelled`

- `Boolean isDisposed`

- `Node curNode`


## Methods

- `Boolean get_isCancelled()`

- `Void set_isCancelled(Boolean)`

- `Boolean get_isDisposed()`

- `Void set_isDisposed(Boolean)`

- `Node get_curNode()`

- `Void set_curNode(Node)`

- `Boolean Cancel()`

- `Void Dispose()`

- `Void SetCurNode(Node)`

- `Boolean UpdateOnce(IWorkerUpdateOnce)`

- `Void TickInEmptyFrame()`

- `IEnumerator Work(CustomYieldInstruction)`

- `Void _InternalTick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class Worker : IDisposable
{
	private HashSet`1 m_updateOnce; // 0x10
	private List`1 m_buffer; // 0x18
	private CustomYieldInstruction m_curWork; // 0x20
	private Boolean <isCancelled>k__BackingField; // 0x28
	private Boolean <isDisposed>k__BackingField; // 0x29
	private Node <curNode>k__BackingField; // 0x30

	public Boolean isCancelled { get; set; }
	public Boolean isDisposed { get; set; }
	public Node curNode { get; set; }

	// RVA: 0x27d5158 VA: 0x7594ded158
	public Boolean get_isCancelled() { }
	// RVA: 0x27d5160 VA: 0x7594ded160
	private Void set_isCancelled(Boolean value) { }
	// RVA: 0x27d516c VA: 0x7594ded16c
	public Boolean get_isDisposed() { }
	// RVA: 0x27d5174 VA: 0x7594ded174
	private Void set_isDisposed(Boolean value) { }
	// RVA: 0x27d5180 VA: 0x7594ded180
	public Node get_curNode() { }
	// RVA: 0x27d5188 VA: 0x7594ded188
	private Void set_curNode(Node value) { }
	// RVA: 0x27d3f68 VA: 0x7594debf68
	public Boolean Cancel() { }
	// RVA: 0x27d3a0c VA: 0x7594deba0c
	public Void Dispose() { }
	// RVA: 0x27d5190 VA: 0x7594ded190
	public Void SetCurNode(Node node) { }
	// RVA: 0x27d46f0 VA: 0x7594dec6f0
	public Boolean UpdateOnce(IWorkerUpdateOnce inst) { }
	// RVA: 0x27d5198 VA: 0x7594ded198
	public Void TickInEmptyFrame() { }
	// RVA: 0x27d53fc VA: 0x7594ded3fc
	public IEnumerator Work(CustomYieldInstruction work) { }
	// RVA: 0x27d519c VA: 0x7594ded19c
	private Void _InternalTick() { }
	// RVA: 0x27d54b4 VA: 0x7594ded4b4
	public Void .ctor() { }
}
```