# StagePreviewNormalView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StagePreviewRankView _rankView`

- `Image _diffLogo`

- `Image _diffBackImg`

- `GameObject _diffGroupButton`

- `GameObject _diffGroupPartBtn`

- `Color _commonApCostColor`

- `Color _groupApCostColor`

- `Color _commonColor`

- `Color _toughColor`

- `GameObject _hasDiffPart`

- `Text _diffShortText`

- `Image _coloredBack`

- `Sprite _normalPart`

- `Sprite _toughPart`


## Methods

- `Void _RaiseTutorialSignal()`

- `Boolean <>xLuaBaseProxy_OnZoneViewChanged(IStageSelectHandler, StageViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StagePreviewNormalView : StagePreviewInfoBasicPanel
{
	protected StagePreviewRankView _rankView; // 0x148
	private Image _diffLogo; // 0x150
	private Image _diffBackImg; // 0x158
	private GameObject _diffGroupButton; // 0x160
	private GameObject _diffGroupPartBtn; // 0x168
	private Color _commonApCostColor; // 0x170
	private Color _groupApCostColor; // 0x180
	private Color _commonColor; // 0x190
	private Color _toughColor; // 0x1a0
	private GameObject _hasDiffPart; // 0x1b0
	private Text _diffShortText; // 0x1b8
	private Image _coloredBack; // 0x1c0
	private Sprite _normalPart; // 0x1c8
	private Sprite _toughPart; // 0x1d0
	private static DelegateBridge __Hotfix0_OnZoneViewChanged; // 0x0
	private static DelegateBridge __Hotfix0_SelectStageViewModel; // 0x8
	private static DelegateBridge __Hotfix0_CheckToShow; // 0x10
	private static DelegateBridge __Hotfix0__RaiseTutorialSignal; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2f9ac08 VA: 0x75955b2c08
	protected override Boolean OnZoneViewChanged(IStageSelectHandler zoneModel, StageViewModel stageModel) { }
	// RVA: 0x2f9afc4 VA: 0x75955b2fc4
	protected override Boolean SelectStageViewModel(IStageSelectHandler zoneModel, out StageViewModel stageModel) { }
	// RVA: 0x2f9b0ec VA: 0x75955b30ec
	protected override Boolean CheckToShow(IStageSelectHandler zoneModel) { }
	// RVA: 0x2f9af60 VA: 0x75955b2f60
	private Void _RaiseTutorialSignal() { }
	// RVA: 0x2f9b1e0 VA: 0x75955b31e0
	public Void .ctor() { }
	// RVA: 0x2f9b250 VA: 0x75955b3250
	private Boolean <>xLuaBaseProxy_OnZoneViewChanged(IStageSelectHandler P0, StageViewModel P1) { }
}
```