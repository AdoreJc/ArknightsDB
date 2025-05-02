# OpenServerV2ChainLoginViewModel

**Namespace:** `Torappu.UI.Home.Activity`


## Fields

- `String desc`

- `String bkgImgId`

- `Boolean m_isAvailable`


## Methods

- `Void LoadData(OpenServerData, OpenServerScheduleItem)`

- `Void UpdateStatusByPlayerData()`

- `Boolean CheckAvailable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Activity
public class OpenServerV2ChainLoginViewModel : IHotfixable
{
	public String desc; // 0x10
	public String bkgImgId; // 0x18
	public List`1 items; // 0x20
	public List`1 displayChars; // 0x28
	private Boolean m_isAvailable; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateStatusByPlayerData; // 0x8
	private static DelegateBridge __Hotfix0_CheckAvailable; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2858124 VA: 0x7594e70124
	public Void LoadData(OpenServerData openServerData, OpenServerScheduleItem groupData) { }
	// RVA: 0x28588a4 VA: 0x7594e708a4
	public Void UpdateStatusByPlayerData() { }
	// RVA: 0x2858e48 VA: 0x7594e70e48
	public Boolean CheckAvailable() { }
	// RVA: 0x2858f80 VA: 0x7594e70f80
	public Void .ctor() { }
}
```