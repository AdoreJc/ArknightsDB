# WhereEnumerableIterator

**Namespace:** ` `


## Dump
```C#
// Dll : System.Core.dll
// Namespace : 
private class WhereEnumerableIterator`1 : Iterator`1
{
	private IEnumerable`1 source; // 0x0
	private Func`2 predicate; // 0x0
	private IEnumerator`1 enumerator; // 0x0


	// RVA: 0x VA: 0x0
	public Void .ctor(IEnumerable`1 source, Func`2 predicate) { }
	// RVA: 0x VA: 0x0
	public override Iterator`1 Clone() { }
	// RVA: 0x VA: 0x0
	public override Void Dispose() { }
	// RVA: 0x VA: 0x0
	public override Boolean MoveNext() { }
	// RVA: 0x VA: 0x0
	public override IEnumerable`1 Select(Func`2 selector) { }
	// RVA: 0x VA: 0x0
	public override IEnumerable`1 Where(Func`2 predicate) { }
}
```