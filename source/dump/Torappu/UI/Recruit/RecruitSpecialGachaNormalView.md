# RecruitSpecialGachaNormalView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Text _recruitName`

- `Text _recruitSummary`

- `Text _singleCrystalPrice`

- `Text _multiCrystalPrice`

- `GameObject _diamondShObj`

- `GameObject _gachaObj`

- `GameObject _diamondShTenObj`

- `GameObject _gachaTenObj`

- `GameObject _gachaBatchedTenObj`

- `GameObject _panelProtect`

- `Text _textRemainTimes`

- `Boolean m_hasInited`

- `UIPageFinder m_pageFinder`

- `Action <onDetailBtnClicked>k__BackingField`

- `Action <onRecruitTenBtnClicked>k__BackingField`

- `Action <onRecruitOnceBtnClicked>k__BackingField`


## Properties

- `Action onDetailBtnClicked`

- `Action onRecruitTenBtnClicked`

- `Action onRecruitOnceBtnClicked`


## Methods

- `Action get_onDetailBtnClicked()`

- `Void set_onDetailBtnClicked(Action)`

- `Action get_onRecruitTenBtnClicked()`

- `Void set_onRecruitTenBtnClicked(Action)`

- `Action get_onRecruitOnceBtnClicked()`

- `Void set_onRecruitOnceBtnClicked(Action)`

- `Void EventOnDetailBtnClicked()`

- `Void EventOnRecruitTenBtnClicked()`

- `Void EventOnRecruitOnceBtnClicked()`

- `Void _InitIfNot()`

- `Void _RenderGachaPolicy(RecruitSpecialGachaViewModel)`

- `Void _RenderInfo(RecruitSpecialGachaViewModel)`

- `Void _RenderIllustChar(RecruitSpecialGachaViewModel)`

- `Void _RenderPortraitChar(RecruitSpecialGachaViewModel)`

- `Void _LoadAndSetIllusts(CharUISkinStruct, IllustInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitSpecialGachaNormalView : DataBinder`1, IHotfixable
{
	private const String CRYSTAL_PRICE_FORMAT; // 0x0
	private Text _recruitName; // 0x20
	private Text _recruitSummary; // 0x28
	private Text _singleCrystalPrice; // 0x30
	private Text _multiCrystalPrice; // 0x38
	private GameObject _diamondShObj; // 0x40
	private GameObject _gachaObj; // 0x48
	private GameObject _diamondShTenObj; // 0x50
	private GameObject _gachaTenObj; // 0x58
	private GameObject _gachaBatchedTenObj; // 0x60
	protected GameObject _panelProtect; // 0x68
	private Text _textRemainTimes; // 0x70
	private RectTransform[] _rectTransformIllustList; // 0x78
	private Image[] _imgIllustProfessionList; // 0x80
	private Text[] _textIlluestNameList; // 0x88
	private RecruitGachaCharButton[] _illustCharButtonList; // 0x90
	private UIAtlasImage[] _imgCharPortraitList; // 0x98
	private Image[] _imgCharProfessionList; // 0xa0
	private Text[] _textCharNameList; // 0xa8
	private List`1 m_illustList; // 0xb0
	private List`1 m_portraitCharList; // 0xb8
	private Boolean m_hasInited; // 0xc0
	private UIPageFinder m_pageFinder; // 0xc8
	private Action <onDetailBtnClicked>k__BackingField; // 0xd8
	private Action <onRecruitTenBtnClicked>k__BackingField; // 0xe0
	private Action <onRecruitOnceBtnClicked>k__BackingField; // 0xe8
	private static DelegateBridge __Hotfix0_get_onDetailBtnClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onDetailBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onRecruitTenBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onRecruitTenBtnClicked; // 0x18
	private static DelegateBridge __Hotfix0_get_onRecruitOnceBtnClicked; // 0x20
	private static DelegateBridge __Hotfix0_set_onRecruitOnceBtnClicked; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge __Hotfix0_EventOnDetailBtnClicked; // 0x38
	private static DelegateBridge __Hotfix0_EventOnRecruitTenBtnClicked; // 0x40
	private static DelegateBridge __Hotfix0_EventOnRecruitOnceBtnClicked; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge __Hotfix0__RenderGachaPolicy; // 0x58
	private static DelegateBridge __Hotfix0__RenderInfo; // 0x60
	private static DelegateBridge __Hotfix0__RenderIllustChar; // 0x68
	private static DelegateBridge __Hotfix0__RenderPortraitChar; // 0x70
	private static DelegateBridge __Hotfix0__GetSkinStruct; // 0x78
	private static DelegateBridge __Hotfix0__LoadAndSetIllusts; // 0x80
	private static DelegateBridge __Hotfix0__ClearIllusts; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	private Action onDetailBtnClicked { get; set; }
	private Action onRecruitTenBtnClicked { get; set; }
	private Action onRecruitOnceBtnClicked { get; set; }

	// RVA: 0x271e2f0 VA: 0x7594d362f0
	private Action get_onDetailBtnClicked() { }
	// RVA: 0x271db78 VA: 0x7594d35b78
	public Void set_onDetailBtnClicked(Action value) { }
	// RVA: 0x271e358 VA: 0x7594d36358
	private Action get_onRecruitTenBtnClicked() { }
	// RVA: 0x271dbfc VA: 0x7594d35bfc
	public Void set_onRecruitTenBtnClicked(Action value) { }
	// RVA: 0x271e3c0 VA: 0x7594d363c0
	private Action get_onRecruitOnceBtnClicked() { }
	// RVA: 0x271dc80 VA: 0x7594d35c80
	public Void set_onRecruitOnceBtnClicked(Action value) { }
	// RVA: 0x271e428 VA: 0x7594d36428
	public override Void OnValueChanged(RecruitSpecialGachaProperty property) { }
	// RVA: 0x271f13c VA: 0x7594d3713c
	public Void EventOnDetailBtnClicked() { }
	// RVA: 0x271f1d8 VA: 0x7594d371d8
	public Void EventOnRecruitTenBtnClicked() { }
	// RVA: 0x271f274 VA: 0x7594d37274
	public Void EventOnRecruitOnceBtnClicked() { }
	// RVA: 0x271e53c VA: 0x7594d3653c
	private Void _InitIfNot() { }
	// RVA: 0x271ea40 VA: 0x7594d36a40
	private Void _RenderGachaPolicy(RecruitSpecialGachaViewModel model) { }
	// RVA: 0x271eb58 VA: 0x7594d36b58
	private Void _RenderInfo(RecruitSpecialGachaViewModel model) { }
	// RVA: 0x271ecdc VA: 0x7594d36cdc
	private Void _RenderIllustChar(RecruitSpecialGachaViewModel model) { }
	// RVA: 0x271eec8 VA: 0x7594d36ec8
	private Void _RenderPortraitChar(RecruitSpecialGachaViewModel model) { }
	// RVA: 0x271f320 VA: 0x7594d37320
	private static CharUISkinStruct _GetSkinStruct(String charId, out CharacterData characterData) { }
	// RVA: 0x271f4c8 VA: 0x7594d374c8
	private Void _LoadAndSetIllusts(CharUISkinStruct skinStruct, IllustInfo info) { }
	// RVA: 0x271f6c8 VA: 0x7594d376c8
	private static Void _ClearIllusts(ref UICharacterIllust charIllust) { }
	// RVA: 0x271f790 VA: 0x7594d37790
	public Void .ctor() { }
}
```