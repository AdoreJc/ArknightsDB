# ResourceFallbackManager

**Namespace:** `System.Resources`


## Fields

- `CultureInfo m_startingCulture`

- `CultureInfo m_neutralResourcesCulture`

- `Boolean m_useParents`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Resources
internal class ResourceFallbackManager : IEnumerable`1, IEnumerable
{
	private CultureInfo m_startingCulture; // 0x10
	private CultureInfo m_neutralResourcesCulture; // 0x18
	private Boolean m_useParents; // 0x20


	// RVA: 0x5fd8e0c VA: 0x75985f0e0c
	internal Void .ctor(CultureInfo startingCulture, CultureInfo neutralResourcesCulture, Boolean useParents) { }
	// RVA: 0x5fd8ebc VA: 0x75985f0ebc
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x5fd8ec0 VA: 0x75985f0ec0
	public IEnumerator`1 GetEnumerator() { }
}
```