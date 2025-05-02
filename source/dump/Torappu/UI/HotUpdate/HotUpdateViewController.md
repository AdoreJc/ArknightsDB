# HotUpdateViewController

**Namespace:** `Torappu.UI.HotUpdate`


## Fields

- `HotUpdater _hotUpdater`

- `Image _blackMask`

- `GameObject _panelMenu`

- `GameObject _panelComplete`

- `HotUpdateTipController _tipController`

- `RetryPolicy _retryPolicy`

- `Single _refreshTipPeriodTime`

- `Text _textVersion`

- `UIFadeFloatPanel _fadeFloatPanel`

- `RectTransform _ageTipsHolder`

- `UIAgeTipsEntry _ageTipsPrefab`

- `RectTransform _voicePrefHolder`

- `HotUpdateVoicePrefView _voicePrefPrefab`

- `HotUpdateNetCheckView _netCheckPrefab`

- `HotUpdateNetErrorAlert _netErrorAlertPrefab`

- `GameObject _btnNetCheck`

- `Text _textBtnNetCheck`

- `GameObject _HGSDKV2Button`

- `Text _recordNumberText`

- `HotUpdateProgressPanel _progressPanel`

- `HotUpdatePreMainInstHolder _preMainViewInst`

- `PeriodicTimer m_refreshTipTimer`

- `ConfigHandler m_networkRouterHandler`

- `HotUpdatePreMainTicker m_preMainTicker`

- `AgeTipsInst m_ageTips`

- `UIAgeTipsEntry m_ageTipsEntry`

- `HotUpdateViewProp m_viewProp`

- `HotUpdateWorkflow m_workflow`


## Methods

- `Void Start()`

- `Void OnDestroy()`

- `Void OnPlayPvEnd()`

- `Void OnStartPlayPV()`

- `Void OnNextPic()`

- `Void OnPanelFinishClick()`

- `Void EventOnRecordClick()`

- `Void OnDeleteCachedFilesClick()`

- `Void OnFloatPanalDismissClick()`

- `Void OnClearCacheBtnClick()`

- `Void OnResourceFixBtnClick()`

- `Void OnNetCheckClicked()`

- `Void EventOnHGSDKV2Clicked()`

- `IEnumerator _OnStartCoroutine()`

- `Void _SetupHintLabelContent()`

- `Void _CheckCrossThisBundleVersionToDeleteAllCachedFiles()`

- `Void _NotifyRemoteConfigReady()`

- `Void _DeleteAllLocalResAndReload()`

- `Void _DeletePersistentInfoAndReload()`

- `Void _ResumeBGM()`

- `Void Update()`

- `Void _InitAgeTips()`

- `Void _InstantiateAgeTips(GameObject)`

- `NetworkErrorDisplayer _AlertNetworkErrorWithNetCheck(String, Action)`

- `Void _AlertNetworkErrorWithNetCheckIgnoreRet(String, Action)`

- `IEnumerator AlertNetworkErrorWithNetCheckRoutine(String, Action)`

- `Void _ShowNetCheckPanel()`

- `HotUpdateViewProp GetViewProp()`

- `HotUpdateViewController GetViewCtrl()`

- `HotUpdatePreMainTicker GetPreMainTicker()`

- `Void StopCoroutineNested(IEnumerator)`

- `Void _StartWorkflow()`

