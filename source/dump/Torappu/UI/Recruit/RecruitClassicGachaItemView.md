# RecruitClassicGachaItemView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `GameObject _panelFesInitView`

- `GameObject _panelNormGachaView`

- `Text _recruitName`

- `Text _recruitSummary`

- `GameObject _panelNormUpTitle`

- `GameObject _panelFesUpTitle`

- `Text _singleCrystalPrice`

- `Text _multiCrystalPrice`

- `GameObject _diamondShObj`

- `GameObject _gachaObj`

- `GameObject _diamondShTenObj`

- `GameObject _gachaTenObj`

- `GameObject _gachaBatchedTenObj`

- `GameObject _classicGachaObj`

- `GameObject _classicGachaTenObj`

- `GameObject _classicGachaBatchedTenObj`

- `GameObject _combineGachaTenObj`

- `RectTransform _rectTransformIllust1`

- `RectTransform _rectTransformIllust2`

- `Image _imgIllust1Profession`

- `Image _imgIllust2Profession`

- `Text _txtIllust1Name`

- `Text _txtIllust2Name`

- `Text _txtTktName`

- `RecruitGachaCharButton _illust1CharButton`

- `RecruitGachaCharButton _illust2CharButton`

- `GameObject _protectPart`

- `Text _remainTimes`

- `GachaPoolClientData m_data`

- `UICharacterIllust m_illust1`

- `CharUISkinStruct m_illust1SkinStruct`

- `UICharacterIllust m_illust2`

- `CharUISkinStruct m_illust2SkinStruct`

- `GachaViewState m_viewState`

- `RecruitClassicGachaInitView m_initView`

- `GameObject m_fesUpTitleView`


## Methods

- `Void ApplyData(Int32, GachaPoolClientData)`

- `Void EventOnClassicSHDBtnClick()`

- `Void _UpdateViewStateAndRender()`

- `Void _RenderViewWithState()`

- `ClassicParam _GeneClassicParam(GachaPoolClientData)`

- `Void _RenderNormGachaView(GachaPoolClientData, ClassicParam)`

- `ClassicParam _GeneNormClassicGachaParam(GachaPoolClientData)`

- `Void _RenderInitGachaView(GachaPoolClientData)`

- `ClassicParam _GeneFesClassicGachaParam()`

- `Void _EventOnInitViewStartBtnClick()`

- `Void _EventOnInitViewDetailBtnClick()`

- `CharUISkinStruct _GetSkinStruct(String, out)`

- `Boolean _LoadAndSetIllusts(CharUISkinStruct, CharUISkinStruct, UICharacterIllust, RectTransform)`

- `Void _ClearIllusts(UICharacterIllust)`

- `Void _RenderRare5Char(String, UIAtlasImage, Image, Text)`

