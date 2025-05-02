# FifthAnnivExplorePlanView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `Text _textPlanTypeName`

- `Text _textPlanName`

- `Text _textDesc`

- `SimpleLayoutContent _optionList`

- `UIAnimationLocation _animEnter`

- `UIAnimationLocation _animSwitch`

- `GameObject _btnPrevGo`

- `UIAtlasImage _imgPrevEventIcon`

- `GameObject _btnNextGo`

- `UIAtlasImage _imgNextEventIcon`

- `UIAtlasObject _iconAtlas`

- `UIAtlasImage _imgEventIcon`

- `GameObject _eventIconGo`

- `Text _textStageNum`

- `GameObject _stageNumGo`

- `FifthAnnivExplorePlanModel m_currPlanModel`

- `Boolean m_hasInited`

- `OptionListAdapter m_optionListAdapter`

- `UIStateFinder m_stateFinder`

- `Int32 m_cacheSwitchPlanSeqNum`

- `Tween m_switchTween`


## Methods

- `Void _PlaySwitchAnimIfNeed()`

- `Void _RenderEventPart()`

- `Void _RenderTargetPart()`

- `Void _InitIfNot()`

- `Void EventOnBtnPrevClick()`

- `Void EventOnBtnNextClick()`

- `UIAnimationLocation <>xLuaBaseProxy_GetEnterAnim()`

- `Boolean <>xLuaBaseProxy_IsTweenPlaying()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExplorePlanView : FifthAnnivExploreDetailViewBase
{
	private Text _textPlanTypeName; // 0x38
	private Text _textPlanName; // 0x40
	private Text _textDesc; // 0x48
	private SimpleLayoutContent _optionList; // 0x50
	private UIAnimationLocation _animEnter; // 0x58
	private UIAnimationLocation _animSwitch; // 0x68
	private GameObject _btnPrevGo; // 0x78
	private UIAtlasImage _imgPrevEventIcon; // 0x80
	private GameObject _btnNextGo; // 0x88
	private UIAtlasImage _imgNextEventIcon; // 0x90
	private UIAtlasObject _iconAtlas; // 0x98
	private UIAtlasImage _imgEventIcon; // 0xa0
	private GameObject _eventIconGo; // 0xa8
	private Text _textStageNum; // 0xb0
	private GameObject _stageNumGo; // 0xb8
	private FifthAnnivExplorePlanModel m_currPlanModel; // 0xc0
	private Boolean m_hasInited; // 0xc8
	private OptionListAdapter m_optionListAdapter; // 0xd0
	private UIStateFinder m_stateFinder; // 0xd8
	private Int32 m_cacheSwitchPlanSeqNum; // 0xe8
	private Tween m_switchTween; // 0xf0
	private static DelegateBridge __Hotfix0_get_status; // 0x0
	private static DelegateBridge __Hotfix0_GetEnterAnim; // 0x8
	private static DelegateBridge __Hotfix0_IsTweenPlaying; // 0x10
	private static DelegateBridge __Hotfix0_OnDataUpdate; // 0x18
	private static DelegateBridge __Hotfix0__PlaySwitchAnimIfNeed; // 0x20
	private static DelegateBridge __Hotfix0__RenderEventPart; // 0x28
	private static DelegateBridge __Hotfix0__RenderTargetPart; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0_EventOnBtnPrevClick; // 0x40
	private static DelegateBridge __Hotfix0_EventOnBtnNextClick; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	protected override DecisionStatus status { get; }

	// RVA: 0x291619c VA: 0x7594f2e19c
	protected override DecisionStatus get_status() { }
	// RVA: 0x2916204 VA: 0x7594f2e204
	protected override UIAnimationLocation GetEnterAnim() { }
	// RVA: 0x2916268 VA: 0x7594f2e268
	public override Boolean IsTweenPlaying() { }
	// RVA: 0x29162f8 VA: 0x7594f2e2f8
	protected override Void OnDataUpdate() { }
	// RVA: 0x2916550 VA: 0x7594f2e550
	private Void _PlaySwitchAnimIfNeed() { }
	// RVA: 0x2916680 VA: 0x7594f2e680
	private Void _RenderEventPart() { }
	// RVA: 0x2916908 VA: 0x7594f2e908
	private Void _RenderTargetPart() { }
	// RVA: 0x2916480 VA: 0x7594f2e480
	private Void _InitIfNot() { }
	// RVA: 0x2916ac4 VA: 0x7594f2eac4
	public Void EventOnBtnPrevClick() { }
	// RVA: 0x2916b68 VA: 0x7594f2eb68
	public Void EventOnBtnNextClick() { }
	// RVA: 0x2916c0c VA: 0x7594f2ec0c
	public Void .ctor() { }
	// RVA: 0x2916c78 VA: 0x7594f2ec78
	private UIAnimationLocation <>xLuaBaseProxy_GetEnterAnim() { }
	// RVA: 0x2916c7c VA: 0x7594f2ec7c
	private Boolean <>xLuaBaseProxy_IsTweenPlaying() { }
}
```