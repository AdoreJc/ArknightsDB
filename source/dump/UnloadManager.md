# UnloadManager

**Namespace:** ` `


## Fields

- `BaseAssetLoader m_loader`

- `Int64 m_currentTs`


## Methods

- `Void Dispose()`

- `Void NotifyLoadAsset(String, Int32)`

- `Void Legacy_RemoveAsset(String)`

- `Void UnloadAsset(Object, Int32)`

- `Void NotifyCurrentTs(Int64)`

- `Void _UnloadAssetImpl(UnloadRequest)`

- `Void _DoReleaseAsset(String, Int32, Object)`

- `Void ForceUnloadPendingAssets()`

- `Int64 _GetNextUnloadTs()`

- `Void _TryUnloadPendingRequests()`

- `Void _RemovePendingRequestsByPath(String)`

- `Void _ClearAllAssets()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
private class UnloadManager : IHotfixable, IDisposable
{
	private const Int64 INVALID_TS_DELTA; // 0x0
	private const Int64 UNLOAD_DELAY; // 0x0
	private Dictionary`2 m_pendingUnloadRequests; // 0x10
	private List`1 m_stringListCache; // 0x18
	private BaseAssetLoader m_loader; // 0x20
	private Int64 m_currentTs; // 0x28
	private static __XLua_Gen_Delegate0 _c__Hotfix0_ctor; // 0x0
	private static __XLua_Gen_Delegate1 __Hotfix0_Dispose; // 0x8
	private static __XLua_Gen_Delegate141 __Hotfix0_NotifyLoadAsset; // 0x10
	private static __XLua_Gen_Delegate0 __Hotfix0_Legacy_RemoveAsset; // 0x18
	private static __XLua_Gen_Delegate141 __Hotfix0_UnloadAsset; // 0x20
	private static __XLua_Gen_Delegate22 __Hotfix0_NotifyCurrentTs; // 0x28
	private static __XLua_Gen_Delegate142 __Hotfix0__DoReleaseAsset; // 0x30
	private static __XLua_Gen_Delegate1 __Hotfix0_ForceUnloadPendingAssets; // 0x38
	private static __XLua_Gen_Delegate21 __Hotfix0__GetNextUnloadTs; // 0x40
	private static __XLua_Gen_Delegate1 __Hotfix0__TryUnloadPendingRequests; // 0x48
	private static __XLua_Gen_Delegate0 __Hotfix0__RemovePendingRequestsByPath; // 0x50
	private static __XLua_Gen_Delegate1 __Hotfix0__ClearAllAssets; // 0x58


	// RVA: 0x6795554 VA: 0x7598dad554
	public Void .ctor(BaseAssetLoader baseAssetLoader) { }
	// RVA: 0x67956cc VA: 0x7598dad6cc
	public Void Dispose() { }
	// RVA: 0x67948e0 VA: 0x7598dac8e0
	public Void NotifyLoadAsset(String path, Int32 group) { }
	// RVA: 0x67950a0 VA: 0x7598dad0a0
	public Void Legacy_RemoveAsset(String path) { }
	// RVA: 0x6794a44 VA: 0x7598daca44
	public Void UnloadAsset(Object asset, Int32 group) { }
	// RVA: 0x67954b0 VA: 0x7598dad4b0
	public Void NotifyCurrentTs(Int64 curTs) { }
	// RVA: 0x6796cac VA: 0x7598daecac
	private Void _UnloadAssetImpl(UnloadRequest request) { }
	// RVA: 0x6796a2c VA: 0x7598daea2c
	private Void _DoReleaseAsset(String path, Int32 assetId, Object asset) { }
	// RVA: 0x6795298 VA: 0x7598dad298
	public Void ForceUnloadPendingAssets() { }
	// RVA: 0x6796d04 VA: 0x7598daed04
	private Int64 _GetNextUnloadTs() { }
	// RVA: 0x6796d78 VA: 0x7598daed78
	private Void _TryUnloadPendingRequests() { }
	// RVA: 0x67965c0 VA: 0x7598dae5c0
	private Void _RemovePendingRequestsByPath(String path) { }
	// RVA: 0x6796360 VA: 0x7598dae360
	private Void _ClearAllAssets() { }
}
```