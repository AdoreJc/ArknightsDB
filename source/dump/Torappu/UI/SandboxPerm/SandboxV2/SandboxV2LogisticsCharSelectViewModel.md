# SandboxV2LogisticsCharSelectViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Boolean m_isValid`

- `Int32 m_duration`

- `Int32 m_drinkCapacity`

- `Int32 m_aimedBuffIndex`


## Properties

- `Boolean isValid`

- `Int32 duration`

- `Int32 drinkCapacity`


## Methods

- `Boolean get_isValid()`

- `Int32 get_duration()`

- `Int32 get_drinkCapacity()`

- `Void LoadData(String, List`1)`

- `Void RefreshData(String)`

- `Void UpdateDataWithSingleChar(SandboxV2CharViewModel, Boolean)`

- `Void ClearAllBuff()`

- `Int32 TryToConsumeAimedBuffIndex()`

- `Void _GeneBuffDict(SandboxV2Data, List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2LogisticsCharSelectViewModel : IHotfixable
{
	private Boolean m_isValid; // 0x10
	private Int32 m_duration; // 0x14
	private Int32 m_drinkCapacity; // 0x18
	private Int32 m_aimedBuffIndex; // 0x1c
	public ListDict`2 buffDict; // 0x20
	private static DelegateBridge __Hotfix0_get_isValid; // 0x0
	private static DelegateBridge __Hotfix0_get_duration; // 0x8
	private static DelegateBridge __Hotfix0_get_drinkCapacity; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_RefreshData; // 0x20
	private static DelegateBridge __Hotfix0_UpdateDataWithSingleChar; // 0x28
	private static DelegateBridge __Hotfix0_ClearAllBuff; // 0x30
	private static DelegateBridge __Hotfix0_TryToConsumeAimedBuffIndex; // 0x38
	private static DelegateBridge __Hotfix0__GeneBuffDict; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Boolean isValid { get; }
	public Int32 duration { get; }
	public Int32 drinkCapacity { get; }

	// RVA: 0x24ac990 VA: 0x7594ac4990
	public Boolean get_isValid() { }
	// RVA: 0x24b4f44 VA: 0x7594accf44
	public Int32 get_duration() { }
	// RVA: 0x24b4fac VA: 0x7594accfac
	public Int32 get_drinkCapacity() { }
	// RVA: 0x24b26a4 VA: 0x7594aca6a4
	public Void LoadData(String topicId, List`1 selectedCharViewModels) { }
	// RVA: 0x24b3b90 VA: 0x7594acbb90
	public Void RefreshData(String topicId) { }
	// RVA: 0x24ad130 VA: 0x7594ac5130
	public Void UpdateDataWithSingleChar(SandboxV2CharViewModel charViewModel, Boolean isAdd) { }
	// RVA: 0x24b287c VA: 0x7594aca87c
	public Void ClearAllBuff() { }
	// RVA: 0x24b57b8 VA: 0x7594acd7b8
	public Int32 TryToConsumeAimedBuffIndex() { }
	// RVA: 0x24b5014 VA: 0x7594acd014
	private Void _GeneBuffDict(SandboxV2Data sandboxV2Data, List`1 selectedCharViewModels) { }
	// RVA: 0x24b25d8 VA: 0x7594aca5d8
	public Void .ctor() { }
}
```