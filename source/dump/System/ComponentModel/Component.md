# Component

**Namespace:** `System.ComponentModel`


## Fields

- `ISite site`

- `EventHandlerList events`


## Properties

- `EventHandlerList Events`

- `IContainer Container`

- `Boolean DesignMode`


## Methods

- `Void add_Disposed(EventHandler)`

- `Void remove_Disposed(EventHandler)`

- `EventHandlerList get_Events()`

- `Void Dispose()`

- `IContainer get_Container()`

- `Boolean get_DesignMode()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class Component : MarshalByRefObject, IComponent, IDisposable
{
	private static readonly Object EventDisposed; // 0x0
	private ISite site; // 0x18
	private EventHandlerList events; // 0x20

	protected virtual Boolean CanRaiseEvents { get; }
	internal Boolean CanRaiseEventsInternal { get; }
	protected EventHandlerList Events { get; }
	public virtual ISite Site { get; set; }
	public IContainer Container { get; }
	protected Boolean DesignMode { get; }

	// RVA: 0x63dd050 VA: 0x75989f5050
	protected override Void Finalize() { }
	// RVA: 0x63dd0f4 VA: 0x75989f50f4
	protected virtual Boolean get_CanRaiseEvents() { }
	// RVA: 0x63dd0fc VA: 0x75989f50fc
	internal Boolean get_CanRaiseEventsInternal() { }
	// RVA: 0x63dd108 VA: 0x75989f5108
	public Void add_Disposed(EventHandler value) { }
	// RVA: 0x63dd214 VA: 0x75989f5214
	public Void remove_Disposed(EventHandler value) { }
	// RVA: 0x63dd194 VA: 0x75989f5194
	protected EventHandlerList get_Events() { }
	// RVA: 0x63dd2a0 VA: 0x75989f52a0
	public virtual ISite get_Site() { }
	// RVA: 0x63dd2a8 VA: 0x75989f52a8
	public virtual Void set_Site(ISite value) { }
	// RVA: 0x63dd2b0 VA: 0x75989f52b0
	public Void Dispose() { }
	// RVA: 0x63dd320 VA: 0x75989f5320
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x63dd62c VA: 0x75989f562c
	public IContainer get_Container() { }
	// RVA: 0x63dd6dc VA: 0x75989f56dc
	protected virtual Object GetService(Type service) { }
	// RVA: 0x63dd790 VA: 0x75989f5790
	protected Boolean get_DesignMode() { }
	// RVA: 0x63dd840 VA: 0x75989f5840
	public override String ToString() { }
	// RVA: 0x63dd970 VA: 0x75989f5970
	public Void .ctor() { }
	// RVA: 0x63dd978 VA: 0x75989f5978
	private static Void .cctor() { }
}
```