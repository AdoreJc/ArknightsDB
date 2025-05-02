# SpecialStoryStageViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Boolean spstPrevUnlocked`

- `String spstPrevStageId`

- `PlayerSpecialStage spstStage`

- `Int32 spstProgress`

- `String spstImageId`


## Methods

- `Void <>xLuaBaseProxy_SetGameData(StageData, TimelyDropOptions, StageDiffGroupTable)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SpecialStoryStageViewModel : StageViewModel, IHotfixable
{
	public Dictionary`2 spstProgressDesc; // 0x148
	public List`1 spstRewards; // 0x150
	public Boolean spstPrevUnlocked; // 0x158
	public String spstPrevStageId; // 0x160
	public PlayerSpecialStage spstStage; // 0x168
	public Int32 spstProgress; // 0x170
	public List`1 spstUnlockStages; // 0x178
	public String spstImageId; // 0x180
	private const String SPECIAL_STORY_UNLOCK_TEMPLATE_READ_STORY; // 0x0
	private static DelegateBridge __Hotfix0_SetGameData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2f78420 VA: 0x7595590420
	public override Void SetGameData(StageData stageData, TimelyDropOptions timelyOptions, StageDiffGroupTable table) { }
	// RVA: 0x2f7922c VA: 0x759559122c
	public Void .ctor() { }
	// RVA: 0x2f79388 VA: 0x7595591388
	private Void <>xLuaBaseProxy_SetGameData(StageData P0, TimelyDropOptions P1, StageDiffGroupTable P2) { }
}
```