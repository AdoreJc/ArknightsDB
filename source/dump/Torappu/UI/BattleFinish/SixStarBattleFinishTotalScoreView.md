# SixStarBattleFinishTotalScoreView

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `Text _textPrefScore`

- `Text _textCurScore`

- `Single _panelTweenTargetY`

- `RectTransform _panelScore`

- `Int32 m_totalScoreBeforeBattle`

- `Int32 m_totalScoreAfterBattle`

- `Int32 m_curCountTotalScore`


## Methods

- `Void _ResetPanelPos()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class SixStarBattleFinishTotalScoreView : SixStarBattleFinishTimeTickListener
{
	private const Single PANEL_TWEEN_DURATION; // 0x0
	private Text _textPrefScore; // 0x18
	private Text _textCurScore; // 0x20
	private Single _panelTweenTargetY; // 0x28
	private RectTransform _panelScore; // 0x30
	private Int32 m_totalScoreBeforeBattle; // 0x38
	private Int32 m_totalScoreAfterBattle; // 0x3c
	private Int32 m_curCountTotalScore; // 0x40
	private static DelegateBridge __Hotfix0_OnSetData; // 0x0
	private static DelegateBridge __Hotfix0_OnTriggerTick; // 0x8
	private static DelegateBridge __Hotfix0__ResetPanelPos; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2e94ddc VA: 0x75954acddc
	public override Void OnSetData(SixStarBattleFinishViewModel viewModel) { }
	// RVA: 0x2e94fc0 VA: 0x75954acfc0
	public override Void OnTriggerTick() { }
	// RVA: 0x2e95124 VA: 0x75954ad124
	private Void _ResetPanelPos() { }
	// RVA: 0x2e951e0 VA: 0x75954ad1e0
	public Void .ctor() { }
}
```