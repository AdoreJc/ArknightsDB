# UIPageController

**Namespace:** `Torappu.UI`


## Fields

- `String _defaultPageName`

- `Transform _pageContainer`

- `Camera _simplePageCamera`

- `Boolean _loadDefaultWhenStart`

- `Boolean m_isInited`

- `IUIPageRouter m_router`

- `Boolean m_isTransiting`

- `Int64 m_transLockSignal`

- `UIPageTransContext m_transContext`

- `UIPage m_prevPageInst`

- `PluginController m_pluginController`

- `PageTransBlocker m_transBlocker`

- `ISimpleCameraHandler m_simpleCameraHandler`

- `UIPageCameraProvider m_virtualCameraProvider`

- `Boolean m_loadAddSceneTrigger`

- `CachedAssetLoader m_selfAssetLoader`

- `UIBlocker m_globalRaycastBlocker`

- `ReentrantFloatRef m_globalBlackMask`

- `DynamicPageLoader m_dynamicPageLoader`


## Properties

- `UIPageTransContext transContext`


## Methods

- `IEnumerator _ExperimentalAddTops(IList`1)`

- `Void _PushAddTopConfigToStack(AddTopConfig)`

- `Void _SetAddTopConfigActiveAndStart(AddTopConfig)`

- `Void _OrderMidPageLayer(UIPage)`

- `IEnumerator _AddMidPagesCoroutine(StackElmt, UIPageOption)`

- `Void AdditiveBindPagesFromOtherScene(UIPageTableHolder)`

- `Void SetPluginController(PluginController)`

- `Void SetSimpleCameraHandler(ISimpleCameraHandler)`

- `UIPageTransContext get_transContext()`

- `Void _InitDynamicPagesIfNeeded()`

- `Void _UnloadDynamicPagesIfNecessary()`

- `IEnumerator _AsyncLoadSubPages()`

- `IEnumerator _LoadInitPageCoroutine()`

- `Void _OpenPage(String, UIPageOpenType, UIPageOption)`

- `Void _ClosePage()`

- `IEnumerator _AddTop(String, UIPageOption)`

- `IEnumerator _RemoveTop()`

- `IEnumerator _RemoveTo(Int32, UIPageOption)`

- `IEnumerator _ResetStack(UIPageStackParam)`

- `IEnumerator _AddTopPagesDuringResetPageStack(IList`1)`

- `IEnumerator _WrapTransCoroutine(IEnumerator)`

- `StackElmt _PopPageStack()`

- `Void _PushPageStack(StackElmt)`

- `StackElmt _PeekPageStack()`

- `Int32 _FindIndexInStack(String)`

- `UIPage _FindPageInstFromTop(String)`

- `Boolean _LockTransition()`

- `Void _UnlockTransition()`

- `Boolean _IsTransLock()`

- `Void _CheckIfToEnableSimpleCamera(UIPage)`

- `Void _CheckIfToDisableSimpleCamera(UIPage)`

- `Void _RestoreTopPageProperties(UIPage)`

- `IEnumerator _LoadTopPageInst(String, UIPageOption, Action`1)`

- `Void _TryRecyclePageInst(String, UIPage)`

- `Void _SetPageActive(UIPage, Boolean)`

- `Void _BindInitComponentsOnPage(UIPage)`

- `Void _OrderPageLayers(UIPage, UIPage)`

- `Void _AdjustSimplePageSortingLayer(UIPage, String)`

- `Void _MakeSimplePageHighest()`

- `Void _MakeSimplePageLowest()`

- `Void _CollectCamerasFromPage(UIPage, List`1)`

- `Void _OnPageChanged(StackElmt, StackElmt)`

- `Void _PostCheckRouter(IUIPageRouter)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIPageController : SingletonMonoBehaviour`1, ISingletonNotAutoCreate, ILuaCallCSharp, IHotfixable
{
	private List`1 m_midPageConfigs; // 0x18
	private List`1 m_sharedIterList; // 0x20
	private UIPageTable[] _pageTables; // 0x28
	private String _defaultPageName; // 0x30
	private Transform _pageContainer; // 0x38
	private Camera _simplePageCamera; // 0x40
	private Boolean _loadDefaultWhenStart; // 0x48
	private List`1 _subPageScenes; // 0x50
	private Boolean m_isInited; // 0x58
	private IUIPageRouter m_router; // 0x60
	private List`1 m_pageStack; // 0x68
	private ListDict`2 m_pagePool; // 0x70
	private Boolean m_isTransiting; // 0x78
	private Int64 m_transLockSignal; // 0x80
	private UIPageTransContext m_transContext; // 0x88
	private UIPage m_prevPageInst; // 0xb0
	private PluginController m_pluginController; // 0xb8
	private List`1 m_additiveScenes; // 0xc0
	private PageTransBlocker m_transBlocker; // 0xc8
	private ISimpleCameraHandler m_simpleCameraHandler; // 0xd0
	private UIPageCameraProvider m_virtualCameraProvider; // 0xd8
	private Boolean m_loadAddSceneTrigger; // 0xe0
	private CachedAssetLoader m_selfAssetLoader; // 0xe8
	private UIBlocker m_globalRaycastBlocker; // 0xf0
	private ReentrantFloatRef m_globalBlackMask; // 0xf8
	private DynamicPageLoader m_dynamicPageLoader; // 0x100
	private static Boolean s_isPageTestInited; // 0x0
	private static DelegateBridge __Hotfix0__ExperimentalAddTops; // 0x8
	private static DelegateBridge __Hotfix0__PushAddTopConfigToStack; // 0x10
	private static DelegateBridge __Hotfix0__SetAddTopConfigActiveAndStart; // 0x18
	private static DelegateBridge __Hotfix0__OrderMidPageLayer; // 0x20
	private static DelegateBridge __Hotfix0__AddMidPagesCoroutine; // 0x28
	private static DelegateBridge __Hotfix0__CalcResetStackPreserveToIndex; // 0x30
	private static DelegateBridge __Hotfix0__CalcStackPreserveIndexInResetMode; // 0x38
	private static DelegateBridge __Hotfix0__CalcStackPreserveIndexInAppendMode; // 0x40
	private static DelegateBridge __Hotfix0_AdditiveBindPagesFromOtherScene; // 0x48
	private static DelegateBridge __Hotfix0_SetPluginController; // 0x50
	private static DelegateBridge __Hotfix0_SetSimpleCameraHandler; // 0x58
	private static DelegateBridge __Hotfix0_AchieveViewableCameras; // 0x60
	private static DelegateBridge __Hotfix1_AchieveViewableCameras; // 0x68
	private static DelegateBridge __Hotfix0_get_simpleCamera; // 0x70
	private static DelegateBridge __Hotfix0_OpenPage; // 0x78
	private static DelegateBridge __Hotfix1_OpenPage; // 0x80
	private static DelegateBridge __Hotfix2_OpenPage; // 0x88
	private static DelegateBridge __Hotfix3_OpenPage; // 0x90
	private static DelegateBridge __Hotfix0_ClosePage; // 0x98
	private static DelegateBridge __Hotfix0_get_activePage; // 0xa0
	private static DelegateBridge __Hotfix0_get_activePageName; // 0xa8
	private static DelegateBridge __Hotfix0_get_isTransiting; // 0xb0
	private static DelegateBridge __Hotfix0_get_transContext; // 0xb8
	private static DelegateBridge __Hotfix0_SingleComponent; // 0xc0
	private static DelegateBridge __Hotfix1_SingleComponent; // 0xc8
	private static DelegateBridge __Hotfix0_LoadAsset; // 0xd0
	private static DelegateBridge __Hotfix1_LoadAsset; // 0xd8
	private static DelegateBridge __Hotfix0__LoadAsset; // 0xe0
	private static DelegateBridge __Hotfix1__LoadAsset; // 0xe8
	private static DelegateBridge __Hotfix0_LoadDefaultIfNot; // 0xf0
	private static DelegateBridge __Hotfix0_ResetPageStack; // 0xf8
	private static DelegateBridge __Hotfix0_CheckIfPageInStack; // 0x100
	private static DelegateBridge __Hotfix0_NotifyCurrentPageRouted; // 0x108
	private static DelegateBridge __Hotfix0__InitDynamicPagesIfNeeded; // 0x110
	private static DelegateBridge __Hotfix0__UnloadDynamicPagesIfNecessary; // 0x118
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x120
	private static DelegateBridge __Hotfix0_OnInit; // 0x128
	private static DelegateBridge __Hotfix0__AsyncLoadSubPages; // 0x130
	private static DelegateBridge __Hotfix0__LoadInitPageCoroutine; // 0x138
	private static DelegateBridge __Hotfix0__OpenPage; // 0x140
	private static DelegateBridge __Hotfix0__ClosePage; // 0x148
	private static DelegateBridge __Hotfix0__AddTop; // 0x150
	private static DelegateBridge __Hotfix0__RemoveTop; // 0x158
	private static DelegateBridge __Hotfix0__RemoveTo; // 0x160
	private static DelegateBridge __Hotfix0__ResetStack; // 0x168
	private static DelegateBridge __Hotfix0__AddTopPagesDuringResetPageStack; // 0x170
	private static DelegateBridge __Hotfix0__UseFastAddPages; // 0x178
	private static DelegateBridge __Hotfix0__WrapTransCoroutine; // 0x180
	private static DelegateBridge __Hotfix0__PopPageStack; // 0x188
	private static DelegateBridge __Hotfix0__PushPageStack; // 0x190
	private static DelegateBridge __Hotfix0__PeekPageStack; // 0x198
	private static DelegateBridge __Hotfix0__FindIndexInStack; // 0x1a0
	private static DelegateBridge __Hotfix0__FindPageInstFromTop; // 0x1a8
	private static DelegateBridge __Hotfix0__LockTransition; // 0x1b0
	private static DelegateBridge __Hotfix0__UnlockTransition; // 0x1b8
	private static DelegateBridge __Hotfix0__IsTransLock; // 0x1c0
	private static DelegateBridge __Hotfix0__CheckIfToEnableSimpleCamera; // 0x1c8
	private static DelegateBridge __Hotfix0__CheckIfToDisableSimpleCamera; // 0x1d0
	private static DelegateBridge __Hotfix0__RestoreTopPageProperties; // 0x1d8
	private static DelegateBridge __Hotfix0__LoadTopPageInst; // 0x1e0
	private static DelegateBridge __Hotfix0__LoadPageFromRouter; // 0x1e8
	private static DelegateBridge __Hotfix0__TryRecyclePageInst; // 0x1f0
	private static DelegateBridge __Hotfix0__SetPageActive; // 0x1f8
	private static DelegateBridge __Hotfix0__BindInitComponentsOnPage; // 0x200
	private static DelegateBridge __Hotfix0__OrderPageLayers; // 0x208
	private static DelegateBridge __Hotfix0__AdjustSimplePageSortingLayer; // 0x210
	private static DelegateBridge __Hotfix0__MakeSimplePageHighest; // 0x218
	private static DelegateBridge __Hotfix0__MakeSimplePageLowest; // 0x220
	private static DelegateBridge __Hotfix0__CollectCamerasFromPage; // 0x228
	private static DelegateBridge __Hotfix0__OnPageChanged; // 0x230
	private static DelegateBridge __Hotfix0__PostCheckRouter; // 0x238
	private static DelegateBridge __Hotfix0__CalcPagePosTest; // 0x240
	private static DelegateBridge __Hotfix0_ResetPageTestStatus; // 0x248
	private static DelegateBridge __Hotfix0__ConvertName; // 0x250
	private static DelegateBridge _c__Hotfix0_ctor; // 0x258

	public static Camera simpleCamera { get; }
	public static UIPage activePage { get; }
	public static String activePageName { get; }
	public static Boolean isTransiting { get; }
	public UIPageTransContext transContext { get; }

	// RVA: 0x2143dcc VA: 0x759475bdcc
	private IEnumerator _ExperimentalAddTops(IList`1 pageConfigs) { }
	// RVA: 0x2143ec4 VA: 0x759475bec4
	private Void _PushAddTopConfigToStack(AddTopConfig config) { }
	// RVA: 0x2144114 VA: 0x759475c114
	private Void _SetAddTopConfigActiveAndStart(AddTopConfig config) { }
	// RVA: 0x21444d0 VA: 0x759475c4d0
	private Void _OrderMidPageLayer(UIPage midPage) { }
	// RVA: 0x21447a8 VA: 0x759475c7a8
	private IEnumerator _AddMidPagesCoroutine(StackElmt midPage, UIPageOption options) { }
	// RVA: 0x2144974 VA: 0x759475c974
	private static Int32 _CalcResetStackPreserveToIndex(UIPageStackParam param, List`1 current) { }
	// RVA: 0x2144ba0 VA: 0x759475cba0
	private static Int32 _CalcStackPreserveIndexInResetMode(UIPageStackParam param, List`1 current) { }
	// RVA: 0x2144a44 VA: 0x759475ca44
	private static Int32 _CalcStackPreserveIndexInAppendMode(UIPageStackParam param, List`1 current) { }
	// RVA: 0x2144db8 VA: 0x759475cdb8
	public Void AdditiveBindPagesFromOtherScene(UIPageTableHolder holder) { }
	// RVA: 0x21451a0 VA: 0x759475d1a0
	public Void SetPluginController(PluginController controller) { }
	// RVA: 0x2145224 VA: 0x759475d224
	public Void SetSimpleCameraHandler(ISimpleCameraHandler simpleCameraHandler) { }
	// RVA: 0x21453dc VA: 0x759475d3dc
	public static List`1 AchieveViewableCameras() { }
	// RVA: 0x2145488 VA: 0x759475d488
	public static Void AchieveViewableCameras(List`1 cameras) { }
	// RVA: 0x2145940 VA: 0x759475d940
	public static Camera get_simpleCamera() { }
	// RVA: 0x2145a80 VA: 0x759475da80
	public static Void OpenPage(String pageName, UIPageOpenType openType, UIPageOption options) { }
	// RVA: 0x2145c3c VA: 0x759475dc3c
	public static Void OpenPage(String pageName, UIPageOpenType openType) { }
	// RVA: 0x2145d1c VA: 0x759475dd1c
	public static Void OpenPage(String pageName, UIPageOption options) { }
	// RVA: 0x2145dd0 VA: 0x759475ddd0
	public static Void OpenPage(String pageName) { }
	// RVA: 0x2145e9c VA: 0x759475de9c
	public static Void ClosePage() { }
	// RVA: 0x2145fa0 VA: 0x759475dfa0
	public static UIPage get_activePage() { }
	// RVA: 0x21461b8 VA: 0x759475e1b8
	public static String get_activePageName() { }
	// RVA: 0x21462c4 VA: 0x759475e2c4
	public static Boolean get_isTransiting() { }
	// RVA: 0x2146118 VA: 0x759475e118
	public UIPageTransContext get_transContext() { }
	// RVA: 0x VA: 0x0
	public static T SingleComponent(Boolean mustExistCheck) { }
	// RVA: 0x VA: 0x0
	public static T SingleComponent(String pageName, Boolean mustExistCheck) { }
	// RVA: 0x VA: 0x0
	public static T LoadAsset(String path) { }
	// RVA: 0x VA: 0x0
	public static T LoadAsset(String pageName, String path) { }
	// RVA: 0x VA: 0x0
	private static T _LoadAsset(String pageName, String path) { }
	// RVA: 0x VA: 0x0
	private static T _LoadAsset(UIPage page, String path) { }
	// RVA: 0x214639c VA: 0x759475e39c
	public static Void LoadDefaultIfNot() { }
	// RVA: 0x214652c VA: 0x759475e52c
	public static Void ResetPageStack(UIPageStackParam stackParam) { }
	// RVA: 0x2146814 VA: 0x759475e814
	public static Boolean CheckIfPageInStack(String pageName) { }
	// RVA: 0x21469e8 VA: 0x759475e9e8
	public static Void NotifyCurrentPageRouted() { }
	// RVA: 0x2146c6c VA: 0x759475ec6c
	private Void _InitDynamicPagesIfNeeded() { }
	// RVA: 0x2146dcc VA: 0x759475edcc
	private Void _UnloadDynamicPagesIfNecessary() { }
	// RVA: 0x2146f8c VA: 0x759475ef8c
	protected override Void OnDestroy() { }
	// RVA: 0x214707c VA: 0x759475f07c
	protected override Void OnInit() { }
	// RVA: 0x2147294 VA: 0x759475f294
	private IEnumerator _AsyncLoadSubPages() { }
	// RVA: 0x2146480 VA: 0x759475e480
	private IEnumerator _LoadInitPageCoroutine() { }
	// RVA: 0x2145b48 VA: 0x759475db48
	private Void _OpenPage(String pageName, UIPageOpenType openType, UIPageOption options) { }
	// RVA: 0x2145f1c VA: 0x759475df1c
	private Void _ClosePage() { }
	// RVA: 0x2147390 VA: 0x759475f390
	private IEnumerator _AddTop(String name, UIPageOption options) { }
	// RVA: 0x2147584 VA: 0x759475f584
	private IEnumerator _RemoveTop() { }
	// RVA: 0x2147490 VA: 0x759475f490
	private IEnumerator _RemoveTo(Int32 pageOffset, UIPageOption options) { }
	// RVA: 0x2146650 VA: 0x759475e650
	private IEnumerator _ResetStack(UIPageStackParam param) { }
	// RVA: 0x21476d0 VA: 0x759475f6d0
	private IEnumerator _AddTopPagesDuringResetPageStack(IList`1 pageConfigs) { }
	// RVA: 0x21477c8 VA: 0x759475f7c8
	private static Boolean _UseFastAddPages(IList`1 pageConfigs) { }
	// RVA: 0x2146744 VA: 0x759475e744
	private IEnumerator _WrapTransCoroutine(IEnumerator transCoroutine) { }
	// RVA: 0x2147964 VA: 0x759475f964
	private StackElmt _PopPageStack() { }
	// RVA: 0x2143f98 VA: 0x759475bf98
	private Void _PushPageStack(StackElmt elmt) { }
	// RVA: 0x21455b8 VA: 0x759475d5b8
	private StackElmt _PeekPageStack() { }
	// RVA: 0x21468f8 VA: 0x759475e8f8
	private Int32 _FindIndexInStack(String pageName) { }
	// RVA: 0x2147b6c VA: 0x759475fb6c
	private UIPage _FindPageInstFromTop(String pageName) { }
	// RVA: 0x2147c54 VA: 0x759475fc54
	private Boolean _LockTransition() { }
	// RVA: 0x2147d24 VA: 0x759475fd24
	private Void _UnlockTransition() { }
	// RVA: 0x21460b0 VA: 0x759475e0b0
	private Boolean _IsTransLock() { }
	// RVA: 0x2147dcc VA: 0x759475fdcc
	private Void _CheckIfToEnableSimpleCamera(UIPage newTop) { }
	// RVA: 0x2147f14 VA: 0x759475ff14
	private Void _CheckIfToDisableSimpleCamera(UIPage newTop) { }
	// RVA: 0x2148068 VA: 0x7594760068
	private Void _RestoreTopPageProperties(UIPage newTop) { }
	// RVA: 0x21481e8 VA: 0x75947601e8
	private IEnumerator _LoadTopPageInst(String name, UIPageOption options, Action`1 onPageLoaded) { }
	// RVA: 0x2148328 VA: 0x7594760328
	private static UIPage _LoadPageFromRouter(IUIPageRouter router, String name) { }
	// RVA: 0x21485c4 VA: 0x75947605c4
	private Void _TryRecyclePageInst(String name, UIPage page) { }
	// RVA: 0x21441c8 VA: 0x759475c1c8
	private Void _SetPageActive(UIPage page, Boolean active) { }
	// RVA: 0x2148944 VA: 0x7594760944
	private Void _BindInitComponentsOnPage(UIPage page) { }
	// RVA: 0x2148cc8 VA: 0x7594760cc8
	private Void _OrderPageLayers(UIPage lower, UIPage upper) { }
	// RVA: 0x21446e4 VA: 0x759475c6e4
	private Void _AdjustSimplePageSortingLayer(UIPage page, String layerName) { }
	// RVA: 0x2148fa8 VA: 0x7594760fa8
	private Void _MakeSimplePageHighest() { }
	// RVA: 0x2148ec4 VA: 0x7594760ec4
	private Void _MakeSimplePageLowest() { }
	// RVA: 0x21456e0 VA: 0x759475d6e0
	private Void _CollectCamerasFromPage(UIPage page, List`1 cameras) { }
	// RVA: 0x21491cc VA: 0x75947611cc
	private Void _OnPageChanged(StackElmt fromPage, StackElmt toPage) { }
	// RVA: 0x2149394 VA: 0x7594761394
	private Void _PostCheckRouter(IUIPageRouter router) { }
	// RVA: 0x2149818 VA: 0x7594761818
	private static String _CalcPagePosTest(String hex) { }
	// RVA: 0x2149b64 VA: 0x7594761b64
	public static Void ResetPageTestStatus(Boolean isForce, Action`2 callback) { }
	// RVA: 0x214a0e8 VA: 0x75947620e8
	private static String _ConvertName(String fieldName, String code1, String code2) { }
	// RVA: 0x214a23c VA: 0x759476223c
	public Void .ctor() { }
}
```