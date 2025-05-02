# Container

**Namespace:** `System.ComponentModel`


## Fields

- `Int32 siteCount`

- `ComponentCollection components`

- `ContainerFilterService filter`

- `Boolean checkedFilter`

- `Object syncObj`


## Methods

- `Void Dispose()`

- `Void Remove(IComponent, Boolean)`

- `Void RemoveWithoutUnsiting(IComponent)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class Container : IContainer, IDisposable
{
	private ISite[] sites; // 0x10
	private Int32 siteCount; // 0x18
	private ComponentCollection components; // 0x20
	private ContainerFilterService filter; // 0x28
	private Boolean checkedFilter; // 0x30
	private Object syncObj; // 0x38

	public virtual ComponentCollection Components { get; }

	// RVA: 0x63ddae0 VA: 0x75989f5ae0
	protected override Void Finalize() { }
	// RVA: 0x63ddb80 VA: 0x75989f5b80
	public virtual Void Add(IComponent component) { }
	// RVA: 0x63ddb90 VA: 0x75989f5b90
	public virtual Void Add(IComponent component, String name) { }
	// RVA: 0x63de020 VA: 0x75989f6020
	protected virtual ISite CreateSite(IComponent component, String name) { }
	// RVA: 0x63cf158 VA: 0x75989e7158
	public Void Dispose() { }
	// RVA: 0x63cece8 VA: 0x75989e6ce8
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x63cf0bc VA: 0x75989e70bc
	protected virtual Object GetService(Type service) { }
	// RVA: 0x63de0f8 VA: 0x75989f60f8
	public virtual ComponentCollection get_Components() { }
	// RVA: 0x63de4d4 VA: 0x75989f64d4
	public virtual Void Remove(IComponent component) { }
	// RVA: 0x63de4dc VA: 0x75989f64dc
	private Void Remove(IComponent component, Boolean preserveSite) { }
	// RVA: 0x63de7d4 VA: 0x75989f67d4
	protected Void RemoveWithoutUnsiting(IComponent component) { }
	// RVA: 0x63de7dc VA: 0x75989f67dc
	protected virtual Void ValidateName(IComponent component, String name) { }
	// RVA: 0x63ce7c4 VA: 0x75989e67c4
	public Void .ctor() { }
}
```