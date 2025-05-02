# CrisisV2SnapshotDataUtil

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2SnapshotDataFromServer m_dataFromServer`


## Methods

- `Boolean RequestCrisisV2SnapshotDataIfNeeded()`

- `ServerDataValidStatus GetServerDataValidStatus()`

- `CrisisV2SnapshotData GetCacheData()`

- `Boolean CheckIfDataValid()`

- `Boolean _RequestCrisisV2SnapshotDataIfNeeded()`

- `Void _OnGetSnapshotProceed(CrisisV2GetSnapshotResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2SnapshotDataUtil : Singleton`1
{
	private CrisisV2SnapshotDataFromServer m_dataFromServer; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_RequestCrisisV2SnapshotDataIfNeeded; // 0x8
	private static DelegateBridge __Hotfix0_GetServerDataValidStatus; // 0x10
	private static DelegateBridge __Hotfix0_GetCacheData; // 0x18
	private static DelegateBridge __Hotfix0_CheckIfDataValid; // 0x20
	private static DelegateBridge __Hotfix0__RequestCrisisV2SnapshotDataIfNeeded; // 0x28
	private static DelegateBridge __Hotfix0__OnGetSnapshotProceed; // 0x30


	// RVA: 0x2bc9578 VA: 0x75951e1578
	private Void .ctor() { }
	// RVA: 0x2bc9644 VA: 0x75951e1644
	public Boolean RequestCrisisV2SnapshotDataIfNeeded() { }
	// RVA: 0x2bc9954 VA: 0x75951e1954
	public ServerDataValidStatus GetServerDataValidStatus() { }
	// RVA: 0x2bc99e4 VA: 0x75951e19e4
	public CrisisV2SnapshotData GetCacheData() { }
	// RVA: 0x2bc9a78 VA: 0x75951e1a78
	public Boolean CheckIfDataValid() { }
	// RVA: 0x2bc96ac VA: 0x75951e16ac
	private Boolean _RequestCrisisV2SnapshotDataIfNeeded() { }
	// RVA: 0x2bc9b00 VA: 0x75951e1b00
	private Void _OnGetSnapshotProceed(CrisisV2GetSnapshotResponse response) { }
}
```