# Site

**Namespace:** ` `


## Fields

- `IComponent component`

- `Container container`

- `String name`


## Properties

- `IComponent Component`

- `IContainer Container`

- `Boolean DesignMode`

- `String Name`


## Methods

- `IComponent get_Component()`

- `IContainer get_Container()`

- `Object GetService(Type)`

- `Boolean get_DesignMode()`

- `String get_Name()`

- `Void set_Name(String)`


## Dump
```C#
// Dll : System.dll
// Namespace : 
private class Site : ISite, IServiceProvider
{
	private IComponent component; // 0x10
	private Container container; // 0x18
	private String name; // 0x20

	public IComponent Component { get; }
	public IContainer Container { get; }
	public Boolean DesignMode { get; }
	public String Name { get; set; }

	// RVA: 0x63de098 VA: 0x75989f6098
	internal Void .ctor(IComponent component, Container container, String name) { }
	// RVA: 0x63dec0c VA: 0x75989f6c0c
	public IComponent get_Component() { }
	// RVA: 0x63dec14 VA: 0x75989f6c14
	public IContainer get_Container() { }
	// RVA: 0x63dec1c VA: 0x75989f6c1c
	public Object GetService(Type service) { }
	// RVA: 0x63dece0 VA: 0x75989f6ce0
	public Boolean get_DesignMode() { }
	// RVA: 0x63dece8 VA: 0x75989f6ce8
	public String get_Name() { }
	// RVA: 0x63decf0 VA: 0x75989f6cf0
	public Void set_Name(String value) { }
}
```