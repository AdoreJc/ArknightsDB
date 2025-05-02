# TemplateMissionCommonBigRewardWithSkinView

**Namespace:** `Torappu.UI.TemplateMission`


## Fields

- `RectTransform _skinContainer`

- `Image _imgSkinGroupIcon`

- `Text _textSkinName`

- `MaskableGraphic _imgSkinNameBkg`

- `Text _textRewardTip`

- `TemplateMissionCommonEntryFadeTween _entryFadeTween`

- `Boolean m_isRendered`

- `CharSkinData m_cachedSkinData`

- `UIPageFinder m_pageFinder`

- `UICharacterIllust m_illust`

- `UIStateFinder m_stateFinder`

- `CharUISkinStruct m_cachedSkinStruct`


## Methods

- `Void _RenderCharSkinPart(CharSkinData, String)`

- `Void _RenderTipsPart(List`1)`

- `Void EventOnDetailBtnClicked()`

- `Void <>xLuaBaseProxy_Init(AbstractTemplateMissionViewController, TemplateMissionCustomResHolder)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateMission
public class TemplateMissionCommonBigRewardWithSkinView : TemplateMissionCommonBigRewardIllustView, IHotfixable
{
	private RectTransform _skinContainer; // 0x50
	private Image _imgSkinGroupIcon; // 0x58
	private Text _textSkinName; // 0x60
	private MaskableGraphic _imgSkinNameBkg; // 0x68
	private Text _textRewardTip; // 0x70
	private TemplateMissionCommonEntryFadeTween _entryFadeTween; // 0x78
	private Boolean m_isRendered; // 0x80
	private CharSkinData m_cachedSkinData; // 0x88
	private UIPageFinder m_pageFinder; // 0x90
	private UICharacterIllust m_illust; // 0xa0
	private UIStateFinder m_stateFinder; // 0xa8
	private CharUISkinStruct m_cachedSkinStruct; // 0xb8
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge __Hotfix0__GetSkinId; // 0x10
	private static DelegateBridge __Hotfix0__RenderCharSkinPart; // 0x18
	private static DelegateBridge __Hotfix0__RenderTipsPart; // 0x20
	private static DelegateBridge __Hotfix0_EventOnDetailBtnClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x23695bc VA: 0x75949815bc
	public override Void Init(AbstractTemplateMissionViewController ctrl_, TemplateMissionCustomResHolder customResHolder_) { }
	// RVA: 0x2369668 VA: 0x7594981668
	protected override Void RenderView() { }
	// RVA: 0x23697bc VA: 0x75949817bc
	private static String _GetSkinId(List`1 paramList) { }
	// RVA: 0x2369844 VA: 0x7594981844
	private Void _RenderCharSkinPart(CharSkinData skinData, String mainColor) { }
	// RVA: 0x2369a78 VA: 0x7594981a78
	private Void _RenderTipsPart(List`1 paramList) { }
	// RVA: 0x2369b38 VA: 0x7594981b38
	public Void EventOnDetailBtnClicked() { }
	// RVA: 0x2369c54 VA: 0x7594981c54
	public Void .ctor() { }
	// RVA: 0x2369d00 VA: 0x7594981d00
	private Void <>xLuaBaseProxy_Init(AbstractTemplateMissionViewController P0, TemplateMissionCustomResHolder P1) { }
}
```