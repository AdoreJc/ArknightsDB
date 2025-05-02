# TemplateMissionCommonBigRewardWithCharIllustView

**Namespace:** `Torappu.UI.TemplateMission`


## Fields

- `GameObject _objIllustPart`

- `RectTransform _rectTransformIllust1`

- `RectTransform _rectTransformIllust2`

- `Material _materialForIllust2`

- `Single _alphaForIllust2`

- `GameObject _objCharInfoPart`

- `Image _profession`

- `Image _rarity`

- `Text _nameText`

- `GameObject _objTipsPart`

- `Text _txtTips`

- `TemplateMissionCommonEntryFadeTween _entryFadeTween`

- `Boolean m_isRendered`

- `String m_cachedCharId`

- `UIStateFinder m_stateFinder`

- `UICharacterIllust m_illust1`

- `UICharacterIllust m_illust2`

- `Material m_cachedIllust2Mat`


## Methods

- `String _GetCharId(List`1)`

- `Void _RenderCharDataPart(String)`

- `Void _RenderCharInfo(String)`

- `Void _RenderTipsPart(List`1)`

- `Void _RenderPortraitPhase2Color(List`1)`

- `Void _RefreshPortraitPhaseMat(UICharacterIllust, Color)`

- `Void OnDetailInfoClick()`

- `Void <>xLuaBaseProxy_Init(AbstractTemplateMissionViewController, TemplateMissionCustomResHolder)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateMission
public class TemplateMissionCommonBigRewardWithCharIllustView : TemplateMissionCommonBigRewardIllustView
{
	private GameObject _objIllustPart; // 0x50
	private RectTransform _rectTransformIllust1; // 0x58
	private RectTransform _rectTransformIllust2; // 0x60
	private Material _materialForIllust2; // 0x68
	private Single _alphaForIllust2; // 0x70
	private GameObject _objCharInfoPart; // 0x78
	private Image _profession; // 0x80
	private Image _rarity; // 0x88
	private Text _nameText; // 0x90
	private GameObject _objTipsPart; // 0x98
	private Text _txtTips; // 0xa0
	private TemplateMissionCommonEntryFadeTween _entryFadeTween; // 0xa8
	private Boolean m_isRendered; // 0xb0
	private String m_cachedCharId; // 0xb8
	private UIStateFinder m_stateFinder; // 0xc0
	private UICharacterIllust m_illust1; // 0xd0
	private UICharacterIllust m_illust2; // 0xd8
	private Material m_cachedIllust2Mat; // 0xe0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge __Hotfix0__GetCharId; // 0x10
	private static DelegateBridge __Hotfix0__RenderCharDataPart; // 0x18
	private static DelegateBridge __Hotfix0__RenderCharInfo; // 0x20
	private static DelegateBridge __Hotfix0__RenderTipsPart; // 0x28
	private static DelegateBridge __Hotfix0__RenderPortraitPhase2Color; // 0x30
	private static DelegateBridge __Hotfix0__RefreshPortraitPhaseMat; // 0x38
	private static DelegateBridge __Hotfix0_OnDetailInfoClick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2368658 VA: 0x7594980658
	public override Void Init(AbstractTemplateMissionViewController ctrl_, TemplateMissionCustomResHolder customResHolder_) { }
	// RVA: 0x2368720 VA: 0x7594980720
	protected override Void RenderView() { }
	// RVA: 0x23688fc VA: 0x75949808fc
	private String _GetCharId(List`1 paramList) { }
	// RVA: 0x23689f4 VA: 0x75949809f4
	private Void _RenderCharDataPart(String charId) { }
	// RVA: 0x2368d34 VA: 0x7594980d34
	private Void _RenderCharInfo(String charId) { }
	// RVA: 0x2368ac4 VA: 0x7594980ac4
	private Void _RenderTipsPart(List`1 paramList) { }
	// RVA: 0x2368c08 VA: 0x7594980c08
	private Void _RenderPortraitPhase2Color(List`1 paramList) { }
	// RVA: 0x2368f54 VA: 0x7594980f54
	private Void _RefreshPortraitPhaseMat(UICharacterIllust illust, Color color) { }
	// RVA: 0x2369118 VA: 0x7594981118
	public Void OnDetailInfoClick() { }
	// RVA: 0x2369218 VA: 0x7594981218
	public Void .ctor() { }
	// RVA: 0x23692c8 VA: 0x75949812c8
	private Void <>xLuaBaseProxy_Init(AbstractTemplateMissionViewController P0, TemplateMissionCustomResHolder P1) { }
}
```