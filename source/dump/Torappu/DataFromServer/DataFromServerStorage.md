# DataFromServerStorage

**Namespace:** `Torappu.DataFromServer`


## Methods

- `Void UpdateStatusWhenLogin()`

- `Void UpdateStatusWhenSyncStatus()`

- `Void _UpdateDataOnEvents(Func`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DataFromServer
public class DataFromServerStorage : Singleton`1
{
	private Dictionary`2 m_storage; // 0x10
	private List`1 m_sharedList; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_UpdateStatusWhenLogin; // 0x8
	private static DelegateBridge __Hotfix0_UpdateStatusWhenSyncStatus; // 0x10
	private static DelegateBridge __Hotfix0_DataFromServer_SetData; // 0x18
	private static DelegateBridge __Hotfix0_DataFromServer_GetData; // 0x20
	private static DelegateBridge __Hotfix0__UpdateDataOnEvents; // 0x28
	private static DelegateBridge __Hotfix0__GenerateCurrentStatus; // 0x30
	private static DelegateBridge __Hotfix0__CheckIfNeedCrossDay; // 0x38
	private static DelegateBridge __Hotfix0__CheckIfValidForCrossDay; // 0x40


	// RVA: 0x372d4a0 VA: 0x7595d454a0
	private Void .ctor() { }
	// RVA: 0x372d5d4 VA: 0x7595d455d4
	public Void UpdateStatusWhenLogin() { }
	// RVA: 0x372d980 VA: 0x7595d45980
	public Void UpdateStatusWhenSyncStatus() { }
	// RVA: 0x372daa8 VA: 0x7595d45aa8
	internal Void DataFromServer_SetData(IDataConfig config, Object data) { }
	// RVA: 0x372dd6c VA: 0x7595d45d6c
	internal GetDataResult DataFromServer_GetData(IDataConfig config) { }
	// RVA: 0x372d6fc VA: 0x7595d456fc
	private Void _UpdateDataOnEvents(Func`2 remover) { }
	// RVA: 0x372dcd4 VA: 0x7595d45cd4
	private static Status _GenerateCurrentStatus() { }
	// RVA: 0x372df10 VA: 0x7595d45f10
	private static Boolean _CheckIfNeedCrossDay(DataChunk chunk) { }
	// RVA: 0x372dfc8 VA: 0x7595d45fc8
	private static Boolean _CheckIfValidForCrossDay(DataChunk chunk) { }
}
```