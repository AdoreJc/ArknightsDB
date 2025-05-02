# RL02MainTransitionView

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `CanvasGroup _panelMainTrans`

- `AudioClickPlayer _clickAudio`

- `UIAtlasImage _iconAtlasImage`

- `Text _textName`

- `Text _textDesc`

- `Image _imgLevelLabel`

- `SimpleLayoutContent _tagLayoutContent`

- `UIAtlasObject _uiAtlasObject`

- `GameObject _effectPrefab`

- `RectTransform _effectTransform`

- `AnimationWrapper _animWrapper`

- `Tween m_enterTween`

- `Tween m_variationTween`

- `GameObject m_variationEffect`

- `Boolean m_isInited`

- `TagAdapter m_tagAdapter`

- `MainTransParam m_cachedMainTransParam`

- `Boolean m_waitForNextClick`

- `Boolean m_waitForAnimEnd`

- `UIPageFinder m_pageFinder`

- `FadeSwitchTween m_mainTransSwitch`


## Properties

- `FadeSwitchTween mainTransSwitch`


## Methods

- `FadeSwitchTween get_mainTransSwitch()`

- `Void OnEnable()`

- `Void _InitIfNot()`

- `Void EventOnMainPanelClicked()`

- `Void _RenderMainTrans(MainTransParam)`

- `IEnumerator _WaitForNextClick()`

- `IEnumerator _ShowVariationTrans()`

- `Boolean <TransCoroutine>b__33_0()`

- `Boolean <_ShowVariationTrans>b__39_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02MainTransitionView : RoguelikeMainTransController
{
	private const Single SHOW_TWEEN_DURATION; // 0x0
	private const Single HIDE_TWEEN_DURATION; // 0x0
	private const Single AUTO_MAIN_TRANS_DUR; // 0x0
	private const String ANIM_ENTER; // 0x0
	private const String ANIM_VARIATION; // 0x0
	private CanvasGroup _panelMainTrans; // 0x20
	private AudioClickPlayer _clickAudio; // 0x28
	private UIAtlasImage _iconAtlasImage; // 0x30
	private Text _textName; // 0x38
	private Text _textDesc; // 0x40
	private Image _imgLevelLabel; // 0x48
	private SimpleLayoutContent _tagLayoutContent; // 0x50
	private List`1 _zoneIconStructs; // 0x58
	private UIAtlasObject _uiAtlasObject; // 0x60
	private GameObject _effectPrefab; // 0x68
	private RectTransform _effectTransform; // 0x70
	private AnimationWrapper _animWrapper; // 0x78
	private Tween m_enterTween; // 0x80
	private Tween m_variationTween; // 0x88
	private GameObject m_variationEffect; // 0x90
	private Boolean m_isInited; // 0x98
	private TagAdapter m_tagAdapter; // 0xa0
	private MainTransParam m_cachedMainTransParam; // 0xa8
	private Boolean m_waitForNextClick; // 0xc8
	private Boolean m_waitForAnimEnd; // 0xc9
	private UIPageFinder m_pageFinder; // 0xd0
	private FadeSwitchTween m_mainTransSwitch; // 0xe0
	private static DelegateBridge __Hotfix0_get_mainTransSwitch; // 0x0
	private static DelegateBridge __Hotfix0_OnEnable; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_TransCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_Reset; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0_EventOnMainPanelClicked; // 0x30
	private static DelegateBridge __Hotfix0__RenderMainTrans; // 0x38
	private static DelegateBridge __Hotfix0__WaitForNextClick; // 0x40
	private static DelegateBridge __Hotfix0__ShowVariationTrans; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	protected FadeSwitchTween mainTransSwitch { get; }

	// RVA: 0x2b730e4 VA: 0x759518b0e4
	protected FadeSwitchTween get_mainTransSwitch() { }
	// RVA: 0x2b731c0 VA: 0x759518b1c0
	private Void OnEnable() { }
	// RVA: 0x2b73258 VA: 0x759518b258
	public override Void Render(RoguelikeDungeonZoneViewProperty property) { }
	// RVA: 0x2b736f0 VA: 0x759518b6f0
	public override IEnumerator TransCoroutine() { }
	// RVA: 0x2b737c4 VA: 0x759518b7c4
	public override Void Reset() { }
	// RVA: 0x2b73330 VA: 0x759518b330
	private Void _InitIfNot() { }
	// RVA: 0x2b73888 VA: 0x759518b888
	public Void EventOnMainPanelClicked() { }
	// RVA: 0x2b733c4 VA: 0x759518b3c4
	private Void _RenderMainTrans(MainTransParam zoneParam) { }
	// RVA: 0x2b738f0 VA: 0x759518b8f0
	private IEnumerator _WaitForNextClick() { }
	// RVA: 0x2b739c4 VA: 0x759518b9c4
	private IEnumerator _ShowVariationTrans() { }
	// RVA: 0x2b73a98 VA: 0x759518ba98
	public Void .ctor() { }
	// RVA: 0x2b73bb4 VA: 0x759518bbb4
	private Boolean <TransCoroutine>b__33_0() { }
	// RVA: 0x2b73bc8 VA: 0x759518bbc8
	private Boolean <_ShowVariationTrans>b__39_0() { }
}
```