# ArchiveLogModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String selectedLogId`

- `Boolean isInit`


## Methods

- `Void LoadData(String, ActArchiveComponentData, ActArchiveInfo)`

- `LogArchiveResItemData _GetArchiveLogResData(String)`

- `String GetDefaultItemId()`

- `Int32 GetSelectedIndex(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveLogModel : IHotfixable
{
	public ListDict`2 logItems; // 0x10
	public String selectedLogId; // 0x18
	public Boolean isInit; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__GetArchiveLogResData; // 0x8
	private static DelegateBridge __Hotfix0_GetDefaultItemId; // 0x10
	private static DelegateBridge __Hotfix0_GetSelectedIndex; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x305b4f8 VA: 0x75956734f8
	public Void LoadData(String archiveId, ActArchiveComponentData compData, ActArchiveInfo archiveInfo) { }
	// RVA: 0x305bab0 VA: 0x7595673ab0
	private LogArchiveResItemData _GetArchiveLogResData(String logId) { }
	// RVA: 0x305bc84 VA: 0x7595673c84
	public String GetDefaultItemId() { }
	// RVA: 0x305be3c VA: 0x7595673e3c
	public Int32 GetSelectedIndex(String selectedItemId) { }
	// RVA: 0x305bedc VA: 0x7595673edc
	public Void .ctor() { }
}
```