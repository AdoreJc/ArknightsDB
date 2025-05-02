# DeepSeaRPBattlePreviewStateBean

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `DeepSeaRPBattleNodeDetailProperty nodeDetailProperty`

- `DeepSeaRPBattleNodeConfigProperty nodeConfigProperty`


## Properties

- `StageViewModel selectedStageModel`


## Methods

- `StageViewModel get_selectedStageModel()`

- `Void LoadData(DeepSeaRPBattleNodeModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPBattlePreviewStateBean : IStateBean, IHotfixable
{
	public DeepSeaRPBattleNodeDetailProperty nodeDetailProperty; // 0x10
	public DeepSeaRPBattleNodeConfigProperty nodeConfigProperty; // 0x18
	private static DelegateBridge __Hotfix0_get_selectedStageModel; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public StageViewModel selectedStageModel { get; }

	// RVA: 0x29e6968 VA: 0x7594ffe968
	public StageViewModel get_selectedStageModel() { }
	// RVA: 0x29e69f8 VA: 0x7594ffe9f8
	public Void LoadData(DeepSeaRPBattleNodeModel battleModel) { }
	// RVA: 0x29e6b28 VA: 0x7594ffeb28
	public Void .ctor() { }
}
```