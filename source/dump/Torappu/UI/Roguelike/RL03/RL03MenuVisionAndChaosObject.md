# RL03MenuVisionAndChaosObject

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `GameObject _pnlContent`

- `Text _txtVision`

- `Text _txtAdjacentVision`

- `CanvasGroup _canvasGroupVision`

- `CanvasGroup _canvasGroupAdjacentVision`

- `RectTransform _rectTransformVisionTxt`

- `RectTransform _rectTransformVisionTxtDefault`

- `RectTransform _rectTransformAdjacentVisionTxt`

- `RectTransform _rectTransformVisionBg`

- `Text _txtName`

- `Image _imgZoneIcon`

- `GameObject _panelPredict`

- `RL03StatusBarChaosEffect _effectPrefab`

- `AnimationCurve _visionRotateCurve`

- `UIPageFinder m_pageFinder`

- `VisionAnimManager m_visionAnimManager`

- `RL03MenuVisionAndChaosViewModel m_cachedModel`

- `Boolean m_cachedStateShow`

- `Int32 m_cachedSightNum`

- `RL03StatusBarChaosEffect m_effect`


## Methods

- `Void _UpdateRenderers()`

- `Void _Render(Boolean, Boolean)`

- `Void _RenderShowStatus(Boolean, Boolean)`

- `Void _RenderZone(String, Boolean)`

- `Void _RenderPredict(Boolean, Boolean)`

- `Void _RenderVision(VisionParam, Boolean)`

- `Void _ResetToVisionValue(Int32, Int32)`

- `Void _RenderChaosEffect(RenderParam, Boolean)`

- `Single _GetVisionRelatedAngle(Int32)`

- `Boolean <Init>b__34_0()`

- `String <Init>b__34_1()`

- `Boolean <Init>b__34_2()`

- `VisionParam <Init>b__34_3()`

- `RenderParam <Init>b__34_4()`

- `Void <>xLuaBaseProxy_Init(RoguelikeMenuBar)`

