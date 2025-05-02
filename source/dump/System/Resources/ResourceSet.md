# ResourceSet

**Namespace:** `System.Resources`


## Fields

- `IResourceReader Reader`

- `Hashtable Table`

- `Hashtable _caseInsensitiveTable`


## Methods

- `Void CommonInit()`

- `Void Dispose()`

- `IDictionaryEnumerator GetEnumeratorHelper()`

- `Object GetObjectInternal(String)`

- `Object GetCaseInsensitiveObjectInternal(String)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Resources
public class ResourceSet : IDisposable, IEnumerable
{
	protected IResourceReader Reader; // 0x10
	protected Hashtable Table; // 0x18
	private Hashtable _caseInsensitiveTable; // 0x20


	// RVA: 0x5fe3974 VA: 0x75985fb974
	protected Void .ctor() { }
	// RVA: 0x5fe39f8 VA: 0x75985fb9f8
	internal Void .ctor(Boolean junk) { }
	// RVA: 0x5fe3990 VA: 0x75985fb990
	private Void CommonInit() { }
	// RVA: 0x5fe3a00 VA: 0x75985fba00
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x5fe3ae4 VA: 0x75985fbae4
	public Void Dispose() { }
	// RVA: 0x5fe3af4 VA: 0x75985fbaf4
	public virtual IDictionaryEnumerator GetEnumerator() { }
	// RVA: 0x5fe3b7c VA: 0x75985fbb7c
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x5fe3af8 VA: 0x75985fbaf8
	private IDictionaryEnumerator GetEnumeratorHelper() { }
	// RVA: 0x5fe3b80 VA: 0x75985fbb80
	public virtual String GetString(String name) { }
	// RVA: 0x5fe3dbc VA: 0x75985fbdbc
	public virtual String GetString(String name, Boolean ignoreCase) { }
	// RVA: 0x5fe429c VA: 0x75985fc29c
	public virtual Object GetObject(String name) { }
	// RVA: 0x5fe42a0 VA: 0x75985fc2a0
	public virtual Object GetObject(String name, Boolean ignoreCase) { }
	// RVA: 0x5fe3ce8 VA: 0x75985fbce8
	private Object GetObjectInternal(String name) { }
	// RVA: 0x5fe3fc0 VA: 0x75985fbfc0
	private Object GetCaseInsensitiveObjectInternal(String name) { }
}
```