- `Void <OnClearCacheBtnClick>b__37_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HotUpdate
public class HotUpdateViewController : MonoBehaviour, IHotfixable, IContext
{
	private const Single FADEIN_TIME; // 0x0
	private HotUpdater _hotUpdater; // 0x18
	private Image _blackMask; // 0x20
	private GameObject _panelMenu; // 0x28
	private GameObject _panelComplete; // 0x30
	private HotUpdateTipController _tipController; // 0x38
	private RetryPolicy _retryPolicy; // 0x40
	private Single _refreshTipPeriodTime; // 0x48
	private Text _textVersion; // 0x50
	private UIFadeFloatPanel _fadeFloatPanel; // 0x58
	private RectTransform _ageTipsHolder; // 0x60
	private UIAgeTipsEntry _ageTipsPrefab; // 0x68
	private RectTransform _voicePrefHolder; // 0x70
	private HotUpdateVoicePrefView _voicePrefPrefab; // 0x78
	private HotUpdateNetCheckView _netCheckPrefab; // 0x80
	private HotUpdateNetErrorAlert _netErrorAlertPrefab; // 0x88
	private GameObject _btnNetCheck; // 0x90
	private Text _textBtnNetCheck; // 0x98
	private GameObject _HGSDKV2Button; // 0xa0
	private Text _recordNumberText; // 0xa8
	private HotUpdateProgressPanel _progressPanel; // 0xb0
	private HotUpdatePreMainInstHolder _preMainViewInst; // 0xb8
	private PeriodicTimer m_refreshTipTimer; // 0xc0
	private ConfigHandler m_networkRouterHandler; // 0xc8
	private HotUpdatePreMainTicker m_preMainTicker; // 0xd0
	private AgeTipsInst m_ageTips; // 0xd8
	private UIAgeTipsEntry m_ageTipsEntry; // 0xe8
	private HotUpdateViewProp m_viewProp; // 0xf0
	private HotUpdateWorkflow m_workflow; // 0xf8
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x8
	private static DelegateBridge __Hotfix0_OnPlayPvEnd; // 0x10
	private static DelegateBridge __Hotfix0_OnStartPlayPV; // 0x18
	private static DelegateBridge __Hotfix0_OnNextPic; // 0x20
	private static DelegateBridge __Hotfix0_OnPanelFinishClick; // 0x28
	private static DelegateBridge __Hotfix0_EventOnRecordClick; // 0x30
	private static DelegateBridge __Hotfix0_OnDeleteCachedFilesClick; // 0x38
	private static DelegateBridge __Hotfix0_OnFloatPanalDismissClick; // 0x40
	private static DelegateBridge __Hotfix0_OnClearCacheBtnClick; // 0x48
	private static DelegateBridge __Hotfix0_OnResourceFixBtnClick; // 0x50
	private static DelegateBridge __Hotfix0_OnNetCheckClicked; // 0x58
	private static DelegateBridge __Hotfix0_EventOnHGSDKV2Clicked; // 0x60
	private static DelegateBridge __Hotfix0__OnStartCoroutine; // 0x68
	private static DelegateBridge __Hotfix0__SetupHintLabelContent; // 0x70
	private static DelegateBridge __Hotfix0__CheckCrossThisBundleVersionToDeleteAllCachedFiles; // 0x78
	private static DelegateBridge __Hotfix0__ConfirmNetworkConfig; // 0x80
	private static DelegateBridge __Hotfix0__NotifyRemoteConfigReady; // 0x88
	private static DelegateBridge __Hotfix0__DeleteAllLocalResAndReload; // 0x90
	private static DelegateBridge __Hotfix0__DeletePersistentInfoAndReload; // 0x98
	private static DelegateBridge __Hotfix0__ResumeBGM; // 0xa0
	private static DelegateBridge __Hotfix0_Update; // 0xa8
	private static DelegateBridge __Hotfix0__InitAgeTips; // 0xb0
	private static DelegateBridge __Hotfix0__InstantiateAgeTips; // 0xb8
	private static DelegateBridge __Hotfix0__AlertNetworkErrorWithNetCheck; // 0xc0
	private static DelegateBridge __Hotfix0__AlertNetworkErrorWithNetCheckIgnoreRet; // 0xc8
	private static DelegateBridge __Hotfix0_AlertNetworkErrorWithNetCheckRoutine; // 0xd0
	private static DelegateBridge __Hotfix0__ShowNetCheckPanel; // 0xd8
	private static DelegateBridge __Hotfix0__CreateWorkflowNodes; // 0xe0
	private static DelegateBridge __Hotfix0_GetViewProp; // 0xe8
	private static DelegateBridge __Hotfix0_GetViewCtrl; // 0xf0
	private static DelegateBridge __Hotfix0_GetPreMainTicker; // 0xf8
	private static DelegateBridge __Hotfix0_StopCoroutineNested; // 0x100
	private static DelegateBridge __Hotfix0__StartWorkflow; // 0x108
	private static DelegateBridge _c__Hotfix0_ctor; // 0x110
	private static DelegateBridge __Hotfix0_Torappu.UI.HotUpdate.HotUpdateWorkflow.IContext.StartCoroutine; // 0x118


	// RVA: 0x27bc9a0 VA: 0x7594dd49a0
	private Void Start() { }
	// RVA: 0x27bd1a4 VA: 0x7594dd51a4
	private Void OnDestroy() { }
	// RVA: 0x27bd440 VA: 0x7594dd5440
	public Void OnPlayPvEnd() { }
	// RVA: 0x27bd4c0 VA: 0x7594dd54c0
	public Void OnStartPlayPV() { }
	// RVA: 0x27bd540 VA: 0x7594dd5540
	public Void OnNextPic() { }
	// RVA: 0x27bd5c0 VA: 0x7594dd55c0
	public Void OnPanelFinishClick() { }
	// RVA: 0x27bd640 VA: 0x7594dd5640
	public Void EventOnRecordClick() { }
	// RVA: 0x27bd73c VA: 0x7594dd573c
	public Void OnDeleteCachedFilesClick() { }
	// RVA: 0x27bd818 VA: 0x7594dd5818
	public Void OnFloatPanalDismissClick() { }
	// RVA: 0x27bd8d4 VA: 0x7594dd58d4
	public Void OnClearCacheBtnClick() { }
	// RVA: 0x27bdaac VA: 0x7594dd5aac
	public Void OnResourceFixBtnClick() { }
	// RVA: 0x27bdc54 VA: 0x7594dd5c54
	public Void OnNetCheckClicked() { }
	// RVA: 0x27bddbc VA: 0x7594dd5dbc
	public Void EventOnHGSDKV2Clicked() { }
	// RVA: 0x27bd0f8 VA: 0x7594dd50f8
	private IEnumerator _OnStartCoroutine() { }
	// RVA: 0x27bde48 VA: 0x7594dd5e48
	private Void _SetupHintLabelContent() { }
	// RVA: 0x27bdf74 VA: 0x7594dd5f74
	private Void _CheckCrossThisBundleVersionToDeleteAllCachedFiles() { }
	// RVA: 0x27be250 VA: 0x7594dd6250
	private static Void _ConfirmNetworkConfig(Content content, Config config) { }
	// RVA: 0x27be534 VA: 0x7594dd6534
	private Void _NotifyRemoteConfigReady() { }
	// RVA: 0x27be6dc VA: 0x7594dd66dc
	private Void _DeleteAllLocalResAndReload() { }
	// RVA: 0x27be834 VA: 0x7594dd6834
	private Void _DeletePersistentInfoAndReload() { }
	// RVA: 0x27be98c VA: 0x7594dd698c
	private Void _ResumeBGM() { }
	// RVA: 0x27bea18 VA: 0x7594dd6a18
	private Void Update() { }
	// RVA: 0x27beb68 VA: 0x7594dd6b68
	private Void _InitAgeTips() { }
	// RVA: 0x27bec8c VA: 0x7594dd6c8c
	private Void _InstantiateAgeTips(GameObject prefab) { }
	// RVA: 0x27bee98 VA: 0x7594dd6e98
	private NetworkErrorDisplayer _AlertNetworkErrorWithNetCheck(String errorMsg, Action callback) { }
	// RVA: 0x27bf16c VA: 0x7594dd716c
	private Void _AlertNetworkErrorWithNetCheckIgnoreRet(String errorMsg, Action callback) { }
	// RVA: 0x27bf1f8 VA: 0x7594dd71f8
	public IEnumerator AlertNetworkErrorWithNetCheckRoutine(String errorMsg, Action callback) { }
	// RVA: 0x27bdcbc VA: 0x7594dd5cbc
	private Void _ShowNetCheckPanel() { }
	// RVA: 0x27bf308 VA: 0x7594dd7308
	private static List`1 _CreateWorkflowNodes() { }
	// RVA: 0x27bfc74 VA: 0x7594dd7c74
	public HotUpdateViewProp GetViewProp() { }
	// RVA: 0x27bfcdc VA: 0x7594dd7cdc
	public HotUpdateViewController GetViewCtrl() { }
	// RVA: 0x27bfd44 VA: 0x7594dd7d44
	public HotUpdatePreMainTicker GetPreMainTicker() { }
	// RVA: 0x27bfdac VA: 0x7594dd7dac
	public Void StopCoroutineNested(IEnumerator routine) { }
	// RVA: 0x27bfe30 VA: 0x7594dd7e30
	private Void _StartWorkflow() { }
	// RVA: 0x27bff40 VA: 0x7594dd7f40
	public Void .ctor() { }
	// RVA: 0x27c00b8 VA: 0x7594dd80b8
	private Coroutine Torappu.UI.HotUpdate.HotUpdateWorkflow.IContext.StartCoroutine(IEnumerator routine) { }
	// RVA: 0x27c013c VA: 0x7594dd813c
	private Void <OnClearCacheBtnClick>b__37_0() { }
}
```