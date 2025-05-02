# DeepSeaRPBattleNodeDetailViewModel

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `DeepSeaRPBattleNodeModel nodeModel`

- `Boolean isSelectedHard`

- `Boolean isShowDetail`

- `Boolean isSelectedStory`


## Properties

- `StageViewModel currSelectStage`


## Methods

- `StageViewModel get_currSelectStage()`

- `String GetPreviewStageId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPBattleNodeDetailViewModel : IHotfixable
{
	public DeepSeaRPBattleNodeModel nodeModel; // 0x10
	public Boolean isSelectedHard; // 0x18
	public Boolean isShowDetail; // 0x19
	public Boolean isSelectedStory; // 0x1a
	private static DelegateBridge __Hotfix0_get_currSelectStage; // 0x0
	private static DelegateBridge __Hotfix0_GetPreviewStageId; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public StageViewModel currSelectStage { get; }

	// RVA: 0x29e6780 VA: 0x7594ffe780
	public StageViewModel get_currSelectStage() { }
	// RVA: 0x29e6808 VA: 0x7594ffe808
	public String GetPreviewStageId() { }
	// RVA: 0x29e688c VA: 0x7594ffe88c
	public Void .ctor() { }
}
```