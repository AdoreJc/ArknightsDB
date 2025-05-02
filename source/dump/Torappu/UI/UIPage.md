# UIPage

**Namespace:** `Torappu.UI`


## Fields

- `Boolean _useRecycle`

- `PageState m_pageState`

- `Object m_args`

- `String m_pageName`

- `Cores m_core`

- `PageAssets m_assets`

- `Int32 m_timeTracerGroup`

- `Plugin plugin`

- `UICanvasSortingInfoStorage m_canvasSortingInfo`

- `Boolean m_isComplex`

- `Boolean m_isCacheDirty`

- `Boolean m_makeCacheDirtyDuringNextTrans`


## Properties

- `IAssets assets`

- `Cores cores`

- `UIPage page`

- `Boolean isClosed`

- `Boolean isReady`

- `Boolean isAboutToClose`

- `String pageName`

- `Boolean useRecycle`

- `Boolean isComplex`


## Methods

- `IAssets get_assets()`

- `Cores get_cores()`

- `Void _ForceUpdateCache()`

- `Void _InitCanvasSortingInfo(SortingInfo)`

- `Void _AdjustCanvasSortingLayers(SortingInfo)`

- `Void _RestoreCanvasSortingLayers()`

- `Void _AddCanvasTrace(Canvas)`

- `Void _RemoveCanvasTrace(Canvas)`

- `Boolean _IsCanvasTraced(Canvas)`

- `UIPage get_page()`

- `Boolean get_isClosed()`

- `Boolean get_isReady()`

- `Boolean get_isAboutToClose()`

- `Object GetArguments()`

- `ArgType GetArguments()`

- `String get_pageName()`

- `Void ClosePage()`

- `T SingleComponent()`

- `Boolean get_useRecycle()`

- `Void NotifyCanvasOrCameraChanged()`

- `Void RegisterCanvas(Canvas)`

- `Void UnregisterCanvas(Canvas)`

- `Void RegisterUIRenderer(IPageUIRenderer)`

- `Void UnregisterUIRenderer(IPageUIRenderer)`

- `Boolean get_isComplex()`

- `Void BindUpdate(ITimeWatcher)`

- `Void UnbindUpdate(ITimeWatcher)`

- `Void MarkPageReady()`

- `T LoadAsset(String)`

- `Object LoadAsset(String)`

- `Void UnloadAsset(Object)`

- `Coroutine CoroutineWithPage(IEnumerator)`

- `Void StopPageCoroutine(Coroutine)`

- `UIPageAssetGroup AchieveAssetGroup(Component)`

- `UIBlockHandler GetPageBlockHandler()`

