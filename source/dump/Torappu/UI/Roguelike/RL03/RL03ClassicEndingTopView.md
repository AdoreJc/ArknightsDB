# RL03ClassicEndingTopView

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `String _failTitleId`

- `String _failIconId`

- `UIAtlasObject _atlasObject`

- `UIAtlasImage _titleIcon`

- `GameObject _pnlSuccess`

- `GameObject _pnlFailed`

- `Action m_onShowReport`


## Methods

- `Void _RenderDifficultIcon(RoguelikeClassicEndingViewModel)`

- `Void OnShowReportClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03ClassicEndingTopView : RoguelikeClassicEndingTopView
{
	private const String SHOW_ANIM_NAME; // 0x0
	private String _failTitleId; // 0x38
	private String _failIconId; // 0x40
	private UIAtlasObject _atlasObject; // 0x48
	private UIAtlasImage _titleIcon; // 0x50
	private GameObject _pnlSuccess; // 0x58
	private GameObject _pnlFailed; // 0x60
	private Action m_onShowReport; // 0x68
	private static DelegateBridge __Hotfix0_set_onShowReport; // 0x0
	private static DelegateBridge __Hotfix0_get_showAnimName; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__RenderDifficultIcon; // 0x18
	private static DelegateBridge __Hotfix0_OnShowReportClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Action onShowReport { set; }
	protected override String showAnimName { get; }

	// RVA: 0x2b92070 VA: 0x75951aa070
	public override Void set_onShowReport(Action value) { }
	// RVA: 0x2b920f4 VA: 0x75951aa0f4
	protected override String get_showAnimName() { }
	// RVA: 0x2b92170 VA: 0x75951aa170
	protected override Void Render(RoguelikeEndingControllerBase controller, RoguelikeClassicEndingViewModel endingViewModel) { }
	// RVA: 0x2b922a0 VA: 0x75951aa2a0
	private Void _RenderDifficultIcon(RoguelikeClassicEndingViewModel endingViewModel) { }
	// RVA: 0x2b92430 VA: 0x75951aa430
	public Void OnShowReportClicked() { }
	// RVA: 0x2b924b4 VA: 0x75951aa4b4
	public Void .ctor() { }
}
```