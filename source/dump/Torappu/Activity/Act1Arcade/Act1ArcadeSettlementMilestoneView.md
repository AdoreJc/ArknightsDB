# Act1ArcadeSettlementMilestoneView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Image _imgToken`

- `Text _textMilestoneReward`

- `Text _textMilestoneLevel`

- `Text _textMilestoneProgressCur`

- `Text _textMilestoneProgressTotal`

- `Image _imgMilestoneProgress`

- `Image _imgMilestoneProgressFx`

- `GameObject _panelMilestoneMaxLevelFx`

- `TwoStateToggle _milestoneLevelStateToggle`

- `Act1ArcadeSettlementModel m_settlementModel`

- `UIItemViewModel m_itemViewModel`

- `Boolean m_isReachMax`

- `TemplateActivityMileStoneItemModel m_catchedMilestoneModel`

- `Int32 m_tweenTargetScore`

- `Int32 m_catchedMilestoneScore`

- `Int32 m_prefLevelScoreNum`

- `Tween m_tween`


## Methods

- `Void OnRender(Act1ArcadeSettlementModel)`

- `Void _ShowIcon()`

- `Void _ShowMilestone()`

- `IEnumerator _PlayMilestoneAnim()`

- `Int32 _TweenScoreGetter()`

- `Void _TweenScoreSetter(Int32)`

- `Void _RefreshMilestoneShow()`

- `Boolean <_PlayMilestoneAnim>b__22_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeSettlementMilestoneView : MonoBehaviour, IHotfixable
{
	private const Single MILESTONE_TWEEN_DURATION; // 0x0
	private const Single MILESTONE_TWEEN_DELAY; // 0x0
	private Image _imgToken; // 0x18
	private Text _textMilestoneReward; // 0x20
	private Text _textMilestoneLevel; // 0x28
	private Text _textMilestoneProgressCur; // 0x30
	private Text _textMilestoneProgressTotal; // 0x38
	private Image _imgMilestoneProgress; // 0x40
	private Image _imgMilestoneProgressFx; // 0x48
	private GameObject _panelMilestoneMaxLevelFx; // 0x50
	private TwoStateToggle _milestoneLevelStateToggle; // 0x58
	private Act1ArcadeSettlementModel m_settlementModel; // 0x60
	private UIItemViewModel m_itemViewModel; // 0x68
	private Boolean m_isReachMax; // 0x70
	private TemplateActivityMileStoneItemModel m_catchedMilestoneModel; // 0x78
	private Int32 m_tweenTargetScore; // 0x80
	private Int32 m_catchedMilestoneScore; // 0x84
	private Int32 m_prefLevelScoreNum; // 0x88
	private Tween m_tween; // 0x90
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0__ShowIcon; // 0x8
	private static DelegateBridge __Hotfix0__ShowMilestone; // 0x10
	private static DelegateBridge __Hotfix0__PlayMilestoneAnim; // 0x18
	private static DelegateBridge __Hotfix0__TweenScoreGetter; // 0x20
	private static DelegateBridge __Hotfix0__TweenScoreSetter; // 0x28
	private static DelegateBridge __Hotfix0__RefreshMilestoneShow; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3406550 VA: 0x7595a1e550
	public Void OnRender(Act1ArcadeSettlementModel model) { }
	// RVA: 0x3406614 VA: 0x7595a1e614
	private Void _ShowIcon() { }
	// RVA: 0x34066e4 VA: 0x7595a1e6e4
	private Void _ShowMilestone() { }
	// RVA: 0x340691c VA: 0x7595a1e91c
	private IEnumerator _PlayMilestoneAnim() { }
	// RVA: 0x34069f0 VA: 0x7595a1e9f0
	private Int32 _TweenScoreGetter() { }
	// RVA: 0x340680c VA: 0x7595a1e80c
	private Void _TweenScoreSetter(Int32 newScore) { }
	// RVA: 0x3406a58 VA: 0x7595a1ea58
	private Void _RefreshMilestoneShow() { }
	// RVA: 0x3406c28 VA: 0x7595a1ec28
	public Void .ctor() { }
	// RVA: 0x3406cd8 VA: 0x7595a1ecd8
	private Boolean <_PlayMilestoneAnim>b__22_0() { }
}
```