# WhereSelectArrayIterator

**Namespace:** ` `


## Fields

- `Int32 index`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : 
private class WhereSelectArrayIterator`2 : Iterator`1
{
	private TSource[] source; // 0x0
	private Func`2 predicate; // 0x0
	private Func`2 selector; // 0x0
	private Int32 index; // 0x0


	// RVA: 0x VA: 0x0
	public Void .ctor(TSource[] source, Func`2 predicate, Func`2 selector) { }
	// RVA: 0x VA: 0x0
	public override Iterator`1 Clone() { }
	// RVA: 0x VA: 0x0
	public override Boolean MoveNext() { }
	// RVA: 0x VA: 0x0
	public override IEnumerable`1 Select(Func`2 selector) { }
	// RVA: 0x VA: 0x0
	public override IEnumerable`1 Where(Func`2 predicate) { }
}
```