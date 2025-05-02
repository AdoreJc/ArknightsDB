# SandboxV2DungeonMiscLogisticsEffectViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Boolean isEnable`

- `Int32 obtainedDrink`

- `Int32 logisticsDrinkCost`

- `SandboxV2DungeonMiscLogisticsEffectItemComparer m_comparer`


## Methods

- `Void LoadData(SandboxV2Data, PlayerSandboxV2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonMiscLogisticsEffectViewModel : IHotfixable
{
	public Boolean isEnable; // 0x10
	public List`1 charInstIds; // 0x18
	public Int32 obtainedDrink; // 0x20
	public Int32 logisticsDrinkCost; // 0x24
	public ListDict`2 logisticsEffects; // 0x28
	private SandboxV2DungeonMiscLogisticsEffectItemComparer m_comparer; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x25b2c80 VA: 0x7594bcac80
	public Void LoadData(SandboxV2Data topicDetailData, PlayerSandboxV2 playerTopicData) { }
	// RVA: 0x25b313c VA: 0x7594bcb13c
	public Void .ctor() { }
}
```