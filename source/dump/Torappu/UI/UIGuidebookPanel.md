# UIGuidebookPanel

**Namespace:** `Torappu.UI`


## Fields

- `ScrollViewPager _pager`

- `UIRenderTextureImage _blurImg`

- `EasyInstancePool _pagePool`

- `EasyInstancePool _togglePool`

- `ToggleGroup _toggleGroup`

- `GameObject _exitButton`

- `CanvasGroup m_canvasGroup`

- `AbstractAssetLoader m_assetLoader`

- `Boolean m_lockClick`

- `Action m_onFinish`

- `Int32 m_forceRead`


## Properties

- `Int32 pageCount`

- `Int32 pageIndex`

- `AbstractAssetLoader assetLoader`

- `CanvasGroup canvasGroup`


## Methods

- `Int32 get_pageCount()`

- `Int32 get_pageIndex()`

- `Void set_pageIndex(Int32)`

- `AbstractAssetLoader get_assetLoader()`

- `CanvasGroup get_canvasGroup()`

- `Void Show(Action)`

- `Boolean Open(IList`1, Int32, Action)`

- `Void OnNextPage(UIGuidebookPage)`

- `Void _ClearAll()`

- `Void _BindBackPress()`

- `Void EventOnClick()`

- `Void Start()`

- `Void OnDestroy()`

- `Void <Start>b__33_0(Int32)`

- `Void <>xLuaBaseProxy_OnHide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIGuidebookPanel : UIFloatMask
{
	private const Single FADE_DURATION; // 0x0
	private const Int32 PRELOAD_FRAMES; // 0x0
	private ScrollViewPager _pager; // 0x40
	private UIRenderTextureImage _blurImg; // 0x48
	private EasyInstancePool _pagePool; // 0x50
	private EasyInstancePool _togglePool; // 0x58
	private ToggleGroup _toggleGroup; // 0x60
	private GameObject _exitButton; // 0x68
	private CanvasGroup m_canvasGroup; // 0x70
	private AbstractAssetLoader m_assetLoader; // 0x78
	private List`1 m_pages; // 0x80
	private List`1 m_toggles; // 0x88
	private Boolean m_lockClick; // 0x90
	private Action m_onFinish; // 0x98
	private Int32 m_forceRead; // 0xa0
	private static DelegateBridge __Hotfix0_get_pageCount; // 0x0
	private static DelegateBridge __Hotfix0_get_pageIndex; // 0x8
	private static DelegateBridge __Hotfix0_set_pageIndex; // 0x10
	private static DelegateBridge __Hotfix0_get_assetLoader; // 0x18
	private static DelegateBridge __Hotfix0_get_canvasGroup; // 0x20
	private static DelegateBridge __Hotfix0_Show; // 0x28
	private static DelegateBridge __Hotfix0_Open; // 0x30
	private static DelegateBridge __Hotfix0_OnNextPage; // 0x38
	private static DelegateBridge __Hotfix0__ClearAll; // 0x40
	private static DelegateBridge __Hotfix0__BindBackPress; // 0x48
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x50
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x58
	private static DelegateBridge __Hotfix0_OnHide; // 0x60
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x68
	private static DelegateBridge __Hotfix0_Start; // 0x70
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public Int32 pageCount { get; }
	public Int32 pageIndex { get; set; }
	public AbstractAssetLoader assetLoader { get; }
	protected CanvasGroup canvasGroup { get; }

	// RVA: 0x217cfdc VA: 0x7594794fdc
	public Int32 get_pageCount() { }
	// RVA: 0x217d050 VA: 0x7594795050
	public Int32 get_pageIndex() { }
	// RVA: 0x217d0c4 VA: 0x75947950c4
	private Void set_pageIndex(Int32 value) { }
	// RVA: 0x217ce50 VA: 0x7594794e50
	public AbstractAssetLoader get_assetLoader() { }
	// RVA: 0x217d278 VA: 0x7594795278
	protected CanvasGroup get_canvasGroup() { }
	// RVA: 0x217d350 VA: 0x7594795350
	public Void Show(Action callback) { }
	// RVA: 0x217d3f4 VA: 0x75947953f4
	public Boolean Open(IList`1 pageIds, Int32 forceRead, Action onFinish) { }
	// RVA: 0x217ced4 VA: 0x7594794ed4
	public Void OnNextPage(UIGuidebookPage page) { }
	// RVA: 0x217d9bc VA: 0x75947959bc
	private Void _ClearAll() { }
	// RVA: 0x217db68 VA: 0x7594795b68
	private Void _BindBackPress() { }
	// RVA: 0x217dc68 VA: 0x7594795c68
	protected override IEnumerator ShowCoroutine() { }
	// RVA: 0x217dd3c VA: 0x7594795d3c
	protected override IEnumerator HideCoroutine() { }
	// RVA: 0x217de10 VA: 0x7594795e10
	protected override Void OnHide() { }
	// RVA: 0x217de84 VA: 0x7594795e84
	public Void EventOnClick() { }
	// RVA: 0x217df74 VA: 0x7594795f74
	private Void Start() { }
	// RVA: 0x217e0dc VA: 0x75947960dc
	private Void OnDestroy() { }
	// RVA: 0x217e144 VA: 0x7594796144
	public Void .ctor() { }
	// RVA: 0x217e29c VA: 0x759479629c
	private Void <Start>b__33_0(Int32 index) { }
	// RVA: 0x217e3c0 VA: 0x75947963c0
	private Void <>xLuaBaseProxy_OnHide() { }
}
```