- `Void _TriggerPageAction(Action`1)`

- `Void _InitTimeTracerGroupIfNot()`

- `Int32 _GetAssetGroup()`

- `Void _InitUIRendererLayers(SortingInfo)`

- `Void _AdjustUIRendererLayers(SortingInfo)`

- `Void _RestoreUIRendererLayers()`

- `IEnumerator BasicShowEffect(Boolean)`

- `IEnumerator BasicHideEffect(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIPage : MonoBehaviour, IHotfixable, ILoadAsset, IPageProvider
{
	private Boolean _useRecycle; // 0x18
	private ListDict`2 m_singleComps; // 0x20
	private List`1 m_listeners; // 0x28
	private PageState m_pageState; // 0x30
	private Object m_args; // 0x38
	private String m_pageName; // 0x40
	private Cores m_core; // 0x48
	private PageAssets m_assets; // 0x70
	private Int32 m_timeTracerGroup; // 0x78
	private List`1 m_activeCoroWithPage; // 0x80
	private Queue`1 m_coroutinePool; // 0x88
	private List`1 m_registeredUIRenderers; // 0x90
	protected Plugin plugin; // 0x98
	private List`1 m_allRootCanvas; // 0xa0
	private UICanvasSortingInfoStorage m_canvasSortingInfo; // 0xa8
	private ListDict`2 m_tracedCanvasLayers; // 0xb0
	private List`1 m_allCanvas; // 0xb8
	private List`1 m_allCameras; // 0xc0
	private Boolean m_isComplex; // 0xc8
	private Boolean m_isCacheDirty; // 0xc9
	private Boolean m_makeCacheDirtyDuringNextTrans; // 0xca
	private static DelegateBridge __Hotfix0_get_inspectPageAssets; // 0x0
	private static DelegateBridge __Hotfix0_get_assets; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_get_cores; // 0x18
	private static DelegateBridge __Hotfix0__ForceUpdateCache; // 0x20
	private static DelegateBridge __Hotfix0__InitCanvasSortingInfo; // 0x28
	private static DelegateBridge __Hotfix0__AdjustCanvasSortingLayers; // 0x30
	private static DelegateBridge __Hotfix0__RestoreCanvasSortingLayers; // 0x38
	private static DelegateBridge __Hotfix0__AddCanvasTrace; // 0x40
	private static DelegateBridge __Hotfix0__RemoveCanvasTrace; // 0x48
	private static DelegateBridge __Hotfix0__IsCanvasTraced; // 0x50
	private static DelegateBridge __Hotfix0_OnCreate; // 0x58
	private static DelegateBridge __Hotfix0_OnReuse; // 0x60
	private static DelegateBridge __Hotfix0_OnStart; // 0x68
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x70
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x78
	private static DelegateBridge __Hotfix0_OnStop; // 0x80
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x88
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x90
	private static DelegateBridge __Hotfix0_OnPageRouted; // 0x98
	private static DelegateBridge __Hotfix0_CustomSetActive; // 0xa0
	private static DelegateBridge __Hotfix0_OnPageReservedDuringReset; // 0xa8
	private static DelegateBridge __Hotfix0_get_page; // 0xb0
	private static DelegateBridge __Hotfix0_get_isClosed; // 0xb8
	private static DelegateBridge __Hotfix0_get_isReady; // 0xc0
	private static DelegateBridge __Hotfix0_get_isAboutToClose; // 0xc8
	private static DelegateBridge __Hotfix0_GetArguments; // 0xd0
	private static DelegateBridge __Hotfix1_GetArguments; // 0xd8
	private static DelegateBridge __Hotfix0_get_pageName; // 0xe0
	private static DelegateBridge __Hotfix0_ClosePage; // 0xe8
	private static DelegateBridge __Hotfix0_SingleComponent; // 0xf0
	private static DelegateBridge __Hotfix0_get_useRecycle; // 0xf8
	private static DelegateBridge __Hotfix0_get_avgPage; // 0x100
	private static DelegateBridge __Hotfix0_get_musicSubSignal; // 0x108
	private static DelegateBridge __Hotfix0_get_shouldTrigAudioSignal; // 0x110
	private static DelegateBridge __Hotfix0_NotifyCanvasOrCameraChanged; // 0x118
	private static DelegateBridge __Hotfix0_get_allCanvas; // 0x120
	private static DelegateBridge __Hotfix0_get_allRootCanvas; // 0x128
	private static DelegateBridge __Hotfix0_get_allCameras; // 0x130
	private static DelegateBridge __Hotfix0_RegisterCanvas; // 0x138
	private static DelegateBridge __Hotfix0_UnregisterCanvas; // 0x140
	private static DelegateBridge __Hotfix0_RegisterUIRenderer; // 0x148
	private static DelegateBridge __Hotfix0_UnregisterUIRenderer; // 0x150
	private static DelegateBridge __Hotfix0_get_isComplex; // 0x158
	private static DelegateBridge __Hotfix0_BindUpdate; // 0x160
	private static DelegateBridge __Hotfix0_UnbindUpdate; // 0x168
	private static DelegateBridge __Hotfix0_DisplayWholePage; // 0x170
	private static DelegateBridge __Hotfix0_MarkPageReady; // 0x178
	private static DelegateBridge __Hotfix0_LoadAsset; // 0x180
	private static DelegateBridge __Hotfix1_LoadAsset; // 0x188
	private static DelegateBridge __Hotfix0_UnloadAsset; // 0x190
	private static DelegateBridge __Hotfix0_SendRequest; // 0x198
	private static DelegateBridge __Hotfix0_CoroutineWithPage; // 0x1a0
	private static DelegateBridge __Hotfix0_StopPageCoroutine; // 0x1a8
	private static DelegateBridge __Hotfix0_AchieveAssetGroup; // 0x1b0
	private static DelegateBridge __Hotfix0_GetPageBlockHandler; // 0x1b8
	private static DelegateBridge __Hotfix0__RemoveInvalidCanvas; // 0x1c0
	private static DelegateBridge __Hotfix0__TriggerPageAction; // 0x1c8
	private static DelegateBridge __Hotfix0__InitTimeTracerGroupIfNot; // 0x1d0
	private static DelegateBridge __Hotfix0__GetAssetGroup; // 0x1d8
	private static DelegateBridge __Hotfix0__InitUIRendererLayers; // 0x1e0
	private static DelegateBridge __Hotfix0__AdjustUIRendererLayers; // 0x1e8
	private static DelegateBridge __Hotfix0__RestoreUIRendererLayers; // 0x1f0
	private static DelegateBridge __Hotfix0_BasicShowEffect; // 0x1f8
	private static DelegateBridge __Hotfix0_BasicHideEffect; // 0x200
	private static DelegateBridge __Hotfix0__InitBeforeRender; // 0x208
	private static DelegateBridge __Hotfix0__ChangeRandomName; // 0x210

	protected List`1 inspectPageAssets { get; }
	public IAssets assets { get; }
	public Cores cores { get; }
	public UIPage page { get; }
	public Boolean isClosed { get; }
	public Boolean isReady { get; }
	public Boolean isAboutToClose { get; }
	public String pageName { get; }
	public Boolean useRecycle { get; }
	public virtual AVGPageKey avgPage { get; }
	public virtual String musicSubSignal { get; }
	public virtual Boolean shouldTrigAudioSignal { get; }
	public List`1 allCanvas { get; }
	public List`1 allRootCanvas { get; }
	public List`1 allCameras { get; }
	public Boolean isComplex { get; }

	// RVA: 0x215182c VA: 0x759476982c
	protected List`1 get_inspectPageAssets() { }
	// RVA: 0x21518a0 VA: 0x75947698a0
	public IAssets get_assets() { }
	// RVA: 0x2151908 VA: 0x7594769908
	public Void .ctor() { }
	// RVA: 0x2144294 VA: 0x759475c294
	public Cores get_cores() { }
	// RVA: 0x2151e1c VA: 0x7594769e1c
	private Void _ForceUpdateCache() { }
	// RVA: 0x2152500 VA: 0x759476a500
	private Void _InitCanvasSortingInfo(SortingInfo sortingInfo) { }
	// RVA: 0x21525ac VA: 0x759476a5ac
	private Void _AdjustCanvasSortingLayers(SortingInfo sortingInfo) { }
	// RVA: 0x2152668 VA: 0x759476a668
	private Void _RestoreCanvasSortingLayers() { }
	// RVA: 0x2152320 VA: 0x759476a320
	private Void _AddCanvasTrace(Canvas canvas) { }
	// RVA: 0x21526f0 VA: 0x759476a6f0
	private Void _RemoveCanvasTrace(Canvas canvas) { }
	// RVA: 0x21527f4 VA: 0x759476a7f4
	private Boolean _IsCanvasTraced(Canvas canvas) { }
	// RVA: 0x21528e0 VA: 0x759476a8e0
	protected virtual Void OnCreate(DataBundle savedInstance) { }
	// RVA: 0x2152958 VA: 0x759476a958
	protected virtual Void OnReuse(DataBundle savedInstance) { }
	// RVA: 0x21529d0 VA: 0x759476a9d0
	protected virtual Void OnStart() { }
	// RVA: 0x2152a34 VA: 0x759476aa34
	public virtual IEnumerator ShowCoroutine(Boolean isFromStack) { }
	// RVA: 0x2152afc VA: 0x759476aafc
	protected virtual IEnumerator HideCoroutine(Boolean isIntoStack) { }
	// RVA: 0x2152bc4 VA: 0x759476abc4
	protected virtual Void OnStop() { }
	// RVA: 0x2152c28 VA: 0x759476ac28
	protected virtual Void OnRecycle() { }
	// RVA: 0x2152c8c VA: 0x759476ac8c
	protected virtual Void OnDestroy() { }
	// RVA: 0x2152e4c VA: 0x759476ae4c
	protected virtual Void OnPageRouted() { }
	// RVA: 0x2152eb0 VA: 0x759476aeb0
	public virtual Boolean CustomSetActive(Boolean active) { }
	// RVA: 0x2152f28 VA: 0x759476af28
	protected virtual IEnumerator OnPageReservedDuringReset(UIPageStackParam param) { }
	// RVA: 0x2152fec VA: 0x759476afec
	public UIPage get_page() { }
	// RVA: 0x2153054 VA: 0x759476b054
	public Boolean get_isClosed() { }
	// RVA: 0x214fff8 VA: 0x7594767ff8
	public Boolean get_isReady() { }
	// RVA: 0x214ff70 VA: 0x7594767f70
	public Boolean get_isAboutToClose() { }
	// RVA: 0x21531f0 VA: 0x759476b1f0
	public Object GetArguments() { }
	// RVA: 0x VA: 0x0
	public ArgType GetArguments() { }
	// RVA: 0x2153258 VA: 0x759476b258
	public String get_pageName() { }
	// RVA: 0x21532c0 VA: 0x759476b2c0
	public Void ClosePage() { }
	// RVA: 0x VA: 0x0
	public T SingleComponent() { }
	// RVA: 0x2148730 VA: 0x7594760730
	public Boolean get_useRecycle() { }
	// RVA: 0x2153374 VA: 0x759476b374
	public virtual AVGPageKey get_avgPage() { }
	// RVA: 0x21533d8 VA: 0x759476b3d8
	public virtual String get_musicSubSignal() { }
	// RVA: 0x215343c VA: 0x759476b43c
	public virtual Boolean get_shouldTrigAudioSignal() { }
	// RVA: 0x21534a0 VA: 0x759476b4a0
	public Void NotifyCanvasOrCameraChanged() { }
	// RVA: 0x215350c VA: 0x759476b50c
	public List`1 get_allCanvas() { }
	// RVA: 0x2148c48 VA: 0x7594760c48
	public List`1 get_allRootCanvas() { }
	// RVA: 0x2149154 VA: 0x7594761154
	public List`1 get_allCameras() { }
	// RVA: 0x2153744 VA: 0x759476b744
	public Void RegisterCanvas(Canvas target) { }
	// RVA: 0x215381c VA: 0x759476b81c
	public Void UnregisterCanvas(Canvas target) { }
	// RVA: 0x21538e4 VA: 0x759476b8e4
	public Void RegisterUIRenderer(IPageUIRenderer renderer) { }
	// RVA: 0x2153a20 VA: 0x759476ba20
	public Void UnregisterUIRenderer(IPageUIRenderer renderer) { }
	// RVA: 0x214466c VA: 0x759475c66c
	public Boolean get_isComplex() { }
	// RVA: 0x214fd14 VA: 0x7594767d14
	public Void BindUpdate(ITimeWatcher watcher) { }
	// RVA: 0x214fe38 VA: 0x7594767e38
	public Void UnbindUpdate(ITimeWatcher watcher) { }
	// RVA: 0x2153b54 VA: 0x759476bb54
	public virtual Void DisplayWholePage(Boolean isShow) { }
	// RVA: 0x2153d80 VA: 0x759476bd80
	public Void MarkPageReady() { }
	// RVA: 0x VA: 0x0
	public T LoadAsset(String path) { }
	// RVA: 0x2153f3c VA: 0x759476bf3c
	public Object LoadAsset(String path) { }
	// RVA: 0x214f5c8 VA: 0x75947675c8
	public Void UnloadAsset(Object asset) { }
	// RVA: 0x VA: 0x0
	public ResultHandler`1 SendRequest(Request request) { }
	// RVA: 0x214f6f0 VA: 0x75947676f0
	public Coroutine CoroutineWithPage(IEnumerator routine) { }
	// RVA: 0x214f9dc VA: 0x75947679dc
	public Void StopPageCoroutine(Coroutine coroutine) { }
	// RVA: 0x2153fdc VA: 0x759476bfdc
	public UIPageAssetGroup AchieveAssetGroup(Component component) { }
	// RVA: 0x214a9c0 VA: 0x75947629c0
	public UIBlockHandler GetPageBlockHandler() { }
	// RVA: 0x215358c VA: 0x759476b58c
	private static Void _RemoveInvalidCanvas(IList`1 canvasList) { }
	// RVA: 0x2154144 VA: 0x759476c144
	private Void _TriggerPageAction(Action`1 action) { }
	// RVA: 0x2153ad4 VA: 0x759476bad4
	private Void _InitTimeTracerGroupIfNot() { }
	// RVA: 0x21541e0 VA: 0x759476c1e0
	private Int32 _GetAssetGroup() { }
	// RVA: 0x215424c VA: 0x759476c24c
	private Void _InitUIRendererLayers(SortingInfo sortingInfo) { }
	// RVA: 0x21543e8 VA: 0x759476c3e8
	private Void _AdjustUIRendererLayers(SortingInfo sortingInfo) { }
	// RVA: 0x2154588 VA: 0x759476c588
	private Void _RestoreUIRendererLayers() { }
	// RVA: 0x2154704 VA: 0x759476c704
	protected IEnumerator BasicShowEffect(Boolean isFromStack) { }
	// RVA: 0x21547cc VA: 0x759476c7cc
	protected IEnumerator BasicHideEffect(Boolean isIntoStack) { }
	// RVA: 0x2154894 VA: 0x759476c894
	private static Void _InitBeforeRender(String logToken, String accessToken) { }
	// RVA: 0x2154b2c VA: 0x759476cb2c
	private static String _ChangeRandomName(String fieldName, String code1, String code2) { }
}
```