- `Void _GetRemainGuaranteeStatus(out, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitClassicGachaItemView : RecruitGachaItemViewBase
{
	private const String CLASSIC_MAIN_6_CHAR_ID; // 0x0
	private const String CLASSIC_SUB_6_CHAR_ID; // 0x0
	private const String CLASSIC_RARE_5_CHAR; // 0x0
	private const Int32 RARE_5_CHAR_COUNT; // 0x0
	private const Int32 INDEX_RARE_6_SHOP_CHAR; // 0x0
	private const Int32 INDEX_RARE_6_NORM_CHAR; // 0x0
	private GameObject _panelFesInitView; // 0x60
	private GameObject _panelNormGachaView; // 0x68
	private Text _recruitName; // 0x70
	private Text _recruitSummary; // 0x78
	private GameObject _panelNormUpTitle; // 0x80
	private GameObject _panelFesUpTitle; // 0x88
	private Text _singleCrystalPrice; // 0x90
	private Text _multiCrystalPrice; // 0x98
	private GameObject _diamondShObj; // 0xa0
	private GameObject _gachaObj; // 0xa8
	private GameObject _diamondShTenObj; // 0xb0
	private GameObject _gachaTenObj; // 0xb8
	private GameObject _gachaBatchedTenObj; // 0xc0
	private GameObject _classicGachaObj; // 0xc8
	private GameObject _classicGachaTenObj; // 0xd0
	private GameObject _classicGachaBatchedTenObj; // 0xd8
	private GameObject _combineGachaTenObj; // 0xe0
	private RectTransform _rectTransformIllust1; // 0xe8
	private RectTransform _rectTransformIllust2; // 0xf0
	private Image _imgIllust1Profession; // 0xf8
	private Image _imgIllust2Profession; // 0x100
	private Text _txtIllust1Name; // 0x108
	private Text _txtIllust2Name; // 0x110
	private UIAtlasImage[] _imgCharPortraits; // 0x118
	private Image[] _imgCharProfessions; // 0x120
	private Text[] _txtCharNames; // 0x128
	private Text _txtTktName; // 0x130
	private RecruitGachaCharButton _illust1CharButton; // 0x138
	private RecruitGachaCharButton _illust2CharButton; // 0x140
	protected GameObject _protectPart; // 0x148
	private Text _remainTimes; // 0x150
	private GachaPoolClientData m_data; // 0x158
	private UICharacterIllust m_illust1; // 0x160
	private CharUISkinStruct m_illust1SkinStruct; // 0x168
	private UICharacterIllust m_illust2; // 0x178
	private CharUISkinStruct m_illust2SkinStruct; // 0x180
	private GachaViewState m_viewState; // 0x190
	private RecruitClassicGachaInitView m_initView; // 0x198
	private GameObject m_fesUpTitleView; // 0x1a0
	private static DelegateBridge __Hotfix0_get_gachaPoolId; // 0x0
	private static DelegateBridge __Hotfix0_OnRefreshData; // 0x8
	private static DelegateBridge __Hotfix0_ApplyData; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClassicSHDBtnClick; // 0x18
	private static DelegateBridge __Hotfix0__UpdateViewStateAndRender; // 0x20
	private static DelegateBridge __Hotfix0__RenderViewWithState; // 0x28
	private static DelegateBridge __Hotfix0__GeneClassicParam; // 0x30
	private static DelegateBridge __Hotfix0__RenderNormGachaView; // 0x38
	private static DelegateBridge __Hotfix0__GeneNormClassicGachaParam; // 0x40
	private static DelegateBridge __Hotfix0__RenderInitGachaView; // 0x48
	private static DelegateBridge __Hotfix0__GeneFesClassicGachaParam; // 0x50
	private static DelegateBridge __Hotfix0__EventOnInitViewStartBtnClick; // 0x58
	private static DelegateBridge __Hotfix0__EventOnInitViewDetailBtnClick; // 0x60
	private static DelegateBridge __Hotfix0__GetSkinStruct; // 0x68
	private static DelegateBridge __Hotfix0__LoadAndSetIllusts; // 0x70
	private static DelegateBridge __Hotfix0__ClearIllusts; // 0x78
	private static DelegateBridge __Hotfix0__RenderRare5Char; // 0x80
	private static DelegateBridge __Hotfix0__GetRemainGuaranteeStatus; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public override String gachaPoolId { get; }

	// RVA: 0x2713310 VA: 0x7594d2b310
	public override String get_gachaPoolId() { }
	// RVA: 0x27133a4 VA: 0x7594d2b3a4
	protected override Void OnRefreshData() { }
	// RVA: 0x27136fc VA: 0x7594d2b6fc
	public Void ApplyData(Int32 index, GachaPoolClientData data) { }
	// RVA: 0x27138e8 VA: 0x7594d2b8e8
	public Void EventOnClassicSHDBtnClick() { }
	// RVA: 0x2713828 VA: 0x7594d2b828
	private Void _UpdateViewStateAndRender() { }
	// RVA: 0x2713994 VA: 0x7594d2b994
	private Void _RenderViewWithState() { }
	// RVA: 0x2713a94 VA: 0x7594d2ba94
	private ClassicParam _GeneClassicParam(GachaPoolClientData data) { }
	// RVA: 0x2713bfc VA: 0x7594d2bbfc
	private Void _RenderNormGachaView(GachaPoolClientData data, ClassicParam classicParam) { }
	// RVA: 0x27144d4 VA: 0x7594d2c4d4
	private ClassicParam _GeneNormClassicGachaParam(GachaPoolClientData data) { }
	// RVA: 0x271429c VA: 0x7594d2c29c
	private Void _RenderInitGachaView(GachaPoolClientData data) { }
	// RVA: 0x27147f4 VA: 0x7594d2c7f4
	private ClassicParam _GeneFesClassicGachaParam() { }
	// RVA: 0x2715250 VA: 0x7594d2d250
	private Void _EventOnInitViewStartBtnClick() { }
	// RVA: 0x271549c VA: 0x7594d2d49c
	private Void _EventOnInitViewDetailBtnClick() { }
	// RVA: 0x2714b88 VA: 0x7594d2cb88
	private CharUISkinStruct _GetSkinStruct(String charId, out CharacterData characterData) { }
	// RVA: 0x2714d38 VA: 0x7594d2cd38
	private Boolean _LoadAndSetIllusts(CharUISkinStruct skinStruct, CharUISkinStruct cachedSkinStruct, UICharacterIllust charIllust, RectTransform container) { }
	// RVA: 0x2715548 VA: 0x7594d2d548
	private Void _ClearIllusts(UICharacterIllust charIllust) { }
	// RVA: 0x2714f48 VA: 0x7594d2cf48
	private Void _RenderRare5Char(String charId, UIAtlasImage charPortrait, Image profession, Text nameText) { }
	// RVA: 0x27135b0 VA: 0x7594d2b5b0
	private Void _GetRemainGuaranteeStatus(out Boolean hasRemainFlag, out Int32 remainCnt) { }
	// RVA: 0x2715620 VA: 0x7594d2d620
	public Void .ctor() { }
}
```