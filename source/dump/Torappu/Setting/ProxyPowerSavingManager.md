# ProxyPowerSavingManager

**Namespace:** `Torappu.Setting`


## Fields

- `Boolean m_openPowerSavingMode`

- `Int64 m_loginToken`


## Methods

- `Boolean GetPowerSavingStatus()`

- `Void SetPowerSavingStatus(Boolean)`

- `Boolean GetProxyBattleStatus()`

- `Void _SendSetLowPowerRequest(Boolean)`

- `Void _SyncFromPlayerData()`

- `Void <_SendSetLowPowerRequest>b__6_0(SetLowPowerResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Setting
public class ProxyPowerSavingManager : Singleton`1
{
	private Boolean m_openPowerSavingMode; // 0x10
	private Int64 m_loginToken; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetPowerSavingStatus; // 0x8
	private static DelegateBridge __Hotfix0_SetPowerSavingStatus; // 0x10
	private static DelegateBridge __Hotfix0_GetProxyBattleStatus; // 0x18
	private static DelegateBridge __Hotfix0__SendSetLowPowerRequest; // 0x20
	private static DelegateBridge __Hotfix0__SyncFromPlayerData; // 0x28


	// RVA: 0x3e34f40 VA: 0x759644cf40
	private Void .ctor() { }
	// RVA: 0x3e34fd8 VA: 0x759644cfd8
	public Boolean GetPowerSavingStatus() { }
	// RVA: 0x3e3518c VA: 0x759644d18c
	public Void SetPowerSavingStatus(Boolean value) { }
	// RVA: 0x3e3540c VA: 0x759644d40c
	public Boolean GetProxyBattleStatus() { }
	// RVA: 0x3e3520c VA: 0x759644d20c
	private Void _SendSetLowPowerRequest(Boolean isLowPower) { }
	// RVA: 0x3e350d8 VA: 0x759644d0d8
	private Void _SyncFromPlayerData() { }
	// RVA: 0x3e354f8 VA: 0x759644d4f8
	private Void <_SendSetLowPowerRequest>b__6_0(SetLowPowerResponse response) { }
}
```