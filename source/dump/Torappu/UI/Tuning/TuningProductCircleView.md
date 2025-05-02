# TuningProductCircleView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `RectTransform _selfRectTransform`

- `Image _baseImg`

- `CanvasGroup _circleGroup`

- `Single _showAlpha`

- `Single _hideAlpha`

- `Single _fadeTweenDuration`

- `Single _radius`

- `UIPageFinder m_pageFinder`

- `Single m_currentSoundPerRound`

- `Single m_currentRotateAngle`

- `Param m_cachedParam`

- `Sequence m_sequence`

- `Boolean m_cachedIsShow`

- `String m_cachedSegmentId`


## Methods

- `Void Render(Param)`

- `Void SetCircleShowStatus(Boolean)`

- `Void UpdateTime(Single)`

- `Void _RenderCircle()`

- `Image _GeneNewImage()`

- `Sprite _LoadFragmentSprite(ILoadAsset, String)`

- `Void _RotateImageWithTargetAngle(Image, Single)`

- `Void _KillSequence()`

- `Void Start()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductCircleView : MonoBehaviour, IHotfixable, ITimeWatcher
{
	private const Single CIRCLE_FULL_ANGLE; // 0x0
	private RectTransform _selfRectTransform; // 0x18
	private Image _baseImg; // 0x20
	private CanvasGroup _circleGroup; // 0x28
	private Single _showAlpha; // 0x30
	private Single _hideAlpha; // 0x34
	private Single _fadeTweenDuration; // 0x38
	private Single _radius; // 0x3c
	private List`1 m_imageList; // 0x40
	private UIPageFinder m_pageFinder; // 0x48
	private Single m_currentSoundPerRound; // 0x58
	private Single m_currentRotateAngle; // 0x5c
	private Param m_cachedParam; // 0x60
	private Sequence m_sequence; // 0x80
	private Boolean m_cachedIsShow; // 0x88
	private String m_cachedSegmentId; // 0x90
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_SetCircleShowStatus; // 0x8
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x10
	private static DelegateBridge __Hotfix0__RenderCircle; // 0x18
	private static DelegateBridge __Hotfix0__GeneNewImage; // 0x20
	private static DelegateBridge __Hotfix0__LoadFragmentSprite; // 0x28
	private static DelegateBridge __Hotfix0__RotateImageWithTargetAngle; // 0x30
	private static DelegateBridge __Hotfix0__KillSequence; // 0x38
	private static DelegateBridge __Hotfix0_Start; // 0x40
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x233214c VA: 0x759494a14c
	public Void Render(Param viewParam) { }
	// RVA: 0x2333b80 VA: 0x759494bb80
	public Void SetCircleShowStatus(Boolean isShow) { }
	// RVA: 0x2333cc4 VA: 0x759494bcc4
	public Void UpdateTime(Single deltaTime) { }
	// RVA: 0x23337d0 VA: 0x759494b7d0
	private Void _RenderCircle() { }
	// RVA: 0x2333e24 VA: 0x759494be24
	private Image _GeneNewImage() { }
	// RVA: 0x2333ed0 VA: 0x759494bed0
	private Sprite _LoadFragmentSprite(ILoadAsset assetLoader, String spriteId) { }
	// RVA: 0x2333f80 VA: 0x759494bf80
	private Void _RotateImageWithTargetAngle(Image targetImage, Single targetAngle) { }
	// RVA: 0x2333af0 VA: 0x759494baf0
	private Void _KillSequence() { }
	// RVA: 0x2334100 VA: 0x759494c100
	private Void Start() { }
	// RVA: 0x2334170 VA: 0x759494c170
	private Void OnDestroy() { }
	// RVA: 0x23341e0 VA: 0x759494c1e0
	public Void .ctor() { }
}
```