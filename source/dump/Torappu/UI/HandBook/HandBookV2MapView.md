# HandBookV2MapView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookV2MapForceShadowView _shadowView`

- `Transform _shadowContainer`

- `HandBookV2MapPointLineView _pointLineView`

- `Transform _pointLineContainer`

- `HandBookV2MapForceView _bgView`

- `Transform _bgContainer`

- `HandBookV2MapBorderView _borderView`

- `Transform _borderContainer`

- `HandBookV2MapLogoView _logoView`

- `Transform _logoContainer`

- `HandBookV2MapForceCardView _cardView`

- `Transform _cardContainer`

- `HandBookV2MapForceLineView _forceLineView`

- `Transform _forcelineContainer`

- `AnimationWrapper _lineAnimWrapper`

- `UIStringEvent _onForceClick`

- `Boolean m_isPlayAnim`

- `Boolean m_isCardAndLineVisible`


## Methods

- `Void PlayFadeOutAnim(Boolean)`

- `Void _Render(HandBookV2MapRenderViewModel)`

- `Void _RenderShadow(HandBookV2ForceViewModel)`

- `Void _RenderBg(HandBookV2ForceViewModel)`

- `Void _RenderBorder(HandBookV2ForceViewModel, Dictionary`2)`

- `Void _RenderLogo(HandBookV2ForceViewModel)`

- `Void _RenderCard(HandBookV2ForceViewModel)`

- `Void _RenderForceLine(HandBookV2ForceLineViewModel)`

- `Void _RenderPointLine(HandBookV2PointLineViewModel)`

- `Void <PlayFadeOutAnim>b__27_0(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2MapView : DataBinder`1, IHotfixable
{
	private HandBookV2MapForceShadowView _shadowView; // 0x20
	private Transform _shadowContainer; // 0x28
	private HandBookV2MapPointLineView _pointLineView; // 0x30
	private Transform _pointLineContainer; // 0x38
	private HandBookV2MapForceView _bgView; // 0x40
	private Transform _bgContainer; // 0x48
	private HandBookV2MapBorderView _borderView; // 0x50
	private Transform _borderContainer; // 0x58
	private HandBookV2MapLogoView _logoView; // 0x60
	private Transform _logoContainer; // 0x68
	private HandBookV2MapForceCardView _cardView; // 0x70
	private Transform _cardContainer; // 0x78
	private HandBookV2MapForceLineView _forceLineView; // 0x80
	private Transform _forcelineContainer; // 0x88
	private AnimationWrapper _lineAnimWrapper; // 0x90
	private UIStringEvent _onForceClick; // 0x98
	private const String LINE_FADE_OUT; // 0x0
	private Boolean m_isPlayAnim; // 0xa0
	private Boolean m_isCardAndLineVisible; // 0xa1
	private Dictionary`2 m_pointLineViewMap; // 0xa8
	private Dictionary`2 m_forceIdx2BgViewMap; // 0xb0
	private Dictionary`2 m_forceIdx2ShadowViewMap; // 0xb8
	private Dictionary`2 m_forceIdx2BorderViewMap; // 0xc0
	private Dictionary`2 m_forceIdx2LogoViewMap; // 0xc8
	private Dictionary`2 m_forceIdx2CardViewMap; // 0xd0
	private Dictionary`2 m_forceLineViewMap; // 0xd8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_PlayFadeOutAnim; // 0x8
	private static DelegateBridge __Hotfix0__Render; // 0x10
	private static DelegateBridge __Hotfix0__RenderShadow; // 0x18
	private static DelegateBridge __Hotfix0__RenderBg; // 0x20
	private static DelegateBridge __Hotfix0__RenderBorder; // 0x28
	private static DelegateBridge __Hotfix0__RenderLogo; // 0x30
	private static DelegateBridge __Hotfix0__RenderCard; // 0x38
	private static DelegateBridge __Hotfix0__RenderForceLine; // 0x40
	private static DelegateBridge __Hotfix0__RenderPointLine; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2ed6e50 VA: 0x75954eee50
	public override Void OnValueChanged(HandBookV2MapRenderProperty property) { }
	// RVA: 0x2ed72e4 VA: 0x75954ef2e4
	public Void PlayFadeOutAnim(Boolean isFadeOut) { }
	// RVA: 0x2ed6ee4 VA: 0x75954eeee4
	private Void _Render(HandBookV2MapRenderViewModel mapViewModel) { }
	// RVA: 0x2ed7590 VA: 0x75954ef590
	private Void _RenderShadow(HandBookV2ForceViewModel viewModel) { }
	// RVA: 0x2ed7714 VA: 0x75954ef714
	private Void _RenderBg(HandBookV2ForceViewModel viewModel) { }
	// RVA: 0x2ed78a8 VA: 0x75954ef8a8
	private Void _RenderBorder(HandBookV2ForceViewModel viewModel, Dictionary`2 pointIndex2ForceIdMap) { }
	// RVA: 0x2ed7a38 VA: 0x75954efa38
	private Void _RenderLogo(HandBookV2ForceViewModel viewModel) { }
	// RVA: 0x2ed7bbc VA: 0x75954efbbc
	private Void _RenderCard(HandBookV2ForceViewModel viewModel) { }
	// RVA: 0x2ed7d50 VA: 0x75954efd50
	private Void _RenderForceLine(HandBookV2ForceLineViewModel lineModel) { }
	// RVA: 0x2ed7e90 VA: 0x75954efe90
	private Void _RenderPointLine(HandBookV2PointLineViewModel pointLineModel) { }
	// RVA: 0x2ed7fd0 VA: 0x75954effd0
	public Void .ctor() { }
	// RVA: 0x2ed829c VA: 0x75954f029c
	private Void <PlayFadeOutAnim>b__27_0(String _) { }
}
```