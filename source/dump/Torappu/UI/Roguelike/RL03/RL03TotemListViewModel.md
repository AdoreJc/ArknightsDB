# RL03TotemListViewModel

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `String m_topicId`

- `RL03TotemListItemViewModel m_locationBossViewModel`

- `RL03TotemListItemViewModel m_effectBossViewModel`

- `RL03TotemListItemViewModel m_selectedLocationViewModel`

- `RL03TotemListItemViewModel m_selectedEffectViewModel`

- `Int32 m_sequenceNum`


## Properties

- `Int32 sequenceNum`

- `RL03TotemViewModel selectedLocationTotemViewModel`

- `RL03TotemViewModel selectedEffectTotemViewModel`


## Methods

- `Int32 get_sequenceNum()`

- `RL03TotemViewModel get_selectedLocationTotemViewModel()`

- `RL03TotemViewModel get_selectedEffectTotemViewModel()`

- `Void LoadData(String, Int32)`

- `Void UpdateTotemDisplayTypeWithMapStatus(List`1)`

- `TotemItemDisplayType GetTotemItemDisplayType(String, String)`

- `Void SelectTotemItem(String, String)`

- `Void _GeneViewModels(Totem)`

- `Void _AddBlockItemViewModels(RoguelikeTotemPosType, RL03TotemListItemViewModel, List`1, ref)`

- `Void _UpdateViewModelsAfterSelectChanged()`

- `Boolean _CheckIfTotemResonance(RL03TotemListItemViewModel, RL03TotemListItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TotemListViewModel : IHotfixable
{
	private String m_topicId; // 0x10
	public List`1 wholeItemViewModels; // 0x18
	private Dictionary`2 m_locationInstItemDict; // 0x20
	private Dictionary`2 m_effectInstItemDict; // 0x28
	private Dictionary`2 m_locationNormalDisplayTypeDict; // 0x30
	private Dictionary`2 m_effectNormalDisplayTypeDict; // 0x38
	private RL03TotemListItemViewModel m_locationBossViewModel; // 0x40
	private RL03TotemListItemViewModel m_effectBossViewModel; // 0x48
	private RL03TotemListItemViewModel m_selectedLocationViewModel; // 0x50
	private RL03TotemListItemViewModel m_selectedEffectViewModel; // 0x58
	private Int32 m_sequenceNum; // 0x60
	private List`1 m_viewSelectStatusList; // 0x68
	private static DelegateBridge __Hotfix0_get_viewSelectStatusList; // 0x0
	private static DelegateBridge __Hotfix0_get_sequenceNum; // 0x8
	private static DelegateBridge __Hotfix0_get_locationInstItemDict; // 0x10
	private static DelegateBridge __Hotfix0_get_selectedLocationTotemViewModel; // 0x18
	private static DelegateBridge __Hotfix0_get_selectedEffectTotemViewModel; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0_UpdateTotemDisplayTypeWithMapStatus; // 0x30
	private static DelegateBridge __Hotfix0_GetTotemItemDisplayType; // 0x38
	private static DelegateBridge __Hotfix0_SelectTotemItem; // 0x40
	private static DelegateBridge __Hotfix0__GeneViewModels; // 0x48
	private static DelegateBridge __Hotfix0__AddBlockItemViewModels; // 0x50
	private static DelegateBridge __Hotfix0__UpdateViewModelsAfterSelectChanged; // 0x58
	private static DelegateBridge __Hotfix0__CheckIfTotemResonance; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public List`1 viewSelectStatusList { get; }
	public Int32 sequenceNum { get; }
	public Dictionary`2 locationInstItemDict { get; }
	public RL03TotemViewModel selectedLocationTotemViewModel { get; }
	public RL03TotemViewModel selectedEffectTotemViewModel { get; }

	// RVA: 0x2ba8910 VA: 0x75951c0910
	public List`1 get_viewSelectStatusList() { }
	// RVA: 0x2ba7da8 VA: 0x75951bfda8
	public Int32 get_sequenceNum() { }
	// RVA: 0x2badd9c VA: 0x75951c5d9c
	public Dictionary`2 get_locationInstItemDict() { }
	// RVA: 0x2bae61c VA: 0x75951c661c
	public RL03TotemViewModel get_selectedLocationTotemViewModel() { }
	// RVA: 0x2bae694 VA: 0x75951c6694
	public RL03TotemViewModel get_selectedEffectTotemViewModel() { }
	// RVA: 0x2badc90 VA: 0x75951c5c90
	public Void LoadData(String topicId, Int32 sequenceNum) { }
	// RVA: 0x2bade04 VA: 0x75951c5e04
	public Void UpdateTotemDisplayTypeWithMapStatus(List`1 cantUseInMapLocationTotemList) { }
	// RVA: 0x2bae338 VA: 0x75951c6338
	public TotemItemDisplayType GetTotemItemDisplayType(String totemId, String instId) { }
	// RVA: 0x2bae448 VA: 0x75951c6448
	public Void SelectTotemItem(String totemId, String instId) { }
	// RVA: 0x2bafa24 VA: 0x75951c7a24
	private Void _GeneViewModels(Totem playerTotem) { }
	// RVA: 0x2bb0638 VA: 0x75951c8638
	private Void _AddBlockItemViewModels(RoguelikeTotemPosType posType, RL03TotemListItemViewModel divinationItemViewModel, List`1 itemViewModels, ref List`1 wholeViewModels) { }
	// RVA: 0x2baff70 VA: 0x75951c7f70
	private Void _UpdateViewModelsAfterSelectChanged() { }
	// RVA: 0x2bb0a64 VA: 0x75951c8a64
	private Boolean _CheckIfTotemResonance(RL03TotemListItemViewModel locationViewModel, RL03TotemListItemViewModel effectViewModel) { }
	// RVA: 0x2badad0 VA: 0x75951c5ad0
	public Void .ctor() { }
}
```