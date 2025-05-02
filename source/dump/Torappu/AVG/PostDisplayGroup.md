# PostDisplayGroup

**Namespace:** `Torappu.AVG`


## Fields

- `IHost m_host`


## Methods

- `T LoadAsset(String)`

- `PostDisplayHandler Bind(PostDisplayKey)`

- `Void Remove(PostDisplayItem)`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class PostDisplayGroup : IHotfixable, IDisposable
{
	private IHost m_host; // 0x10
	private List`1 m_items; // 0x18
	private List`1 m_cachedItems; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_LoadAsset; // 0x8
	private static DelegateBridge __Hotfix0_Bind; // 0x10
	private static DelegateBridge __Hotfix0_Remove; // 0x18
	private static DelegateBridge __Hotfix0_Dispose; // 0x20


	// RVA: 0x3e98240 VA: 0x75964b0240
	public Void .ctor(IHost host) { }
	// RVA: 0x VA: 0x0
	public T LoadAsset(String resPath) { }
	// RVA: 0x VA: 0x0
	public PostDisplayHandler Bind(PostDisplayKey key) { }
	// RVA: 0x3e9c170 VA: 0x75964b4170
	public Void Remove(PostDisplayItem item) { }
	// RVA: 0x3e9c3c4 VA: 0x75964b43c4
	public Void Dispose() { }
}
```