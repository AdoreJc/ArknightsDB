# TrackPointLocalCache

**Namespace:** `Torappu.UI`


## Methods

- `Void _ApplyTraceOnData(IEnumerator`1, Func`4)`

- `Boolean _CheckTrace(String, TrackPointCacheGroup)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class TrackPointLocalCache : Singleton`1
{
	private const Int32 VALID_TOKEN; // 0x0
	private Data`1 m_memCache; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__GetMemCache; // 0x8
	private static DelegateBridge __Hotfix0_LogTrace; // 0x10
	private static DelegateBridge __Hotfix0_BatchLogTrace; // 0x18
	private static DelegateBridge __Hotfix0_Consume; // 0x20
	private static DelegateBridge __Hotfix0_BatchConsume; // 0x28
	private static DelegateBridge __Hotfix0_CheckTrace; // 0x30
	private static DelegateBridge __Hotfix0__ActionLogTrace; // 0x38
	private static DelegateBridge __Hotfix0__ActionConsumeTrace; // 0x40
	private static DelegateBridge __Hotfix0__ApplyTraceOnData; // 0x48
	private static DelegateBridge __Hotfix0__CheckTrace; // 0x50


	// RVA: 0x21e9ae0 VA: 0x7594801ae0
	private Void .ctor() { }
	// RVA: 0x21e9b70 VA: 0x7594801b70
	private Data`1 _GetMemCache() { }
	// RVA: 0x21e9ca8 VA: 0x7594801ca8
	public static Void LogTrace(String trace, TrackPointCacheGroup group) { }
	// RVA: 0x21ea078 VA: 0x7594802078
	public static Void BatchLogTrace(IEnumerator`1 traceIter) { }
	// RVA: 0x21ea15c VA: 0x759480215c
	public static Void Consume(String trace, TrackPointCacheGroup group) { }
	// RVA: 0x21ea2fc VA: 0x75948022fc
	public static Void BatchConsume(IEnumerator`1 traceIter) { }
	// RVA: 0x21ea3e0 VA: 0x75948023e0
	public static Boolean CheckTrace(String trace, TrackPointCacheGroup group) { }
	// RVA: 0x21ea54c VA: 0x759480254c
	private static Boolean _ActionLogTrace(CacheData data, String trace, TrackPointCacheGroup group) { }
	// RVA: 0x21ea748 VA: 0x7594802748
	private static Boolean _ActionConsumeTrace(CacheData data, String trace, TrackPointCacheGroup group) { }
	// RVA: 0x21e9e48 VA: 0x7594801e48
	private Void _ApplyTraceOnData(IEnumerator`1 traceIter, Func`4 action) { }
	// RVA: 0x21ea484 VA: 0x7594802484
	public Boolean _CheckTrace(String trace, TrackPointCacheGroup group) { }
}
```