- `Void <>xLuaBaseProxy_DispatchMenuEffects(List`1)`

- `Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03MenuVisionAndChaosObject : RoguelikeMenuObject`1
{
	private const Single ANIM_DURATION; // 0x0
	private static Vector3 SIGHT_TEXT_SCALE_VECTOR3; // 0x0
	private static readonly Type[] STATES_NOT_SHOW; // 0x10
	private GameObject _pnlContent; // 0x28
	private Text _txtVision; // 0x30
	private Text _txtAdjacentVision; // 0x38
	private CanvasGroup _canvasGroupVision; // 0x40
	private CanvasGroup _canvasGroupAdjacentVision; // 0x48
	private RectTransform _rectTransformVisionTxt; // 0x50
	private RectTransform _rectTransformVisionTxtDefault; // 0x58
	private RectTransform _rectTransformAdjacentVisionTxt; // 0x60
	private RectTransform _rectTransformVisionBg; // 0x68
	private List`1 _visionConfigs; // 0x70
	private Text _txtName; // 0x78
	private Image _imgZoneIcon; // 0x80
	private GameObject _panelPredict; // 0x88
	private RL03StatusBarChaosEffect _effectPrefab; // 0x90
	private AnimationCurve _visionRotateCurve; // 0x98
	private RoguelikeMenuViewRenderer`1 m_showRenderer; // 0xa0
	private RoguelikeMenuViewRenderer`1 m_zoneRenderer; // 0xa8
	private List`1 m_renderers; // 0xb0
	private UIPageFinder m_pageFinder; // 0xb8
	private VisionAnimManager m_visionAnimManager; // 0xc8
	private RL03MenuVisionAndChaosViewModel m_cachedModel; // 0xd0
	private Boolean m_cachedStateShow; // 0xd8
	private Dictionary`2 m_visionConfigDict; // 0xe0
	private Int32 m_cachedSightNum; // 0xe8
	private RL03StatusBarChaosEffect m_effect; // 0xf0
	private static DelegateBridge __Hotfix0_get_menuType; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge __Hotfix0_CollectMenuEffectPrefabs; // 0x28
	private static DelegateBridge __Hotfix0_DispatchMenuEffects; // 0x30
	private static DelegateBridge __Hotfix0_OnMenuAdapterChanged; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x40
	private static DelegateBridge __Hotfix0__UpdateRenderers; // 0x48
	private static DelegateBridge __Hotfix0__Render; // 0x50
	private static DelegateBridge __Hotfix0__RenderShowStatus; // 0x58
	private static DelegateBridge __Hotfix0__RenderZone; // 0x60
	private static DelegateBridge __Hotfix0__RenderPredict; // 0x68
	private static DelegateBridge __Hotfix0__RenderVision; // 0x70
	private static DelegateBridge __Hotfix0__ResetToVisionValue; // 0x78
	private static DelegateBridge __Hotfix0__RenderChaosEffect; // 0x80
	private static DelegateBridge __Hotfix0__GetVisionRelatedAngle; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2b9d28c VA: 0x75951b528c
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2b9d304 VA: 0x75951b5304
	public override Void Init(RoguelikeMenuBar menu) { }
	// RVA: 0x2b9db64 VA: 0x75951b5b64
	public override List`1 CollectMenuEffectPrefabs() { }
	// RVA: 0x2b9dc90 VA: 0x75951b5c90
	public override Void DispatchMenuEffects(List`1 instanceList) { }
	// RVA: 0x2b9ddcc VA: 0x75951b5dcc
	public override Void OnMenuAdapterChanged(RoguelikeMenuAdapter adapter, Boolean fastMode) { }
	// RVA: 0x2b9e3a0 VA: 0x75951b63a0
	public override Void Render(RL03MenuVisionAndChaosViewModel viewModel) { }
	// RVA: 0x2b9dee4 VA: 0x75951b5ee4
	private Void _UpdateRenderers() { }
	// RVA: 0x2b9e120 VA: 0x75951b6120
	private Void _Render(Boolean fastMode, Boolean isFromAdapterChange) { }
	// RVA: 0x2b9e460 VA: 0x75951b6460
	private Void _RenderShowStatus(Boolean show, Boolean fastMode) { }
	// RVA: 0x2b9e568 VA: 0x75951b6568
	private Void _RenderZone(String zoneId, Boolean fastMode) { }
	// RVA: 0x2b9e6b0 VA: 0x75951b66b0
	private Void _RenderPredict(Boolean isShow, Boolean fastMode) { }
	// RVA: 0x2b9e74c VA: 0x75951b674c
	private Void _RenderVision(VisionParam visionParam, Boolean fastMode) { }
	// RVA: 0x2b9e8e0 VA: 0x75951b68e0
	private Void _ResetToVisionValue(Int32 curSightNum, Int32 maxSightNum) { }
	// RVA: 0x2b9ed1c VA: 0x75951b6d1c
	private Void _RenderChaosEffect(RenderParam renderParam, Boolean fastMode) { }
	// RVA: 0x2b9ec38 VA: 0x75951b6c38
	private Single _GetVisionRelatedAngle(Int32 targetNum) { }
	// RVA: 0x2b9eedc VA: 0x75951b6edc
	public Void .ctor() { }
	// RVA: 0x2b9ef7c VA: 0x75951b6f7c
	private static Void .cctor() { }
	// RVA: 0x2b9f100 VA: 0x75951b7100
	private Boolean <Init>b__34_0() { }
	// RVA: 0x2b9f140 VA: 0x75951b7140
	private String <Init>b__34_1() { }
	// RVA: 0x2b9f15c VA: 0x75951b715c
	private Boolean <Init>b__34_2() { }
	// RVA: 0x2b9f1f4 VA: 0x75951b71f4
	private VisionParam <Init>b__34_3() { }
	// RVA: 0x2b9f324 VA: 0x75951b7324
	private RenderParam <Init>b__34_4() { }
	// RVA: 0x2b9f454 VA: 0x75951b7454
	private Void <>xLuaBaseProxy_Init(RoguelikeMenuBar P0) { }
	// RVA: 0x2b9f45c VA: 0x75951b745c
	private List`1 <>xLuaBaseProxy_CollectMenuEffectPrefabs() { }
	// RVA: 0x2b9f464 VA: 0x75951b7464
	private Void <>xLuaBaseProxy_DispatchMenuEffects(List`1 P0) { }
	// RVA: 0x2b9f46c VA: 0x75951b746c
	private Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter P0, Boolean P1) { }
}
```