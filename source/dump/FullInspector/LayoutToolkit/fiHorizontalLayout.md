# fiHorizontalLayout

**Namespace:** `FullInspector.LayoutToolkit`


## Fields

- `fiLayout _defaultRule`


## Properties

- `Int32 ExpandCount`

- `Single MinimumWidth`


## Methods

- `Void Add(fiLayout)`

- `Void Add(Single)`

- `Void Add(String)`

- `Void Add(String, Single)`

- `Void Add(String, fiLayout)`

- `Void Add(Single, fiLayout)`

- `Void Add(String, Single, fiLayout)`

- `Void ActualAdd(String, Single, fiExpandMode, fiLayout)`

- `Int32 get_ExpandCount()`

- `Single get_MinimumWidth()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector.LayoutToolkit
public class fiHorizontalLayout : fiLayout, IEnumerable
{
	private List`1 _items; // 0x10
	private fiLayout _defaultRule; // 0x18

	private Int32 ExpandCount { get; }
	private Single MinimumWidth { get; }
	public override Single Height { get; }

	// RVA: 0x34d6694 VA: 0x7595aee694
	public Void .ctor() { }
	// RVA: 0x34d67e4 VA: 0x7595aee7e4
	public Void .ctor(fiLayout defaultRule) { }
	// RVA: 0x34d68c4 VA: 0x7595aee8c4
	public Void Add(fiLayout rule) { }
	// RVA: 0x34d6a78 VA: 0x7595aeea78
	public Void Add(Single width) { }
	// RVA: 0x34d6ae0 VA: 0x7595aeeae0
	public Void Add(String id) { }
	// RVA: 0x34d6af0 VA: 0x7595aeeaf0
	public Void Add(String id, Single width) { }
	// RVA: 0x34d6afc VA: 0x7595aeeafc
	public Void Add(String id, fiLayout rule) { }
	// RVA: 0x34d6b0c VA: 0x7595aeeb0c
	public Void Add(Single width, fiLayout rule) { }
	// RVA: 0x34d6b80 VA: 0x7595aeeb80
	public Void Add(String id, Single width, fiLayout rule) { }
	// RVA: 0x34d692c VA: 0x7595aee92c
	private Void ActualAdd(String id, Single width, fiExpandMode expandMode, fiLayout rule) { }
	// RVA: 0x34d6b8c VA: 0x7595aeeb8c
	private Int32 get_ExpandCount() { }
	// RVA: 0x34d6c38 VA: 0x7595aeec38
	private Single get_MinimumWidth() { }
	// RVA: 0x34d6cdc VA: 0x7595aeecdc
	public override Rect GetSectionRect(String sectionId, Rect initial) { }
	// RVA: 0x34d6e84 VA: 0x7595aeee84
	public override Boolean RespondsTo(String sectionId) { }
	// RVA: 0x34d6f70 VA: 0x7595aeef70
	public override Single get_Height() { }
	// RVA: 0x34d7064 VA: 0x7595aef064
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
}
```