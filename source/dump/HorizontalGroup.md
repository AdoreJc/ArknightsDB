# HorizontalGroup

**Namespace:** ` `


## Methods

- `Void Add(tkControl`2)`

- `Void Add(Boolean, tkControl`2)`

- `Void Add(Single)`

- `Void Add(Single, tkControl`2)`

- `Void InternalAdd(Boolean, Single, Single, tkControl`2)`

- `Void DoLayout(Rect, T, TContext, fiGraphMetadata)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HorizontalGroup : tkControl`2, IEnumerable
{
	private readonly List`1 _items; // 0x0
	private static readonly tkControl`2 DefaultRule; // 0x0

	protected override IEnumerable`1 NonMemberChildControls { get; }

	// RVA: 0x VA: 0x0
	protected override IEnumerable`1 get_NonMemberChildControls() { }
	// RVA: 0x VA: 0x0
	public Void Add(tkControl`2 rule) { }
	// RVA: 0x VA: 0x0
	public Void Add(Boolean matchParentHeight, tkControl`2 rule) { }
	// RVA: 0x VA: 0x0
	public Void Add(Single width) { }
	// RVA: 0x VA: 0x0
	public Void Add(Single width, tkControl`2 rule) { }
	// RVA: 0x VA: 0x0
	private Void InternalAdd(Boolean matchParentHeight, Single width, Single fillStrength, tkControl`2 rule) { }
	// RVA: 0x VA: 0x0
	private Void DoLayout(Rect rect, T obj, TContext context, fiGraphMetadata metadata) { }
	// RVA: 0x VA: 0x0
	protected override T DoEdit(Rect rect, T obj, TContext context, fiGraphMetadata metadata) { }
	// RVA: 0x VA: 0x0
	protected override Single DoGetHeight(T obj, TContext context, fiGraphMetadata metadata) { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	private static Void .cctor() { }
}
```