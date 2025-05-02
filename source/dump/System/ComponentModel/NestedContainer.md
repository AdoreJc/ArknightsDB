# NestedContainer

**Namespace:** `System.ComponentModel`


## Properties

- `IComponent Owner`


## Methods

- `IComponent get_Owner()`

- `Void OnOwnerDisposed(Object, EventArgs)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class NestedContainer : Container, INestedContainer, IContainer, IDisposable
{
	private readonly IComponent <Owner>k__BackingField; // 0x40

	public IComponent Owner { get; }
	protected virtual String OwnerName { get; }

	// RVA: 0x63ce65c VA: 0x75989e665c
	public Void .ctor(IComponent owner) { }
	// RVA: 0x63ce838 VA: 0x75989e6838
	public IComponent get_Owner() { }
	// RVA: 0x63ce840 VA: 0x75989e6840
	protected virtual String get_OwnerName() { }
	// RVA: 0x63ceab4 VA: 0x75989e6ab4
	protected override ISite CreateSite(IComponent component, String name) { }
	// RVA: 0x63cebdc VA: 0x75989e6bdc
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x63cf00c VA: 0x75989e700c
	protected override Object GetService(Type service) { }
	// RVA: 0x63cf154 VA: 0x75989e7154
	private Void OnOwnerDisposed(Object sender, EventArgs e) { }
}
```