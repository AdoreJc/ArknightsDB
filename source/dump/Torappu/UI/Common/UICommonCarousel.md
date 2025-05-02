# UICommonCarousel

**Namespace:** `Torappu.UI.Common`


## Fields

- `RectTransform _container`

- `CanvasGroup _canvasGroup`

- `Single _fadeOutTime`

- `Tween m_hideTween`

- `Sequence m_animSequence`

- `Single m_width`

- `Single m_animTime`


## Methods

- `Void InitState()`

- `T GenCarouselItem(T)`

- `Void AddAnim(UICommonCarouselItem, Single, Action)`

- `Void PlaySequence(Boolean)`

- `Void _InstTweener(RectTransform, Single, Single, Action)`

- `Boolean _CheckItemIllegal(UICommonCarouselItem)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Common
public class UICommonCarousel : MonoBehaviour, IHotfixable
{
	private RectTransform _container; // 0x18
	private CanvasGroup _canvasGroup; // 0x20
	private Single _fadeOutTime; // 0x28
	private Tween m_hideTween; // 0x30
	private Sequence m_animSequence; // 0x38
	private Single m_width; // 0x40
	private Single m_animTime; // 0x44
	private static DelegateBridge __Hotfix0_InitState; // 0x0
	private static DelegateBridge __Hotfix0_GenCarouselItem; // 0x8
	private static DelegateBridge __Hotfix0_AddAnim; // 0x10
	private static DelegateBridge __Hotfix0_PlaySequence; // 0x18
	private static DelegateBridge __Hotfix0__InstTweener; // 0x20
	private static DelegateBridge __Hotfix0__CheckItemIllegal; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2c5d1c0 VA: 0x75952751c0
	public Void InitState() { }
	// RVA: 0x VA: 0x0
	public T GenCarouselItem(T item) { }
	// RVA: 0x2c5d340 VA: 0x7595275340
	public Void AddAnim(UICommonCarouselItem item, Single speed, Action onFinish) { }
	// RVA: 0x2c5d410 VA: 0x7595275410
	public Void PlaySequence(Boolean loop) { }
	// RVA: 0x2c5d618 VA: 0x7595275618
	private Void _InstTweener(RectTransform item, Single perferedWidth, Single speed, Action onFinish) { }
	// RVA: 0x2c5d9c8 VA: 0x75952759c8
	private Boolean _CheckItemIllegal(UICommonCarouselItem item) { }
	// RVA: 0x2c5daac VA: 0x7595275aac
	public Void .ctor() { }
}
```