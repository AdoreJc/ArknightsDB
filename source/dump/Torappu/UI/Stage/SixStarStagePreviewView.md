# SixStarStagePreviewView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `SixStarStagePreviewRankView _rankView`

- `SixStarStagePreviewRuneBarView _runeBarView`

- `GameObject _panelRewardGroup`

- `SimpleLayoutContent _advanceRuneLayoutContent`

- `UIAnimationLocation _showBaseAnimationLocation`

- `UIAnimationLocation _showAdvanceAnimationLocation`

- `Text _txtStartBattle`

- `Boolean m_isInited`

- `UIStateFinder m_uiStateFinder`

- `UIBiAnimClipSwitchTween m_runeModeSwitchTween`

- `StageViewModel m_stageModel`

- `SixStarStagePreviewAdvanceDescViewModel m_advanceDescViewModel`

- `ListAdapter m_listAdapter`


## Methods

- `Void _InitIfNot()`

- `Boolean _CheckIfNeedRuneSelect(StageViewModel)`

- `Void _RaiseTutorialSignal()`

- `Void OnRewardGroupBtnClick()`

- `Void OnSixStarStartBattleBtnClick()`

- `Boolean <>xLuaBaseProxy_OnZoneViewChanged(IStageSelectHandler, StageViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarStagePreviewView : StagePreviewInfoBasicPanel
{
	private SixStarStagePreviewRankView _rankView; // 0x148
	private SixStarStagePreviewRuneBarView _runeBarView; // 0x150
	private GameObject _panelRewardGroup; // 0x158
	private SimpleLayoutContent _advanceRuneLayoutContent; // 0x160
	private UIAnimationLocation _showBaseAnimationLocation; // 0x168
	private UIAnimationLocation _showAdvanceAnimationLocation; // 0x178
	private Text _txtStartBattle; // 0x188
	private Boolean m_isInited; // 0x190
	private UIStateFinder m_uiStateFinder; // 0x198
	private UIBiAnimClipSwitchTween m_runeModeSwitchTween; // 0x1a8
	private StageViewModel m_stageModel; // 0x1b0
	private SixStarStagePreviewAdvanceDescViewModel m_advanceDescViewModel; // 0x1b8
	private ListAdapter m_listAdapter; // 0x1c0
	private static DelegateBridge __Hotfix0_OnZoneViewChanged; // 0x0
	private static DelegateBridge __Hotfix0_SelectStageViewModel; // 0x8
	private static DelegateBridge __Hotfix0_CheckToShow; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__CheckIfNeedRuneSelect; // 0x20
	private static DelegateBridge __Hotfix0__RaiseTutorialSignal; // 0x28
	private static DelegateBridge __Hotfix0_OnRewardGroupBtnClick; // 0x30
	private static DelegateBridge __Hotfix0_OnSixStarStartBattleBtnClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2f4cb80 VA: 0x7595564b80
	protected override Boolean OnZoneViewChanged(IStageSelectHandler zoneModel, StageViewModel stageModel) { }
	// RVA: 0x2f4cfa8 VA: 0x7595564fa8
	protected override Boolean SelectStageViewModel(IStageSelectHandler zoneModel, out StageViewModel stageModel) { }
	// RVA: 0x2f4d0c0 VA: 0x75955650c0
	protected override Boolean CheckToShow(IStageSelectHandler zoneModel) { }
	// RVA: 0x2f4cdf0 VA: 0x7595564df0
	private Void _InitIfNot() { }
	// RVA: 0x2f4d248 VA: 0x7595565248
	private Boolean _CheckIfNeedRuneSelect(StageViewModel stageModel) { }
	// RVA: 0x2f4cf44 VA: 0x7595564f44
	private Void _RaiseTutorialSignal() { }
	// RVA: 0x2f4d328 VA: 0x7595565328
	public Void OnRewardGroupBtnClick() { }
	// RVA: 0x2f4d3cc VA: 0x75955653cc
	public Void OnSixStarStartBattleBtnClick() { }
	// RVA: 0x2f4d4a8 VA: 0x75955654a8
	public Void .ctor() { }
	// RVA: 0x2f4d554 VA: 0x7595565554
	private Boolean <>xLuaBaseProxy_OnZoneViewChanged(IStageSelectHandler P0, StageViewModel P1) { }
}
```