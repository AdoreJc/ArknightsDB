# RL04ClassicEndingTopView

**Namespace:** `Torappu.UI.Roguelike.RL04`


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

- `String _GetFailEndingIconName(RoguelikeClassicEndingViewModel)`

- `String _GetEndingIconName(RoguelikeClassicEndingViewModel)`

- `Void OnShowReportClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04ClassicEndingTopView : RoguelikeClassicEndingTopView
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
	private static DelegateBridge __Hotfix0__GetFailEndingIconName; // 0x20
	private static DelegateBridge __Hotfix0__GetEndingIconName; // 0x28
	private static DelegateBridge __Hotfix0_OnShowReportClicked; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override Action onShowReport { set; }
	protected override String showAnimName { get; }

	// RVA: 0x2b10a8c VA: 0x7595128a8c
	public override Void set_onShowReport(Action value) { }
	// RVA: 0x2b10b10 VA: 0x7595128b10
	protected override String get_showAnimName() { }
	// RVA: 0x2b10b8c VA: 0x7595128b8c
	protected override Void Render(RoguelikeEndingControllerBase controller, RoguelikeClassicEndingViewModel endingViewModel) { }
	// RVA: 0x2b10cd4 VA: 0x7595128cd4
	private Void _RenderDifficultIcon(RoguelikeClassicEndingViewModel endingViewModel) { }
	// RVA: 0x2b10e5c VA: 0x7595128e5c
	private String _GetFailEndingIconName(RoguelikeClassicEndingViewModel endingViewModel) { }
	// RVA: 0x2b10f38 VA: 0x7595128f38
	private String _GetEndingIconName(RoguelikeClassicEndingViewModel endingViewModel) { }
	// RVA: 0x2b11038 VA: 0x7595129038
	public Void OnShowReportClicked() { }
	// RVA: 0x2b110bc VA: 0x75951290bc
	public Void .ctor() { }
}
```