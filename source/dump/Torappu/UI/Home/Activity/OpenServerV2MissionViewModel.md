# OpenServerV2MissionViewModel

**Namespace:** `Torappu.UI.Home.Activity`


## Fields

- `Boolean m_isAvailable`


## Methods

- `Void LoadData(OpenServerData, OpenServerScheduleItem)`

- `Void UpdateStatusByPlayerData()`

- `Boolean CheckAvailable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Activity
public class OpenServerV2MissionViewModel : IHotfixable
{
	public List`1 items; // 0x10
	private Boolean m_isAvailable; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateStatusByPlayerData; // 0x8
	private static DelegateBridge __Hotfix0_CheckAvailable; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x28583d8 VA: 0x7594e703d8
	public Void LoadData(OpenServerData openServerData, OpenServerScheduleItem groupData) { }
	// RVA: 0x2858a8c VA: 0x7594e70a8c
	public Void UpdateStatusByPlayerData() { }
	// RVA: 0x2858eb0 VA: 0x7594e70eb0
	public Boolean CheckAvailable() { }
	// RVA: 0x285909c VA: 0x7594e7109c
	public Void .ctor() { }
}
```