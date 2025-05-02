# FileSystemEnumerable

**Namespace:** `System.IO.Enumeration`


## Fields

- `DelegateEnumerator _enumerator`

- `FindPredicate <ShouldIncludePredicate>k__BackingField`

- `FindPredicate <ShouldRecursePredicate>k__BackingField`


## Properties

- `FindPredicate ShouldIncludePredicate`

- `FindPredicate ShouldRecursePredicate`


## Methods

- `FindPredicate get_ShouldIncludePredicate()`

- `Void set_ShouldIncludePredicate(FindPredicate)`

- `FindPredicate get_ShouldRecursePredicate()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.IO.Enumeration
public class FileSystemEnumerable`1 : IEnumerable`1, IEnumerable
{
	private DelegateEnumerator _enumerator; // 0x0
	private readonly FindTransform _transform; // 0x0
	private readonly EnumerationOptions _options; // 0x0
	private readonly String _directory; // 0x0
	private FindPredicate <ShouldIncludePredicate>k__BackingField; // 0x0
	private FindPredicate <ShouldRecursePredicate>k__BackingField; // 0x0

	public FindPredicate ShouldIncludePredicate { get; set; }
	public FindPredicate ShouldRecursePredicate { get; }

	// RVA: 0x VA: 0x0
	public Void .ctor(String directory, FindTransform transform, EnumerationOptions options) { }
	// RVA: 0x VA: 0x0
	public FindPredicate get_ShouldIncludePredicate() { }
	// RVA: 0x VA: 0x0
	public Void set_ShouldIncludePredicate(FindPredicate value) { }
	// RVA: 0x VA: 0x0
	public FindPredicate get_ShouldRecursePredicate() { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
}
```