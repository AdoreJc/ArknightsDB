# StageZoneTabView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Image _pic`

- `AnimationWrapper _onShowAnim`

- `CanvasGroup _canvasGroup`

- `RectTransform _timelyDropContainer`

- `UICommonTrackPoint _trackPoint`

- `IPlugin _plugin`

- `Single m_tweenPos`

- `ZoneViewType m_type`

- `StageZoneTabViewModel m_viewModel`

- `Tween m_cacheTween`

- `Tween m_cacheColorTween`

- `GameObject m_timelyObj`

- `String m_cachedDropId`

- `TrackPointViewProperty m_property`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void OnClick()`

- `Void Render(StageZoneTabViewModel, Boolean)`

- `Void _TweenAlpha(Single)`

- `Void _RenderTimelyDrop()`

- `Single <Render>b__19_0()`

- `Void <Render>b__19_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneTabView : MonoBehaviour, IHotfixable
{
	private Image _pic; // 0x18
	private AnimationWrapper _onShowAnim; // 0x20
	private CanvasGroup _canvasGroup; // 0x28
	private RectTransform _timelyDropContainer; // 0x30
	private UICommonTrackPoint _trackPoint; // 0x38
	private IPlugin _plugin; // 0x40
	private Single m_tweenPos; // 0x48
	private ZoneViewType m_type; // 0x4c
	private StageZoneTabViewModel m_viewModel; // 0x50
	private Tween m_cacheTween; // 0x58
	private Tween m_cacheColorTween; // 0x60
	private GameObject m_timelyObj; // 0x68
	private String m_cachedDropId; // 0x70
	private TrackPointViewProperty m_property; // 0x78
	private Boolean m_isInited; // 0x80
	public Action`1 onClickEvent; // 0x88
	private const String ON_SHOW_PARAM; // 0x0
	private const String BLACK_UNSELECT; // 0x0
	private const String BLACK_SELECT; // 0x0
	private const String WHITE_UNSELECT; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__TweenAlpha; // 0x18
	private static DelegateBridge __Hotfix0__RenderTimelyDrop; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2fbe350 VA: 0x75955d6350
	private Void _InitIfNot() { }
	// RVA: 0x2fbe438 VA: 0x75955d6438
	public Void OnClick() { }
	// RVA: 0x2fbd350 VA: 0x75955d5350
	public Void Render(StageZoneTabViewModel viewModel, Boolean isBlack) { }
	// RVA: 0x2fbe8b8 VA: 0x75955d68b8
	private Void _TweenAlpha(Single pos) { }
	// RVA: 0x2fbe664 VA: 0x75955d6664
	private Void _RenderTimelyDrop() { }
	// RVA: 0x2fbe95c VA: 0x75955d695c
	public Void .ctor() { }
	// RVA: 0x2fbe9cc VA: 0x75955d69cc
	private Single <Render>b__19_0() { }
	// RVA: 0x2fbe9d4 VA: 0x75955d69d4
	private Void <Render>b__19_1(Single pos) { }
}
```