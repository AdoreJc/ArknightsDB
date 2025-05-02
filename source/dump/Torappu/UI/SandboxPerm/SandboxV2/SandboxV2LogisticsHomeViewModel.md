# SandboxV2LogisticsHomeViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Int32 drinkCntPerPeriod`

- `Int32 basementLevel`

- `SandboxV2LogisticsBuffInvalidStatus buffInvalidStatus`

- `Int32 drinkTotalCapacity`

- `Int32 squadMaxCount`

- `Int32 squadMaxValidCount`

- `String removeCharDialogDesc`

- `String removeCharDialogWarning`

- `Boolean isInRift`

- `String m_topicId`

- `SandboxV2LogisticsVisitMode m_visitMode`

- `Int32 m_selectedCharIndex`


## Properties

- `String topicId`

- `Boolean isBuffValid`

- `Boolean isUpdateSquadValid`

- `Int32 selectCharIndex`

- `Boolean isNoSelectChar`


## Methods

- `String get_topicId()`

- `Boolean get_isBuffValid()`

- `Boolean get_isUpdateSquadValid()`

- `Int32 get_selectCharIndex()`

- `Boolean get_isNoSelectChar()`

- `Void InitData(String, SandboxV2LogisticsVisitMode)`

- `Void LoadData()`

- `SandboxV2LogisticsCharViewModel GetSelectCharViewModel()`

- `Boolean TryToSwitchBuffInfo(Int32)`

- `Void SwitchBuffInfoToTotal()`

- `Boolean CheckIfDecreaseBuffWhenRemoveChar()`

- `Int32 GetCharSelectIndexByIndex(Int32)`

- `Void _GeneCharViewModelList(SandboxV2Data, PlayerSandboxV2)`

- `Void _GeneBuffViewModelList(SandboxV2Data, PlayerSandboxV2)`

- `SandboxV2LogisticsBuffInvalidStatus _GetBuffInvalidStatus(PlayerSandboxV2)`

- `Int32 _CompareCharsWithCharSelectRule(SandboxV2LogisticsCharViewModel, SandboxV2LogisticsCharViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2LogisticsHomeViewModel : IHotfixable
{
	public ListDict`2 buffListDict; // 0x10
	public List`1 charList; // 0x18
	public Int32 drinkCntPerPeriod; // 0x20
	public Int32 basementLevel; // 0x24
	public SandboxV2LogisticsBuffInvalidStatus buffInvalidStatus; // 0x28
	public Int32 drinkTotalCapacity; // 0x2c
	public Int32 squadMaxCount; // 0x30
	public Int32 squadMaxValidCount; // 0x34
	public String removeCharDialogDesc; // 0x38
	public String removeCharDialogWarning; // 0x40
	public Boolean isInRift; // 0x48
	private String m_topicId; // 0x50
	private SandboxV2LogisticsVisitMode m_visitMode; // 0x58
	private Int32 m_selectedCharIndex; // 0x5c
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_isBuffValid; // 0x8
	private static DelegateBridge __Hotfix0_get_isUpdateSquadValid; // 0x10
	private static DelegateBridge __Hotfix0_get_selectCharIndex; // 0x18
	private static DelegateBridge __Hotfix0_get_isNoSelectChar; // 0x20
	private static DelegateBridge __Hotfix0_InitData; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0_GetSelectCharViewModel; // 0x38
	private static DelegateBridge __Hotfix0_TryToSwitchBuffInfo; // 0x40
	private static DelegateBridge __Hotfix0_SwitchBuffInfoToTotal; // 0x48
	private static DelegateBridge __Hotfix0_CheckIfDecreaseBuffWhenRemoveChar; // 0x50
	private static DelegateBridge __Hotfix0_GeneSelectCharDictForCharSelect; // 0x58
	private static DelegateBridge __Hotfix0_GetCharSelectIndexByIndex; // 0x60
	private static DelegateBridge __Hotfix0__GeneCharViewModelList; // 0x68
	private static DelegateBridge __Hotfix0__GeneBuffViewModelList; // 0x70
	private static DelegateBridge __Hotfix0__GetBuffInvalidStatus; // 0x78
	private static DelegateBridge __Hotfix0__CompareCharsWithCharSelectRule; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public String topicId { get; }
	public Boolean isBuffValid { get; }
	public Boolean isUpdateSquadValid { get; }
	public Int32 selectCharIndex { get; }
	public Boolean isNoSelectChar { get; }

	// RVA: 0x25d9bd8 VA: 0x7594bf1bd8
	public String get_topicId() { }
	// RVA: 0x25db9e4 VA: 0x7594bf39e4
	public Boolean get_isBuffValid() { }
	// RVA: 0x25da230 VA: 0x7594bf2230
	public Boolean get_isUpdateSquadValid() { }
	// RVA: 0x25dcf88 VA: 0x7594bf4f88
	public Int32 get_selectCharIndex() { }
	// RVA: 0x25d9960 VA: 0x7594bf1960
	public Boolean get_isNoSelectChar() { }
	// RVA: 0x25dd9a8 VA: 0x7594bf59a8
	public Void InitData(String topicId, SandboxV2LogisticsVisitMode visitMode) { }
	// RVA: 0x25dab40 VA: 0x7594bf2b40
	public Void LoadData() { }
	// RVA: 0x25d99fc VA: 0x7594bf19fc
	public SandboxV2LogisticsCharViewModel GetSelectCharViewModel() { }
	// RVA: 0x25da2a0 VA: 0x7594bf22a0
	public Boolean TryToSwitchBuffInfo(Int32 squadIndex) { }
	// RVA: 0x25da0c0 VA: 0x7594bf20c0
	public Void SwitchBuffInfoToTotal() { }
	// RVA: 0x25d9aa0 VA: 0x7594bf1aa0
	public Boolean CheckIfDecreaseBuffWhenRemoveChar() { }
	// RVA: 0x25da710 VA: 0x7594bf2710
	public ListDict`2 GeneSelectCharDictForCharSelect() { }
	// RVA: 0x25da8b4 VA: 0x7594bf28b4
	public Int32 GetCharSelectIndexByIndex(Int32 selectIndex) { }
	// RVA: 0x25ddacc VA: 0x7594bf5acc
	private Void _GeneCharViewModelList(SandboxV2Data gameData, PlayerSandboxV2 playerSandboxV2) { }
	// RVA: 0x25ddf2c VA: 0x7594bf5f2c
	private Void _GeneBuffViewModelList(SandboxV2Data gameData, PlayerSandboxV2 playerSandboxV2) { }
	// RVA: 0x25de4b4 VA: 0x7594bf64b4
	private SandboxV2LogisticsBuffInvalidStatus _GetBuffInvalidStatus(PlayerSandboxV2 playerSandboxV2) { }
	// RVA: 0x25de928 VA: 0x7594bf6928
	private Int32 _CompareCharsWithCharSelectRule(SandboxV2LogisticsCharViewModel obj1, SandboxV2LogisticsCharViewModel obj2) { }
	// RVA: 0x25dd88c VA: 0x7594bf588c
	public Void .ctor() { }
}
```