# MarshalByValueComponent

**Namespace:** `System.ComponentModel`


## Fields

- `ISite _site`

- `EventHandlerList _events`


## Properties

- `EventHandlerList Events`


## Methods

- `Void add_Disposed(EventHandler)`

- `Void remove_Disposed(EventHandler)`

- `EventHandlerList get_Events()`

- `Void Dispose()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class MarshalByValueComponent : IComponent, IDisposable, IServiceProvider
{
	private static readonly Object s_eventDisposed; // 0x0
	private ISite _site; // 0x10
	private EventHandlerList _events; // 0x18

	protected EventHandlerList Events { get; }
	public virtual ISite Site { get; set; }
	public virtual IContainer Container { get; }
	public virtual Boolean DesignMode { get; }

	// RVA: 0x63c7d10 VA: 0x75989dfd10
	public Void .ctor() { }
	// RVA: 0x63c7d18 VA: 0x75989dfd18
	protected override Void Finalize() { }
	// RVA: 0x63c7db8 VA: 0x75989dfdb8
	public Void add_Disposed(EventHandler value) { }
	// RVA: 0x63c7eb8 VA: 0x75989dfeb8
	public Void remove_Disposed(EventHandler value) { }
	// RVA: 0x63c7e40 VA: 0x75989dfe40
	protected EventHandlerList get_Events() { }
	// RVA: 0x63c7f40 VA: 0x75989dff40
	public virtual ISite get_Site() { }
	// RVA: 0x63c7f48 VA: 0x75989dff48
	public virtual Void set_Site(ISite value) { }
	// RVA: 0x63c7f50 VA: 0x75989dff50
	public Void Dispose() { }
	// RVA: 0x63c7fbc VA: 0x75989dffbc
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x63c824c VA: 0x75989e024c
	public virtual IContainer get_Container() { }
	// RVA: 0x63c82fc VA: 0x75989e02fc
	public virtual Object GetService(Type service) { }
	// RVA: 0x63c83b0 VA: 0x75989e03b0
	public virtual Boolean get_DesignMode() { }
	// RVA: 0x63c8460 VA: 0x75989e0460
	public override String ToString() { }
	// RVA: 0x63c8590 VA: 0x75989e0590
	private static Void .cctor() { }
}
```