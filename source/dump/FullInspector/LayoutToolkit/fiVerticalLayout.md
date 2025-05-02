# fiVerticalLayout

**Namespace:** `FullInspector.LayoutToolkit`


## Methods

- `Void Add(fiLayout)`

- `Void Add(String, fiLayout)`

- `Void Add(String, Single)`

- `Void Add(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector.LayoutToolkit
public class fiVerticalLayout : fiLayout, IEnumerable
{
	private List`1 _items; // 0x10

	public override Single Height { get; }

	// RVA: 0x34d72e4 VA: 0x7595aef2e4
	public Void Add(fiLayout rule) { }
	// RVA: 0x34d751c VA: 0x7595aef51c
	public Void Add(String sectionId, fiLayout rule) { }
	// RVA: 0x34d760c VA: 0x7595aef60c
	public Void Add(String sectionId, Single height) { }
	// RVA: 0x34d7284 VA: 0x7595aef284
	public Void Add(Single height) { }
	// RVA: 0x34d76a0 VA: 0x7595aef6a0
	public override Rect GetSectionRect(String sectionId, Rect initial) { }
	// RVA: 0x34d7810 VA: 0x7595aef810
	public override Boolean RespondsTo(String sectionId) { }
	// RVA: 0x34d78e8 VA: 0x7595aef8e8
	public override Single get_Height() { }
	// RVA: 0x34d7994 VA: 0x7595aef994
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x34d6754 VA: 0x7595aee754
	public Void .ctor() { }
}
```