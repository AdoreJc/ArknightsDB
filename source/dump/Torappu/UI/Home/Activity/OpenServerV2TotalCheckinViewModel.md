# OpenServerV2TotalCheckinViewModel

**Namespace:** `Torappu.UI.Home.Activity`


## Fields

- `String desc`

- `Boolean m_isAvailable`


## Methods

- `Void LoadData(OpenServerData, OpenServerScheduleItem)`

- `Void UpdateStatusByPlayerData()`

- `Boolean CheckAvailable()`

- `Int32 GetFirstNotGotItemIndex()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Activity
public class OpenServerV2TotalCheckinViewModel : IHotfixable
{
	public String desc; // 0x10
	public List`1 items; // 0x18
	public List`1 displayChars; // 0x20
	private Boolean m_isAvailable; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateStatusByPlayerData; // 0x8
	private static DelegateBridge __Hotfix0_CheckAvailable; // 0x10
	private static DelegateBridge __Hotfix0_GetFirstNotGotItemIndex; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2858600 VA: 0x7594e70600
	public Void LoadData(OpenServerData openServerData, OpenServerScheduleItem groupData) { }
	// RVA: 0x2858c60 VA: 0x7594e70c60
	public Void UpdateStatusByPlayerData() { }
	// RVA: 0x2858f18 VA: 0x7594e70f18
	public Boolean CheckAvailable() { }
	// RVA: 0x2857230 VA: 0x7594e6f230
	public Int32 GetFirstNotGotItemIndex() { }
	// RVA: 0x2859168 VA: 0x7594e71168
	public Void .ctor() { }
}
```