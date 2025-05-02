# ActMultiV3PriClassModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3IdentityType <identityType>k__BackingField`


## Properties

- `ActMultiV3IdentityType identityType`


## Methods

- `ActMultiV3IdentityType get_identityType()`

- `Void set_identityType(ActMultiV3IdentityType)`

- `Void GenRequestSlotList(List`1)`

- `Void MergeCharIdTypeDict(Dictionary`2)`

- `Void LoadData(String, ActMultiV3Data, ActMultiV3MapModeType, ActMultiV3IdentityType)`

- `Void ShrinkSlots()`

- `Void UpdatePlayerData()`

- `Void _InitCharList(String, ActMultiV3MapModeType, ActMultiV3IdentityType)`

- `Int32 CalcCharCount()`

- `Boolean CheckIfCharChanged(List`1)`

- `Int32 _CalcCharCount()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3PriClassModel : IHotfixable
{
	private ActMultiV3CharViewModel[] m_charArr; // 0x10
	private ActMultiV3IdentityType <identityType>k__BackingField; // 0x18
	private static DelegateBridge __Hotfix0_get_identityType; // 0x0
	private static DelegateBridge __Hotfix0_set_identityType; // 0x8
	private static DelegateBridge __Hotfix0_get_charArr; // 0x10
	private static DelegateBridge __Hotfix0_GenRequestSlotList; // 0x18
	private static DelegateBridge __Hotfix0_MergeCharIdTypeDict; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0_ShrinkSlots; // 0x30
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x38
	private static DelegateBridge __Hotfix0__InitCharList; // 0x40
	private static DelegateBridge __Hotfix0_CalcCharCount; // 0x48
	private static DelegateBridge __Hotfix0_CheckIfCharChanged; // 0x50
	private static DelegateBridge __Hotfix0__CalcCharCount; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public ActMultiV3IdentityType identityType { get; set; }
	public ActMultiV3CharViewModel[] charArr { get; }

	// RVA: 0x31425dc VA: 0x759575a5dc
	public ActMultiV3IdentityType get_identityType() { }
	// RVA: 0x3142644 VA: 0x759575a644
	private Void set_identityType(ActMultiV3IdentityType value) { }
	// RVA: 0x31426c0 VA: 0x759575a6c0
	public ActMultiV3CharViewModel[] get_charArr() { }
	// RVA: 0x3142728 VA: 0x759575a728
	public Void GenRequestSlotList(List`1 slotList) { }
	// RVA: 0x3142b0c VA: 0x759575ab0c
	public Void MergeCharIdTypeDict(Dictionary`2 outputDict) { }
	// RVA: 0x3142cd8 VA: 0x759575acd8
	public Void LoadData(String actId, ActMultiV3Data actData, ActMultiV3MapModeType modeType, ActMultiV3IdentityType idType) { }
	// RVA: 0x3143034 VA: 0x759575b034
	public Void ShrinkSlots() { }
	// RVA: 0x31430b4 VA: 0x759575b0b4
	public Void UpdatePlayerData() { }
	// RVA: 0x3142dec VA: 0x759575adec
	private Void _InitCharList(String actId, ActMultiV3MapModeType modeType, ActMultiV3IdentityType idType) { }
	// RVA: 0x314354c VA: 0x759575b54c
	public Int32 CalcCharCount() { }
	// RVA: 0x31436a0 VA: 0x759575b6a0
	public Boolean CheckIfCharChanged(List`1 playerCharList) { }
	// RVA: 0x31435b4 VA: 0x759575b5b4
	private Int32 _CalcCharCount() { }
	// RVA: 0x3143954 VA: 0x759575b954
	public Void .ctor() { }
}
```