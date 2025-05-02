# RoguelikeRewardListView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeRewardListLayout _listLayout`

- `UIIntEvent _onClick`

- `GameObject _leaveBack`

- `CanvasGroup _canvasGroup`

- `RectTransform _transCompleteBtnHolder`

- `RoguelikeRewardStyle <uiStyle>k__BackingField`

- `Action <onCompleteBtnClick>k__BackingField`

- `RoguelikeRewardListViewModel m_cacheViewModel`

- `FadeSwitchTween m_panelBackShowTween`

- `RoguelikeRewardExtraInfoFactory m_extraInfoFactory`

- `UIStateFinder m_finder`

- `UIPageListener m_pageListener`

- `Boolean m_isEntryAnimPlayed`

- `Boolean m_inited`

- `String m_cachedTopicId`


## Properties

- `RoguelikeRewardStyle uiStyle`

- `Action onCompleteBtnClick`

- `UIPageListener pageListener`


## Methods

- `RoguelikeRewardStyle get_uiStyle()`

- `Void set_uiStyle(RoguelikeRewardStyle)`

- `Action get_onCompleteBtnClick()`

- `Void set_onCompleteBtnClick(Action)`

- `UIPageListener get_pageListener()`

- `Void _InitIfNot()`

- `Void ResetRenderStatus()`

- `Void _RenderItemList(RoguelikeRewardListViewModel)`

- `Void CheckIfFinish()`

- `IEnumerator _DismissCor()`

- `Void ToEndAnimation()`

- `IEnumerator _ApplyAnimation()`

- `Coroutine _CoroutineWithPage(IEnumerator)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardListView : DataBinder`1, IHotfixable
{
	private RoguelikeRewardListLayout _listLayout; // 0x20
	private UIIntEvent _onClick; // 0x28
	private GameObject _leaveBack; // 0x30
	private CanvasGroup _canvasGroup; // 0x38
	private RectTransform _transCompleteBtnHolder; // 0x40
	private RoguelikeRewardStyle <uiStyle>k__BackingField; // 0x48
	private Action <onCompleteBtnClick>k__BackingField; // 0x50
	private RoguelikeRewardListViewModel m_cacheViewModel; // 0x58
	private FadeSwitchTween m_panelBackShowTween; // 0x60
	private List`1 m_itemList; // 0x68
	private RoguelikeRewardExtraInfoFactory m_extraInfoFactory; // 0x70
	private UIStateFinder m_finder; // 0x78
	private UIPageListener m_pageListener; // 0x88
	private Boolean m_isEntryAnimPlayed; // 0x90
	private Boolean m_inited; // 0x91
	private String m_cachedTopicId; // 0x98
	private static DelegateBridge __Hotfix0_get_uiStyle; // 0x0
	private static DelegateBridge __Hotfix0_set_uiStyle; // 0x8
	private static DelegateBridge __Hotfix0_get_onCompleteBtnClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onCompleteBtnClick; // 0x18
	private static DelegateBridge __Hotfix0_GetDisplayList; // 0x20
	private static DelegateBridge __Hotfix0_get_pageListener; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0_ResetRenderStatus; // 0x38
	private static DelegateBridge __Hotfix0__RenderItemList; // 0x40
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x48
	private static DelegateBridge __Hotfix0_CheckIfFinish; // 0x50
	private static DelegateBridge __Hotfix0__DismissCor; // 0x58
	private static DelegateBridge __Hotfix0_ToEndAnimation; // 0x60
	private static DelegateBridge __Hotfix0__ApplyAnimation; // 0x68
	private static DelegateBridge __Hotfix0__CoroutineWithPage; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public RoguelikeRewardStyle uiStyle { get; set; }
	public Action onCompleteBtnClick { get; set; }
	protected UIPageListener pageListener { get; }

	// RVA: 0x2a9ce84 VA: 0x75950b4e84
	public RoguelikeRewardStyle get_uiStyle() { }
	// RVA: 0x2a9ceec VA: 0x75950b4eec
	public Void set_uiStyle(RoguelikeRewardStyle value) { }
	// RVA: 0x2a9cf70 VA: 0x75950b4f70
	public Action get_onCompleteBtnClick() { }
	// RVA: 0x2a9cfd8 VA: 0x75950b4fd8
	public Void set_onCompleteBtnClick(Action value) { }
	// RVA: 0x2a9d05c VA: 0x75950b505c
	public IList`1 GetDisplayList() { }
	// RVA: 0x2a9d0c4 VA: 0x75950b50c4
	protected UIPageListener get_pageListener() { }
	// RVA: 0x2a9d18c VA: 0x75950b518c
	private Void _InitIfNot() { }
	// RVA: 0x2a9d4a0 VA: 0x75950b54a0
	public Void ResetRenderStatus() { }
	// RVA: 0x2a9d508 VA: 0x75950b5508
	private Void _RenderItemList(RoguelikeRewardListViewModel viewModel) { }
	// RVA: 0x2a9db2c VA: 0x75950b5b2c
	public override Void OnValueChanged(RoguelikeRewardViewProperty property) { }
	// RVA: 0x2a9e3c0 VA: 0x75950b63c0
	public Void CheckIfFinish() { }
	// RVA: 0x2a9dcbc VA: 0x75950b5cbc
	private IEnumerator _DismissCor() { }
	// RVA: 0x2a9e598 VA: 0x75950b6598
	public Void ToEndAnimation() { }
	// RVA: 0x2a9d8fc VA: 0x75950b58fc
	private IEnumerator _ApplyAnimation() { }
	// RVA: 0x2a9d9a8 VA: 0x75950b59a8
	private Coroutine _CoroutineWithPage(IEnumerator coroutine) { }
	// RVA: 0x2a9e730 VA: 0x75950b6730
	public Void .ctor() { }
}
```