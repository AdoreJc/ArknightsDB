# FifthAnnivExploreOptionItemView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `Text _textName`

- `Text _textDesc`

- `UIAtlasImage _imgConfirmBg`

- `Color _colorRed`

- `Color _colorYellow`

- `Color _colorGreen`

- `GameObject _btnSelectGo`

- `GameObject _eventPartGo`

- `Text _textWinRateShrink`

- `Text _textWinRateExpand`

- `GameObject _attrDeltaListGo`

- `SimpleLayoutContent _attrDeltaList`

- `SimpleLayoutContent _attrCondList`

- `GameObject _targetPartGo`

- `Text _textSelect`

- `GameObject _disableMaskGo`

- `UIAtlasImage _imgDecoCircle`

- `Single _alphaDisable`

- `UIAnimationLocation _animExpand`

- `Single _lowWinRateThres`

- `Single _highWinRateThres`

- `AnimationSwitchTween m_animSwitchTween`

- `Boolean m_hasInited`

- `AttrDeltaListAdapter m_attrDeltaListAdapter`

- `AttrCondListAdapter m_attrCondListAdapter`

- `UIStateFinder m_stateFinder`

- `FifthAnnivExploreOptionModel m_optionModel`

- `DecisionNodeType m_decisionType`

- `Int32 m_cacheEnterSeqNum`

- `Int32 m_cacheSwitchPlanSeqNum`


## Methods

- `Void Render(FifthAnnivExploreDecisionModel, FifthAnnivExploreOptionModel, Boolean)`

- `Void _RenderImpl()`

- `Void _PlaySwitchAnimIfNeed(FifthAnnivExploreDecisionModel, Boolean)`

- `Void _RenderEventPart()`

- `String _GetPercentageStr(Single)`

- `Void _RenderTargetPart()`

- `Void _InitIfNot()`

- `Void EventOnOptionClick()`

- `Void EventOnConfirmClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreOptionItemView : MonoBehaviour, IHotfixable
{
	private Text _textName; // 0x18
	private Text _textDesc; // 0x20
	private UIAtlasImage _imgConfirmBg; // 0x28
	private Color _colorRed; // 0x30
	private Color _colorYellow; // 0x40
	private Color _colorGreen; // 0x50
	private GameObject _btnSelectGo; // 0x60
	private GameObject _eventPartGo; // 0x68
	private Text _textWinRateShrink; // 0x70
	private Text _textWinRateExpand; // 0x78
	private GameObject _attrDeltaListGo; // 0x80
	private SimpleLayoutContent _attrDeltaList; // 0x88
	private SimpleLayoutContent _attrCondList; // 0x90
	private GameObject _targetPartGo; // 0x98
	private Text _textSelect; // 0xa0
	private GameObject _disableMaskGo; // 0xa8
	private UIAtlasImage _imgDecoCircle; // 0xb0
	private Single _alphaDisable; // 0xb8
	private UIAnimationLocation _animExpand; // 0xc0
	private Single _lowWinRateThres; // 0xd0
	private Single _highWinRateThres; // 0xd4
	private AnimationSwitchTween m_animSwitchTween; // 0xd8
	private Boolean m_hasInited; // 0xe0
	private AttrDeltaListAdapter m_attrDeltaListAdapter; // 0xe8
	private AttrCondListAdapter m_attrCondListAdapter; // 0xf0
	private UIStateFinder m_stateFinder; // 0xf8
	private FifthAnnivExploreOptionModel m_optionModel; // 0x108
	private DecisionNodeType m_decisionType; // 0x110
	private Int32 m_cacheEnterSeqNum; // 0x114
	private Int32 m_cacheSwitchPlanSeqNum; // 0x118
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderImpl; // 0x8
	private static DelegateBridge __Hotfix0__PlaySwitchAnimIfNeed; // 0x10
	private static DelegateBridge __Hotfix0__RenderEventPart; // 0x18
	private static DelegateBridge __Hotfix0__GetPercentageStr; // 0x20
	private static DelegateBridge __Hotfix0__RenderTargetPart; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0_EventOnOptionClick; // 0x38
	private static DelegateBridge __Hotfix0_EventOnConfirmClick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2914d00 VA: 0x7594f2cd00
	public Void Render(FifthAnnivExploreDecisionModel decisionModel, FifthAnnivExploreOptionModel optionModel, Boolean isSelect) { }
	// RVA: 0x2914fcc VA: 0x7594f2cfcc
	private Void _RenderImpl() { }
	// RVA: 0x2915100 VA: 0x7594f2d100
	private Void _PlaySwitchAnimIfNeed(FifthAnnivExploreDecisionModel decisionModel, Boolean isSelect) { }
	// RVA: 0x29153f4 VA: 0x7594f2d3f4
	private Void _RenderEventPart() { }
	// RVA: 0x2915658 VA: 0x7594f2d658
	private String _GetPercentageStr(Single winRate) { }
	// RVA: 0x291520c VA: 0x7594f2d20c
	private Void _RenderTargetPart() { }
	// RVA: 0x2914e34 VA: 0x7594f2ce34
	private Void _InitIfNot() { }
	// RVA: 0x2915844 VA: 0x7594f2d844
	public Void EventOnOptionClick() { }
	// RVA: 0x2915950 VA: 0x7594f2d950
	public Void EventOnConfirmClick() { }
	// RVA: 0x2915a5c VA: 0x7594f2da5c
	public Void .ctor() { }
}
```