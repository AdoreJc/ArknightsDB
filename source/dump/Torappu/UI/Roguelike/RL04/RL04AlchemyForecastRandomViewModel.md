# RL04AlchemyForecastRandomViewModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Boolean <isInfoValid>k__BackingField`

- `Single <relicProp>k__BackingField`

- `Single <shieldProp>k__BackingField`

- `Single <populationProp>k__BackingField`

- `AlchemyPoolRarityType <poolRarity>k__BackingField`

- `Int32 <rewardRarityMaxCount>k__BackingField`


## Properties

- `Boolean isInfoValid`

- `Single relicProp`

- `Single shieldProp`

- `Single populationProp`

- `AlchemyPoolRarityType poolRarity`

- `Int32 rewardRarityMaxCount`


## Methods

- `Boolean get_isInfoValid()`

- `Void set_isInfoValid(Boolean)`

- `Single get_relicProp()`

- `Void set_relicProp(Single)`

- `Single get_shieldProp()`

- `Void set_shieldProp(Single)`

- `Single get_populationProp()`

- `Void set_populationProp(Single)`

- `AlchemyPoolRarityType get_poolRarity()`

- `Void set_poolRarity(AlchemyPoolRarityType)`

- `Int32 get_rewardRarityMaxCount()`

- `Void set_rewardRarityMaxCount(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemyForecastRandomViewModel : IHotfixable
{
	private Boolean <isInfoValid>k__BackingField; // 0x10
	private Single <relicProp>k__BackingField; // 0x14
	private Single <shieldProp>k__BackingField; // 0x18
	private Single <populationProp>k__BackingField; // 0x1c
	private AlchemyPoolRarityType <poolRarity>k__BackingField; // 0x20
	private Int32 <rewardRarityMaxCount>k__BackingField; // 0x24
	private List`1 m_rewardRarityItemViewModels; // 0x28
	private static DelegateBridge __Hotfix0_get_isInfoValid; // 0x0
	private static DelegateBridge __Hotfix0_set_isInfoValid; // 0x8
	private static DelegateBridge __Hotfix0_get_relicProp; // 0x10
	private static DelegateBridge __Hotfix0_set_relicProp; // 0x18
	private static DelegateBridge __Hotfix0_get_shieldProp; // 0x20
	private static DelegateBridge __Hotfix0_set_shieldProp; // 0x28
	private static DelegateBridge __Hotfix0_get_populationProp; // 0x30
	private static DelegateBridge __Hotfix0_set_populationProp; // 0x38
	private static DelegateBridge __Hotfix0_get_poolRarity; // 0x40
	private static DelegateBridge __Hotfix0_set_poolRarity; // 0x48
	private static DelegateBridge __Hotfix0_get_rewardRarityMaxCount; // 0x50
	private static DelegateBridge __Hotfix0_set_rewardRarityMaxCount; // 0x58
	private static DelegateBridge __Hotfix0_get_rewardRarityItemViewModels; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68
	private static DelegateBridge _c__Hotfix1_ctor; // 0x70
	private static DelegateBridge __Hotfix0_EMPTY; // 0x78

	public Boolean isInfoValid { get; set; }
	public Single relicProp { get; set; }
	public Single shieldProp { get; set; }
	public Single populationProp { get; set; }
	public AlchemyPoolRarityType poolRarity { get; set; }
	public Int32 rewardRarityMaxCount { get; set; }
	public List`1 rewardRarityItemViewModels { get; }

	// RVA: 0x2afe2f8 VA: 0x75951162f8
	public Boolean get_isInfoValid() { }
	// RVA: 0x2afe360 VA: 0x7595116360
	private Void set_isInfoValid(Boolean value) { }
	// RVA: 0x2afe3e0 VA: 0x75951163e0
	public Single get_relicProp() { }
	// RVA: 0x2afe448 VA: 0x7595116448
	private Void set_relicProp(Single value) { }
	// RVA: 0x2afe4c4 VA: 0x75951164c4
	public Single get_shieldProp() { }
	// RVA: 0x2afe52c VA: 0x759511652c
	private Void set_shieldProp(Single value) { }
	// RVA: 0x2afe5a8 VA: 0x75951165a8
	public Single get_populationProp() { }
	// RVA: 0x2afe610 VA: 0x7595116610
	private Void set_populationProp(Single value) { }
	// RVA: 0x2afe68c VA: 0x759511668c
	public AlchemyPoolRarityType get_poolRarity() { }
	// RVA: 0x2afe6f4 VA: 0x75951166f4
	private Void set_poolRarity(AlchemyPoolRarityType value) { }
	// RVA: 0x2afe770 VA: 0x7595116770
	public Int32 get_rewardRarityMaxCount() { }
	// RVA: 0x2afe7d8 VA: 0x75951167d8
	public Void set_rewardRarityMaxCount(Int32 value) { }
	// RVA: 0x2afe854 VA: 0x7595116854
	public List`1 get_rewardRarityItemViewModels() { }
	// RVA: 0x2afe8bc VA: 0x75951168bc
	private Void .ctor() { }
	// RVA: 0x2afe980 VA: 0x7595116980
	public Void .ctor(Int32 maxAlchemyPoolRarity, RoguelikeAlchemyData alchemyData) { }
	// RVA: 0x2afebfc VA: 0x7595116bfc
	public static RL04AlchemyForecastRandomViewModel EMPTY(Int32 maxAlchemyPoolRarity) { }
}
```