# LegionCharacterStatus

**Namespace:** ` `


## Fields

- `Single <hatred>k__BackingField`

- `Boolean <keepStatusOnce>k__BackingField`

- `Int32 statusLevel`

- `Int32 tmpStatusLevel`


## Properties

- `Single hatred`

- `Boolean keepStatusOnce`

- `ProfessionCategory lastStatusProfession`


## Methods

- `Void Reset()`

- `Single get_hatred()`

- `Void set_hatred(Single)`

- `Boolean get_keepStatusOnce()`

- `Void set_keepStatusOnce(Boolean)`

- `ProfessionCategory get_lastStatusProfession()`

- `Boolean AddStatusLevel(ProfessionCategory, Int32, Int32)`

- `Void FilterMaxLevel(Int32)`

- `Int32 GetStatusLevel(ProfessionCategory)`

- `Int32 GetStatusTotalLevel()`

- `Int32 GetSpecifiedProfessionStatusTotalLevel(ProfessionCategory)`

- `Int32 GetStatusProfessionCnt()`

- `Void AddStatusToTmpStatusDic()`

- `Void ClearTmpStatusDic()`

- `Void CopyFrom(LegionCharacterStatus)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionCharacterStatus : IHotfixable
{
	private static HashSet`1 m_sharedSet; // 0x0
	private Single <hatred>k__BackingField; // 0x10
	private Boolean <keepStatusOnce>k__BackingField; // 0x14
	public List`1 statusList; // 0x18
	public List`1 tempStatusList; // 0x20
	private Dictionary`2 m_tmpStatusDic; // 0x28
	public Int32 statusLevel; // 0x30
	public Int32 tmpStatusLevel; // 0x34
	private static DelegateBridge __Hotfix0_Reset; // 0x8
	private static DelegateBridge __Hotfix0_get_hatred; // 0x10
	private static DelegateBridge __Hotfix0_set_hatred; // 0x18
	private static DelegateBridge __Hotfix0_get_keepStatusOnce; // 0x20
	private static DelegateBridge __Hotfix0_set_keepStatusOnce; // 0x28
	private static DelegateBridge __Hotfix0_get_lastStatusProfession; // 0x30
	private static DelegateBridge __Hotfix0_AddStatusLevel; // 0x38
	private static DelegateBridge __Hotfix0_FilterMaxLevel; // 0x40
	private static DelegateBridge __Hotfix0_GetStatusLevel; // 0x48
	private static DelegateBridge __Hotfix0_GetStatusTotalLevel; // 0x50
	private static DelegateBridge __Hotfix0_GetSpecifiedProfessionStatusTotalLevel; // 0x58
	private static DelegateBridge __Hotfix0_GetStatusProfessionCnt; // 0x60
	private static DelegateBridge __Hotfix0_AddStatusToTmpStatusDic; // 0x68
	private static DelegateBridge __Hotfix0_ClearTmpStatusDic; // 0x70
	private static DelegateBridge __Hotfix0_CopyFrom; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public Single hatred { get; set; }
	public Boolean keepStatusOnce { get; set; }
	public ProfessionCategory lastStatusProfession { get; }

	// RVA: 0x3fda5fc VA: 0x75965f25fc
	public Void Reset() { }
	// RVA: 0x3fdac78 VA: 0x75965f2c78
	public Single get_hatred() { }
	// RVA: 0x3fda3f4 VA: 0x75965f23f4
	public Void set_hatred(Single value) { }
	// RVA: 0x3fd7a24 VA: 0x75965efa24
	public Boolean get_keepStatusOnce() { }
	// RVA: 0x3fd7a9c VA: 0x75965efa9c
	public Void set_keepStatusOnce(Boolean value) { }
	// RVA: 0x3fdacf0 VA: 0x75965f2cf0
	public ProfessionCategory get_lastStatusProfession() { }
	// RVA: 0x3fd82f8 VA: 0x75965f02f8
	public Boolean AddStatusLevel(ProfessionCategory professionKey, Int32 num, Int32 maxNum) { }
	// RVA: 0x3fd7304 VA: 0x75965ef304
	public Void FilterMaxLevel(Int32 maxLevel) { }
	// RVA: 0x3fd9110 VA: 0x75965f1110
	public Int32 GetStatusLevel(ProfessionCategory key) { }
	// RVA: 0x3fd9c6c VA: 0x75965f1c6c
	public Int32 GetStatusTotalLevel() { }
	// RVA: 0x3fda190 VA: 0x75965f2190
	public Int32 GetSpecifiedProfessionStatusTotalLevel(ProfessionCategory queryProfession) { }
	// RVA: 0x3fd9d84 VA: 0x75965f1d84
	public Int32 GetStatusProfessionCnt() { }
	// RVA: 0x3fd86d0 VA: 0x75965f06d0
	public Void AddStatusToTmpStatusDic() { }
	// RVA: 0x3fd89e0 VA: 0x75965f09e0
	public Void ClearTmpStatusDic() { }
	// RVA: 0x3fda6d0 VA: 0x75965f26d0
	public Void CopyFrom(LegionCharacterStatus fromStatus) { }
	// RVA: 0x3fda480 VA: 0x75965f2480
	public Void .ctor() { }
	// RVA: 0x3fdada8 VA: 0x75965f2da8
	private static Void .cctor() { }
}
```