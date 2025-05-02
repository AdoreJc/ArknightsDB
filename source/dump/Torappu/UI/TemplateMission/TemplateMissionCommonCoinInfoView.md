# TemplateMissionCommonCoinInfoView

**Namespace:** `Torappu.UI.TemplateMission`


## Fields

- `Image _imgCoin`

- `Text _txtCoin`

- `UIAtlasImage _imgBgLeft`

- `TemplateMissionCommonEntryFadeTween _entryFadeTween`

- `Boolean m_isImgRendered`


## Methods

- `Void _RenderCoinImg(TemplateMissionViewModel)`

- `Void _RenderCoinCount(TemplateMissionCoinViewModel)`

- `Void <>xLuaBaseProxy_Init(AbstractTemplateMissionViewController, TemplateMissionCustomResHolder)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateMission
public class TemplateMissionCommonCoinInfoView : TemplateMissionCoinInfoView
{
	private Image _imgCoin; // 0x40
	private Text _txtCoin; // 0x48
	private UIAtlasImage _imgBgLeft; // 0x50
	private TemplateMissionCommonEntryFadeTween _entryFadeTween; // 0x58
	private Boolean m_isImgRendered; // 0x60
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge __Hotfix0__RenderCoinImg; // 0x10
	private static DelegateBridge __Hotfix0__RenderCoinCount; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2369edc VA: 0x7594981edc
	public override Void Init(AbstractTemplateMissionViewController ctrl_, TemplateMissionCustomResHolder customResHolder_) { }
	// RVA: 0x2369f7c VA: 0x7594981f7c
	protected override Void RenderView() { }
	// RVA: 0x236a0b0 VA: 0x75949820b0
	private Void _RenderCoinImg(TemplateMissionViewModel model) { }
	// RVA: 0x236a284 VA: 0x7594982284
	private Void _RenderCoinCount(TemplateMissionCoinViewModel coinModel) { }
	// RVA: 0x236a428 VA: 0x7594982428
	public Void .ctor() { }
	// RVA: 0x236a494 VA: 0x7594982494
	private Void <>xLuaBaseProxy_Init(AbstractTemplateMissionViewController P0, TemplateMissionCustomResHolder P1) { }
}
```