# RL02ClassicEndingTopView

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `String _failTitleId`

- `UIAtlasObject _atlasObject`

- `GameObject _pnlSuccess`

- `GameObject _pnlFailed`

- `Action m_onShowReport`


## Methods

- `Void OnShowReportClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02ClassicEndingTopView : RoguelikeClassicEndingTopView
{
	private const String SHOW_ANIM_NAME; // 0x0
	private String _failTitleId; // 0x38
	private UIAtlasObject _atlasObject; // 0x40
	private GameObject _pnlSuccess; // 0x48
	private GameObject _pnlFailed; // 0x50
	private Action m_onShowReport; // 0x58
	private static DelegateBridge __Hotfix0_set_onShowReport; // 0x0
	private static DelegateBridge __Hotfix0_get_showAnimName; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnShowReportClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override Action onShowReport { set; }
	protected override String showAnimName { get; }

	// RVA: 0x2b5d46c VA: 0x759517546c
	public override Void set_onShowReport(Action value) { }
	// RVA: 0x2b5d4f0 VA: 0x75951754f0
	protected override String get_showAnimName() { }
	// RVA: 0x2b5d56c VA: 0x759517556c
	protected override Void Render(RoguelikeEndingControllerBase controller, RoguelikeClassicEndingViewModel endingViewModel) { }
	// RVA: 0x2b5d690 VA: 0x7595175690
	public Void OnShowReportClicked() { }
	// RVA: 0x2b5d714 VA: 0x7595175714
	public Void .ctor() { }
}
```