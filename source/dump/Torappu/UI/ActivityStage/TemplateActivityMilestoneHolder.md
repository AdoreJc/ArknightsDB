# TemplateActivityMilestoneHolder

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `TemplateActivityCommonMileStoneAdapter _adapter`

- `LoopHorizontalScrollRect _content`

- `GridLayoutGroup _layout`

- `Image _imgMilestoneIcon`

- `Text _textMilestoneCount`

- `TwoStateToggle _btnRewardToggle`

- `TemplateActivityMilestoneWidget _widget`

- `Single _durationTween`

- `Single _delayTween`

- `Boolean m_hasInited`

- `TweenWrapper m_focusTween`


## Methods

- `Void OnViewModelRefresh(TemplateActivityViewModel)`

- `Void _InitIfNot()`

- `Void FocusOnIdx(Int32)`

- `Sprite _LoadItemIcon(String)`

- `Single <FocusOnIdx>b__14_0()`

- `Void <FocusOnIdx>b__14_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityMilestoneHolder : MonoBehaviour, IBaseActViewBinder, IHotfixable
{
	private const Int32 SLIDE_MAX_LENGTH; // 0x0
	private TemplateActivityCommonMileStoneAdapter _adapter; // 0x18
	private LoopHorizontalScrollRect _content; // 0x20
	private GridLayoutGroup _layout; // 0x28
	private Image _imgMilestoneIcon; // 0x30
	private Text _textMilestoneCount; // 0x38
	private TwoStateToggle _btnRewardToggle; // 0x40
	private TemplateActivityMilestoneWidget _widget; // 0x48
	private Single _durationTween; // 0x50
	private Single _delayTween; // 0x54
	private Boolean m_hasInited; // 0x58
	private TweenWrapper m_focusTween; // 0x60
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_FocusOnIdx; // 0x10
	private static DelegateBridge __Hotfix0__LoadItemIcon; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30a7408 VA: 0x75956bf408
	public Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x30a7668 VA: 0x75956bf668
	private Void _InitIfNot() { }
	// RVA: 0x309cda8 VA: 0x75956b4da8
	public Void FocusOnIdx(Int32 targetIndex) { }
	// RVA: 0x30a76dc VA: 0x75956bf6dc
	private Sprite _LoadItemIcon(String itemId) { }
	// RVA: 0x30a7834 VA: 0x75956bf834
	public Void .ctor() { }
	// RVA: 0x30a78b0 VA: 0x75956bf8b0
	private Single <FocusOnIdx>b__14_0() { }
	// RVA: 0x30a78cc VA: 0x75956bf8cc
	private Void <FocusOnIdx>b__14_1(Single value) { }
}
```