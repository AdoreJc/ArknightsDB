# CollectionChangeEventArgs

**Namespace:** `System.ComponentModel`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class CollectionChangeEventArgs : EventArgs
{
	private readonly CollectionChangeAction <Action>k__BackingField; // 0x10
	private readonly Object <Element>k__BackingField; // 0x18

	public virtual CollectionChangeAction Action { get; }
	public virtual Object Element { get; }

	// RVA: 0x63b70c4 VA: 0x75989cf0c4
	public Void .ctor(CollectionChangeAction action, Object element) { }
	// RVA: 0x63b7140 VA: 0x75989cf140
	public virtual CollectionChangeAction get_Action() { }
	// RVA: 0x63b7148 VA: 0x75989cf148
	public virtual Object get_Element() { }
}
```