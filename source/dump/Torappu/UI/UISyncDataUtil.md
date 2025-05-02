# UISyncDataUtil

**Namespace:** `Torappu.UI`


## Fields

- `Int64 m_lastSyncDataTs`

- `Boolean m_isInitSyncStatus`

- `Int32 m_syncStatusTryTriggerCount`

- `DateTime m_lastAuthTime`

- `SyncServiceController m_syncServiceController`

- `PlayerSyncStatusViewModel m_cachedViewModel`


## Methods

- `EventStruct _FindNextSyncEvent()`

- `Boolean CheckIfToReauth()`

- `Boolean CheckIfCrossDays()`

- `Void TrySyncPlayerStatus(Action`2)`

- `Boolean CheckCrossDaysAndResync()`

- `Boolean CheckCrossDaysAndResyncIgnoreCheckin()`

- `Boolean _CheckCrossDaysAndResync(Boolean)`

- `Void _RouteToHomeToResync()`

- `Boolean _CheckIfSyncStatusDirty()`

- `Void _UpdateCacheAfterSyncStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UISyncDataUtil : Singleton`1
{
	private const Int32 SYNC_STATUS_INTERVAL_COUNT; // 0x0
	private const Int32 SYNC_STATUS_INTERVAL_SECONDS; // 0x0
	private const Int32 SYNC_STATUS_INTERVAL_FIXED; // 0x0
	private static Int32 s_loginSession; // 0x0
	private Int64 m_lastSyncDataTs; // 0x10
	private Boolean m_isInitSyncStatus; // 0x18
	private Int32 m_syncStatusTryTriggerCount; // 0x1c
	private DateTime m_lastAuthTime; // 0x20
	private SyncServiceController m_syncServiceController; // 0x28
	private PlayerSyncStatusViewModel m_cachedViewModel; // 0x30
	private List`1 m_staticSyncEvents; // 0x38
	private static DelegateBridge __Hotfix0__FindNextSyncEvent; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_NotifyDataSync; // 0x18
	private static DelegateBridge __Hotfix0_NotifyAuth; // 0x20
	private static DelegateBridge __Hotfix0_GetSyncStatusModel; // 0x28
	private static DelegateBridge __Hotfix0_GetLoginSession; // 0x30
	private static DelegateBridge __Hotfix0_GetForbiddenShopList; // 0x38
	private static DelegateBridge __Hotfix0_GetForbiddenGachaList; // 0x40
	private static DelegateBridge __Hotfix0_CheckIfToReauth; // 0x48
	private static DelegateBridge __Hotfix0_CheckIfCrossDays; // 0x50
	private static DelegateBridge __Hotfix0_TrySyncPlayerStatus; // 0x58
	private static DelegateBridge __Hotfix0_CheckCrossDaysAndResync; // 0x60
	private static DelegateBridge __Hotfix0_CheckCrossDaysAndResyncIgnoreCheckin; // 0x68
	private static DelegateBridge __Hotfix0__CheckCrossDaysAndResync; // 0x70
	private static DelegateBridge __Hotfix0__RouteToHomeToResync; // 0x78
	private static DelegateBridge __Hotfix0__CheckIfCanCheckin; // 0x80
	private static DelegateBridge __Hotfix0__CheckIfSyncStatusDirty; // 0x88
	private static DelegateBridge __Hotfix0__UpdateCacheAfterSyncStatus; // 0x90
	private static DelegateBridge __Hotfix0__CheckIfToSyncByTime; // 0x98
	private static DelegateBridge __Hotfix0__InitStatusSyncEventList; // 0xa0


	// RVA: 0x21f96c8 VA: 0x75948116c8
	private EventStruct _FindNextSyncEvent() { }
	// RVA: 0x21f9cfc VA: 0x7594811cfc
	private Void .ctor() { }
	// RVA: 0x21fa564 VA: 0x7594812564
	public static Void NotifyDataSync() { }
	// RVA: 0x21fa62c VA: 0x759481262c
	public static Void NotifyAuth() { }
	// RVA: 0x21fa6f4 VA: 0x75948126f4
	public static PlayerSyncStatusViewModel GetSyncStatusModel() { }
	// RVA: 0x21fa788 VA: 0x7594812788
	public static Int32 GetLoginSession() { }
	// RVA: 0x21fa810 VA: 0x7594812810
	public static List`1 GetForbiddenShopList() { }
	// RVA: 0x21fa8a8 VA: 0x75948128a8
	public static List`1 GetForbiddenGachaList() { }
	// RVA: 0x21fa940 VA: 0x7594812940
	public Boolean CheckIfToReauth() { }
	// RVA: 0x21fa9f4 VA: 0x75948129f4
	public Boolean CheckIfCrossDays() { }
	// RVA: 0x21faae4 VA: 0x7594812ae4
	public Void TrySyncPlayerStatus(Action`2 callback) { }
	// RVA: 0x21fb764 VA: 0x7594813764
	public Boolean CheckCrossDaysAndResync() { }
	// RVA: 0x21fb9c4 VA: 0x75948139c4
	public Boolean CheckCrossDaysAndResyncIgnoreCheckin() { }
	// RVA: 0x21fb7e0 VA: 0x75948137e0
	private Boolean _CheckCrossDaysAndResync(Boolean ignoreCheckin) { }
	// RVA: 0x21fbb6c VA: 0x7594813b6c
	private Void _RouteToHomeToResync() { }
	// RVA: 0x21fba40 VA: 0x7594813a40
	private static Boolean _CheckIfCanCheckin() { }
	// RVA: 0x21fac94 VA: 0x7594812c94
	private Boolean _CheckIfSyncStatusDirty() { }
	// RVA: 0x21fbdcc VA: 0x7594813dcc
	private Void _UpdateCacheAfterSyncStatus() { }
	// RVA: 0x21fbe70 VA: 0x7594813e70
	private static Boolean _CheckIfToSyncByTime(DateTime curTime, ref DateTime lastUpdateTime) { }
	// RVA: 0x21f9960 VA: 0x7594811960
	private static List`1 _InitStatusSyncEventList() { }
	// RVA: 0x21fc018 VA: 0x7594814018
	private static Void .cctor() { }
}
```