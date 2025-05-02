# Act42D0EffectDetailItemView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `UIAnimationLocation _lightAnim`

- `UIAnimationLocation _itemAnim`

- `Text _cost`

- `Text _desc`

- `LayoutElement _layoutElement`

- `Single _reserveHeight`

- `CanvasGroup _canvasGroup`

- `Boolean m_isInited`

- `Act42D0EffectItemViewModel m_cachedViewModel`

- `UIPageFinder m_pageFinder`

- `TextGenerator m_textGenerator`

- `TextGenerationSettings m_textSettings`

- `Tween m_lightTween`

- `AnimationSwitchTween m_itemTween`


## Properties

- `CanvasGroup canvasGroup`


## Methods

- `CanvasGroup get_canvasGroup()`

- `Void Render(Act42D0EffectItemViewModel, Boolean)`

- `Void TriggerNewlyAddAnim()`

- `Void TriggerRemoveAnim()`

- `Void _InitIfNot()`

- `Void _UpdateDescHeight(String)`

- `Void OnRemoveClick()`

- `Void OnDestroy()`

- `Void _ClearLightTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0EffectDetailItemView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _lightAnim; // 0x18
	private UIAnimationLocation _itemAnim; // 0x28
	private Text _cost; // 0x38
	private Text _desc; // 0x40
	private LayoutElement _layoutElement; // 0x48
	private Single _reserveHeight; // 0x50
	private CanvasGroup _canvasGroup; // 0x58
	private Boolean m_isInited; // 0x60
	private Act42D0EffectItemViewModel m_cachedViewModel; // 0x68
	private UIPageFinder m_pageFinder; // 0x70
	private TextGenerator m_textGenerator; // 0x80
	private TextGenerationSettings m_textSettings; // 0x88
	private Tween m_lightTween; // 0xe8
	private AnimationSwitchTween m_itemTween; // 0xf0
	private static DelegateBridge __Hotfix0_get_canvasGroup; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_TriggerNewlyAddAnim; // 0x10
	private static DelegateBridge __Hotfix0_TriggerRemoveAnim; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__UpdateDescHeight; // 0x28
	private static DelegateBridge __Hotfix0_OnRemoveClick; // 0x30
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x38
	private static DelegateBridge __Hotfix0__ClearLightTween; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public CanvasGroup canvasGroup { get; }

	// RVA: 0x320d1bc VA: 0x75958251bc
	public CanvasGroup get_canvasGroup() { }
	// RVA: 0x320c108 VA: 0x7595824108
	public Void Render(Act42D0EffectItemViewModel viewModel, Boolean needReset) { }
	// RVA: 0x320d2b4 VA: 0x75958252b4
	public Void TriggerNewlyAddAnim() { }
	// RVA: 0x320d22c VA: 0x759582522c
	public Void TriggerRemoveAnim() { }
	// RVA: 0x320de5c VA: 0x7595825e5c
	private Void _InitIfNot() { }
	// RVA: 0x320df4c VA: 0x7595825f4c
	private Void _UpdateDescHeight(String content) { }
	// RVA: 0x320e128 VA: 0x7595826128
	public Void OnRemoveClick() { }
	// RVA: 0x320e220 VA: 0x7595826220
	private Void OnDestroy() { }
	// RVA: 0x320e2ac VA: 0x75958262ac
	private Void _ClearLightTween() { }
	// RVA: 0x320e34c VA: 0x759582634c
	public Void .ctor() { }
}
```