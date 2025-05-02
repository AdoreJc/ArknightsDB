# SixStarBattleFinishRankView

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `Int32 m_rankBeforeBattle`

- `Int32 m_rankAfterBattle`

- `Int32 m_curCountRank`


## Methods

- `Void _PlayStarAudio()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class SixStarBattleFinishRankView : SixStarBattleFinishTimeTickListener, IHotfixable
{
	private GameObject[] _rankItems; // 0x18
	private Int32 m_rankBeforeBattle; // 0x20
	private Int32 m_rankAfterBattle; // 0x24
	private Int32 m_curCountRank; // 0x28
	private static DelegateBridge __Hotfix0_OnSetData; // 0x0
	private static DelegateBridge __Hotfix0_OnTriggerTick; // 0x8
	private static DelegateBridge __Hotfix0__PlayStarAudio; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2e949d0 VA: 0x75954ac9d0
	public override Void OnSetData(SixStarBattleFinishViewModel viewModel) { }
	// RVA: 0x2e94c4c VA: 0x75954acc4c
	public override Void OnTriggerTick() { }
	// RVA: 0x2e94ba4 VA: 0x75954acba4
	private Void _PlayStarAudio() { }
	// RVA: 0x2e94d00 VA: 0x75954acd00
	public Void .ctor() { }
}
```