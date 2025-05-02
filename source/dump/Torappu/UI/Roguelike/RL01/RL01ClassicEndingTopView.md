# RL01ClassicEndingTopView

**Namespace:** `Torappu.UI.Roguelike.RL01`


## Fields

- `String _failTitleId`

- `UIAtlasObject _atlasObject`

- `Action m_onShowReport`


## Methods

- `Void OnShowReportClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL01
public class RL01ClassicEndingTopView : RoguelikeClassicEndingTopView
{
	private const String SHOW_ANIM_NAME; // 0x0
	private String _failTitleId; // 0x38
	private UIAtlasObject _atlasObject; // 0x40
	private Action m_onShowReport; // 0x48
	private static DelegateBridge __Hotfix0_set_onShowReport; // 0x0
	private static DelegateBridge __Hotfix0_get_showAnimName; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnShowReportClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override Action onShowReport { set; }
	protected override String showAnimName { get; }

	// RVA: 0x2b76ed8 VA: 0x759518eed8
	public override Void set_onShowReport(Action value) { }
	// RVA: 0x2b76f5c VA: 0x759518ef5c
	protected override String get_showAnimName() { }
	// RVA: 0x2b76fd8 VA: 0x759518efd8
	protected override Void Render(RoguelikeEndingControllerBase controller, RoguelikeClassicEndingViewModel endingViewModel) { }
	// RVA: 0x2b770d4 VA: 0x759518f0d4
	public Void OnShowReportClicked() { }
	// RVA: 0x2b77158 VA: 0x759518f158
	public Void .ctor() { }
}
```