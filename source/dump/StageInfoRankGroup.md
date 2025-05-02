# StageInfoRankGroup

**Namespace:** ` `


## Fields

- `GameObject _pnlRoot`

- `BattleFinishRankGroup _rankGroup`

- `GameObject _fourStarRankGroup`


## Methods

- `Void Render(Act24sideBattleInfoViewModel, Boolean, Boolean)`

- `Void _PlayFstarPopupSE()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class StageInfoRankGroup : IHotfixable
{
	private GameObject _pnlRoot; // 0x10
	private BattleFinishRankGroup _rankGroup; // 0x18
	private GameObject _fourStarRankGroup; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__PlayFstarPopupSE; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x329042c VA: 0x75958a842c
	public Void Render(Act24sideBattleInfoViewModel viewModel, Boolean active, Boolean isPrewarm) { }
	// RVA: 0x329057c VA: 0x75958a857c
	private Void _PlayFstarPopupSE() { }
	// RVA: 0x3290624 VA: 0x75958a8624
	public Void .ctor() { }
}
```