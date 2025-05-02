# SandboxV2LogisticsCharSelectBuffViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `ProfessionCategory professionCategory`

- `Int32 maxValidBuffCount`

- `Int32 currentBuffCount`

- `String buffParam`

- `SandboxV2LogisticsData m_logisticsData`

- `String m_noBuffDesc`

- `String m_formatDesc`

- `Int32 <index>k__BackingField`


## Properties

- `Int32 index`

- `Boolean isFullBuff`

- `String fullDesc`


## Methods

- `Void set_index(Int32)`

- `Int32 get_index()`

- `Boolean get_isFullBuff()`

- `String get_fullDesc()`

- `Void InitData(SandboxV2Data, ProfessionCategory, Int32)`

- `Void AddCharInBuffViewModel(SandboxV2CharViewModel)`

- `Void RemoveCharInBuffViewModel(SandboxV2CharViewModel)`

- `Void ClearCharsInBuffViewModel()`

- `SandboxV2LogisticsData _GetLogisticsDataByProfession(SandboxV2Data, ProfessionCategory)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2LogisticsCharSelectBuffViewModel : IHotfixable
{
	public ProfessionCategory professionCategory; // 0x10
	public Int32 maxValidBuffCount; // 0x14
	public Int32 currentBuffCount; // 0x18
	public String buffParam; // 0x20
	private SandboxV2LogisticsData m_logisticsData; // 0x28
	private String m_noBuffDesc; // 0x30
	private String m_formatDesc; // 0x38
	private Int32 <index>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_set_index; // 0x0
	private static DelegateBridge __Hotfix0_get_index; // 0x8
	private static DelegateBridge __Hotfix0_get_isFullBuff; // 0x10
	private static DelegateBridge __Hotfix0_get_fullDesc; // 0x18
	private static DelegateBridge __Hotfix0_InitData; // 0x20
	private static DelegateBridge __Hotfix0_AddCharInBuffViewModel; // 0x28
	private static DelegateBridge __Hotfix0_RemoveCharInBuffViewModel; // 0x30
	private static DelegateBridge __Hotfix0_ClearCharsInBuffViewModel; // 0x38
	private static DelegateBridge __Hotfix0__GetLogisticsDataByProfession; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Int32 index { get; set; }
	public Boolean isFullBuff { get; }
	public String fullDesc { get; }

	// RVA: 0x24b59d8 VA: 0x7594acd9d8
	private Void set_index(Int32 value) { }
	// RVA: 0x24b56ac VA: 0x7594acd6ac
	public Int32 get_index() { }
	// RVA: 0x24b5a54 VA: 0x7594acda54
	public Boolean get_isFullBuff() { }
	// RVA: 0x24b5ac4 VA: 0x7594acdac4
	public String get_fullDesc() { }
	// RVA: 0x24b58a0 VA: 0x7594acd8a0
	public Void InitData(SandboxV2Data sandboxV2Data, ProfessionCategory professionCategory, Int32 index) { }
	// RVA: 0x24b53ec VA: 0x7594acd3ec
	public Void AddCharInBuffViewModel(SandboxV2CharViewModel charViewModel) { }
	// RVA: 0x24b5538 VA: 0x7594acd538
	public Void RemoveCharInBuffViewModel(SandboxV2CharViewModel charViewModel) { }
	// RVA: 0x24b5714 VA: 0x7594acd714
	public Void ClearCharsInBuffViewModel() { }
	// RVA: 0x24b5b50 VA: 0x7594acdb50
	private SandboxV2LogisticsData _GetLogisticsDataByProfession(SandboxV2Data gameData, ProfessionCategory professionCategory) { }
	// RVA: 0x24b5830 VA: 0x7594acd830
	public Void .ctor() { }
}
```