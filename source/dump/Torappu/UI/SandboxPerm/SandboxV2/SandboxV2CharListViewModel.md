# SandboxV2CharListViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2CharViewModel m_lastSelectViewModel`

- `String topicId`

- `SandboxV2SelectPluginLogic logic`

- `SandboxV2CharSelectTabEnum attryTabType`

- `Boolean needShuffle`

- `SandboxV2AdminCharSelectStateMode mode`

- `SandboxV2ShuffleViewModel shuffleViewModel`

- `SandboxV2ExpeditionCharSelectViewModel expeditionViewModel`

- `SandboxV2LogisticsCharSelectViewModel logisticsViewModel`

- `Boolean showPopView`

- `Int32 focusIndex`

- `Int32 focusSeqNun`

- `Int32 selectMaxCount`

- `Int32 selectCount`


## Properties

- `SandboxV2CharViewModel lastSelectViewModel`


## Methods

- `SandboxV2CharViewModel get_lastSelectViewModel()`

- `Void set_lastSelectViewModel(SandboxV2CharViewModel)`

- `SandboxV2CharViewModel GetCharViewModelByInstId(Int32)`

- `Void InitViewModel(OpenOption)`

- `Void OnCharClear()`

- `Boolean _IsCharFiltered(OpenOption, SandboxV2CharViewModel)`

- `Void SortViewModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CharListViewModel : IHotfixable
{
	private SandboxV2CharViewModel m_lastSelectViewModel; // 0x10
	public String topicId; // 0x18
	public SandboxV2SelectPluginLogic logic; // 0x20
	public SandboxV2CharSelectTabEnum attryTabType; // 0x28
	public List`1 charViewModels; // 0x30
	public List`1 selectedViewModels; // 0x38
	public List`1 resultList; // 0x40
	public Boolean needShuffle; // 0x48
	public SandboxV2AdminCharSelectStateMode mode; // 0x4c
	public SandboxV2ShuffleViewModel shuffleViewModel; // 0x50
	public SandboxV2ExpeditionCharSelectViewModel expeditionViewModel; // 0x58
	public SandboxV2LogisticsCharSelectViewModel logisticsViewModel; // 0x60
	public Boolean showPopView; // 0x68
	public Int32 focusIndex; // 0x6c
	public Int32 focusSeqNun; // 0x70
	public Int32 selectMaxCount; // 0x74
	public Int32 selectCount; // 0x78
	private static DelegateBridge __Hotfix0_get_lastSelectViewModel; // 0x0
	private static DelegateBridge __Hotfix0_set_lastSelectViewModel; // 0x8
	private static DelegateBridge __Hotfix0_GetCharViewModelShuffledList; // 0x10
	private static DelegateBridge __Hotfix0_GetCharViewModelByInstId; // 0x18
	private static DelegateBridge __Hotfix0_InitViewModel; // 0x20
	private static DelegateBridge __Hotfix0_OnCharClear; // 0x28
	private static DelegateBridge __Hotfix0__IsCharFiltered; // 0x30
	private static DelegateBridge __Hotfix0_SortViewModel; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public SandboxV2CharViewModel lastSelectViewModel { get; set; }

	// RVA: 0x24adb78 VA: 0x7594ac5b78
	public SandboxV2CharViewModel get_lastSelectViewModel() { }
	// RVA: 0x24ad090 VA: 0x7594ac5090
	public Void set_lastSelectViewModel(SandboxV2CharViewModel value) { }
	// RVA: 0x24b0d9c VA: 0x7594ac8d9c
	public List`1 GetCharViewModelShuffledList() { }
	// RVA: 0x24acf7c VA: 0x7594ac4f7c
	public SandboxV2CharViewModel GetCharViewModelByInstId(Int32 instId) { }
	// RVA: 0x24b15c4 VA: 0x7594ac95c4
	public Void InitViewModel(OpenOption option) { }
	// RVA: 0x24b27f0 VA: 0x7594aca7f0
	public Void OnCharClear() { }
	// RVA: 0x24b2388 VA: 0x7594aca388
	private Boolean _IsCharFiltered(OpenOption options, SandboxV2CharViewModel charViewModel) { }
	// RVA: 0x24b2b34 VA: 0x7594acab34
	public Void SortViewModel() { }
	// RVA: 0x24b2ca8 VA: 0x7594acaca8
	public Void .ctor() { }
}
```