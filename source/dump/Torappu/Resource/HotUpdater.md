# HotUpdater

**Namespace:** `Torappu.Resource`


## Fields

- `Options m_options`

- `UpdateState m_updateState`

- `PersistentResRecover m_persistResRecover`

- `HotUpdateInfo m_newUpdateInfoCache`

- `Int32 m_countOfTypedResInUpdateList`

- `FileDownloader m_updateInfoDownloader`

- `DownloadInterface m_downloadInterface`

- `Single m_startTime`

- `UIHotUpdatePreferencePanel _hotupdatePrefPanel`

- `Coroutine m_initSDKCoroutine`

- `NetUsagePolicy m_nullableNetUsagePolicy`


## Properties

- `UpdateState updateState`


## Methods

- `Void Start()`

- `Void OnDestroy()`

- `Void InterruptDownload(Action`1)`

- `UpdateState get_updateState()`

- `Void set_updateState(UpdateState)`

- `Void StartHotUpdate(Options)`

- `IEnumerator _InitSDKCoroutine(Action)`

- `Void UpdateTime(Single)`

- `Boolean CanInterrupt()`

- `Void _OnUpdateInfoDownloaded(Options, Boolean)`

- `Void _OnNewUpdateInfoAchieved(HotUpdateInfo)`

- `Void _OnExtraResPrefSelected(HotUpdateInfo, CalcResult, Boolean)`

- `Void _TryShowVoiceResPrefDialog(CalcResult, Action)`

- `DownloadInterface _EnsureDownloadInterface()`

- `Void _OnPreferenceStepFinished(HotUpdateInfo, CalcResult, ResPrefContext)`

- `Void _OnDownloadAllowed(HotUpdateInfo, List`1)`

- `Void _OnABDownloadSizeChange(Int64, Int64)`

- `Void _OnPausedByMobileDataPolicy(Int64)`

- `Void _OnABDownloadError(DownloadError)`

- `Void _OnResourceDownloadFinish()`

- `Void _OnConfirmError()`

- `Void _OnTrivialError()`

- `IEnumerator _WaitForResourceUpdateStop(Action`1)`

- `Void _StopBackgroundTasks()`

- `IEnumerator _FinishResourceUpdate()`

- `Void _CompleteCurrentHotUpdate(Boolean)`

- `Void _OverwriteHotUpdateInfoWithCache()`

- `Void _DeleteLocalPersistentResInfoNoThrow()`

- `Void _SetUnzipProgress(Single)`

- `Void _QuitGame()`

- `Boolean _CheckIfToRecoverPersistResInfo()`

- `Void _RecoverPersistResInfoImpl(Action)`

- `Void _FetchVersion()`

- `Void _UpdateWithVersion(String, HotUpdateInfo)`

- `Boolean _PrepareResCacheDirectory(String, out)`

- `Void _UpdateHotUpdateInfo(String, Action`1)`

- `Void _AlertNetworkError(String, Action)`

- `NetUsagePolicy _EnsureNetUsagePolicy()`

- `Void <StartHotUpdate>b__39_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Resource
public class HotUpdater : MonoBehaviour, ITimeWatcher, IHotfixable
{
	private const Single PERCENT_THRESHOLD_TO_DOWNLOAD_LARGE_PACK; // 0x0
	public const Int64 MIN_BYTES_SIZE_TO_NOTIFY_IF_NOT_WIFI; // 0x0
	private const Single MIN_DELTA_OF_TRIVIAL_ERROR; // 0x0
	private Options m_options; // 0x18
	private UpdateState m_updateState; // 0x60
	private PersistentResRecover m_persistResRecover; // 0x68
	private Queue`1 m_updateInfoQueue; // 0x70
	private HotUpdateInfo m_newUpdateInfoCache; // 0x78
	private Action`1 m_onFinishUpdateHotInfo; // 0x80
	private List`1 m_updateResList; // 0x88
	private List`1 m_removeResList; // 0x90
	private Int32 m_countOfTypedResInUpdateList; // 0x98
	private FileDownloader m_updateInfoDownloader; // 0xa0
	private DownloadInterface m_downloadInterface; // 0xa8
	private Single m_startTime; // 0xb0
	private UIHotUpdatePreferencePanel _hotupdatePrefPanel; // 0xb8
	private static VersionInfo <onlineVersionInfo>k__BackingField; // 0x0
	private Coroutine m_initSDKCoroutine; // 0xc0
	private static String s_updateInfoPath; // 0x10
	private static String s_updateInfoPathInCacheDir; // 0x18
	private NetUsagePolicy m_nullableNetUsagePolicy; // 0xc8
	private static DelegateBridge __Hotfix0_get_ENABLED; // 0x20
	private static DelegateBridge __Hotfix0_Start; // 0x28
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x30
	private static DelegateBridge __Hotfix0_GenerateZipNameFromAssetOrBundleName; // 0x38
	private static DelegateBridge __Hotfix0_DeletePersistentRes; // 0x40
	private static DelegateBridge __Hotfix0_MarkUpdateResInvalid; // 0x48
	private static DelegateBridge __Hotfix0_InterruptDownload; // 0x50
	private static DelegateBridge __Hotfix0_LoadLocalUpdateInfo; // 0x58
	private static DelegateBridge __Hotfix0_MarkUpdateResInvalidNoThrow; // 0x60
	private static DelegateBridge __Hotfix0_get_onlineVersionInfo; // 0x68
	private static DelegateBridge __Hotfix0_set_onlineVersionInfo; // 0x70
	private static DelegateBridge __Hotfix0_ConfirmOnlineVersionInfo; // 0x78
	private static DelegateBridge __Hotfix0_get_updateState; // 0x80
	private static DelegateBridge __Hotfix0_set_updateState; // 0x88
	private static DelegateBridge __Hotfix0_StartHotUpdate; // 0x90
	private static DelegateBridge __Hotfix0__InitSDKCoroutine; // 0x98
	private static DelegateBridge __Hotfix0_UpdateTime; // 0xa0
	private static DelegateBridge __Hotfix0_CanInterrupt; // 0xa8
	private static DelegateBridge __Hotfix0__OnUpdateInfoDownloaded; // 0xb0
	private static DelegateBridge __Hotfix0__OnNewUpdateInfoAchieved; // 0xb8
	private static DelegateBridge __Hotfix0__OnExtraResPrefSelected; // 0xc0
	private static DelegateBridge __Hotfix0__CheckIfShowVoiceResPrefDialog; // 0xc8
	private static DelegateBridge __Hotfix0__TryShowVoiceResPrefDialog; // 0xd0
	private static DelegateBridge __Hotfix0__EnsureDownloadInterface; // 0xd8
	private static DelegateBridge __Hotfix0__OnPreferenceStepFinished; // 0xe0
	private static DelegateBridge __Hotfix0__FillUpdateListWithCalcResult; // 0xe8
	private static DelegateBridge __Hotfix0__OnDownloadAllowed; // 0xf0
	private static DelegateBridge __Hotfix0__OnABDownloadSizeChange; // 0xf8
	private static DelegateBridge __Hotfix0__OnPausedByMobileDataPolicy; // 0x100
	private static DelegateBridge __Hotfix0__OnABDownloadError; // 0x108
	private static DelegateBridge __Hotfix0__OnResourceDownloadFinish; // 0x110
	private static DelegateBridge __Hotfix0__OnConfirmError; // 0x118
	private static DelegateBridge __Hotfix0__OnTrivialError; // 0x120
	private static DelegateBridge __Hotfix0_GenerateVersionFileUrl; // 0x128
	private static DelegateBridge __Hotfix0__GenAssetsFolderUrl; // 0x130
	private static DelegateBridge __Hotfix0__GenUpdateInfoUrl; // 0x138
	private static DelegateBridge __Hotfix0_GetUpdateInfoPath; // 0x140
	private static DelegateBridge __Hotfix0__GetUpdateInfoCachePath; // 0x148
	private static DelegateBridge __Hotfix0__GenResZipUrl; // 0x150
	private static DelegateBridge __Hotfix0__LoadUpdateInfoFromFile; // 0x158
	private static DelegateBridge __Hotfix0__WaitForResourceUpdateStop; // 0x160
	private static DelegateBridge __Hotfix0__StopBackgroundTasks; // 0x168
	private static DelegateBridge __Hotfix0__FinishResourceUpdate; // 0x170
	private static DelegateBridge __Hotfix0__CompleteCurrentHotUpdate; // 0x178
	private static DelegateBridge __Hotfix0__OverwriteHotUpdateInfoWithCache; // 0x180
	private static DelegateBridge __Hotfix0__DeleteLocalPersistentResInfoNoThrow; // 0x188
	private static DelegateBridge __Hotfix0__DeleteUnusedFiles; // 0x190
	private static DelegateBridge __Hotfix0__CalcUpdateResParams; // 0x198
	private static DelegateBridge __Hotfix0__ResCategoryMatched; // 0x1a0
	private static DelegateBridge __Hotfix0__CheckIfAssetDirty; // 0x1a8
	private static DelegateBridge __Hotfix0__DoLargePackExtension; // 0x1b0
	private static DelegateBridge __Hotfix0__TryUseLargePackForList; // 0x1b8
	private static DelegateBridge __Hotfix0__CheckIfShowPreferencePanel; // 0x1c0
	private static DelegateBridge __Hotfix0__CalcResListDownloadSize; // 0x1c8
	private static DelegateBridge __Hotfix0__CalcAndStoreNewPersistentResInfoToCacheFolder; // 0x1d0
	private static DelegateBridge __Hotfix0__SetUnzipProgress; // 0x1d8
	private static DelegateBridge __Hotfix0__QuitGame; // 0x1e0
	private static DelegateBridge __Hotfix0__CheckIfToRecoverPersistResInfo; // 0x1e8
	private static DelegateBridge __Hotfix0__RecoverPersistResInfoImpl; // 0x1f0
	private static DelegateBridge __Hotfix0__FetchVersion; // 0x1f8
	private static DelegateBridge __Hotfix0__UpdateWithVersion; // 0x200
	private static DelegateBridge __Hotfix0__PrepareResCacheDirectory; // 0x208
	private static DelegateBridge __Hotfix0__UpdateHotUpdateInfo; // 0x210
	private static DelegateBridge __Hotfix0__AlertNetworkError; // 0x218
	private static DelegateBridge __Hotfix0_LoadLocalResStatus; // 0x220
	private static DelegateBridge __Hotfix0__EnsureNetUsagePolicy; // 0x228
	private static DelegateBridge _c__Hotfix0_ctor; // 0x230

	public static Boolean ENABLED { get; }
	public static VersionInfo onlineVersionInfo { get; set; }
	public UpdateState updateState { get; set; }

	// RVA: 0x37305c0 VA: 0x7595d485c0
	public static Boolean get_ENABLED() { }
	// RVA: 0x373082c VA: 0x7595d4882c
	private Void Start() { }
	// RVA: 0x37308b4 VA: 0x7595d488b4
	private Void OnDestroy() { }
	// RVA: 0x3730a18 VA: 0x7595d48a18
	public static String GenerateZipNameFromAssetOrBundleName(String inputName) { }
	// RVA: 0x3730b34 VA: 0x7595d48b34
	public static Void DeletePersistentRes() { }
	// RVA: 0x3730c0c VA: 0x7595d48c0c
	public static Void MarkUpdateResInvalid() { }
	// RVA: 0x3730d70 VA: 0x7595d48d70
	public Void InterruptDownload(Action`1 cb) { }
	// RVA: 0x3731018 VA: 0x7595d49018
	public static HotUpdateInfo LoadLocalUpdateInfo() { }
	// RVA: 0x3731284 VA: 0x7595d49284
	public static Void MarkUpdateResInvalidNoThrow() { }
	// RVA: 0x3731358 VA: 0x7595d49358
	public static VersionInfo get_onlineVersionInfo() { }
	// RVA: 0x37313b4 VA: 0x7595d493b4
	private static Void set_onlineVersionInfo(VersionInfo value) { }
	// RVA: 0x373143c VA: 0x7595d4943c
	public static Void ConfirmOnlineVersionInfo(VersionInfo info) { }
	// RVA: 0x37314bc VA: 0x7595d494bc
	public UpdateState get_updateState() { }
	// RVA: 0x3731524 VA: 0x7595d49524
	private Void set_updateState(UpdateState value) { }
	// RVA: 0x37315cc VA: 0x7595d495cc
	public Void StartHotUpdate(Options options) { }
	// RVA: 0x3731744 VA: 0x7595d49744
	private IEnumerator _InitSDKCoroutine(Action nextStep) { }
	// RVA: 0x3731814 VA: 0x7595d49814
	public Void UpdateTime(Single timeDetla) { }
	// RVA: 0x3730eac VA: 0x7595d48eac
	public Boolean CanInterrupt() { }
	// RVA: 0x3731984 VA: 0x7595d49984
	private Void _OnUpdateInfoDownloaded(Options options, Boolean isSuc) { }
	// RVA: 0x3731c04 VA: 0x7595d49c04
	private Void _OnNewUpdateInfoAchieved(HotUpdateInfo updateInfo) { }
	// RVA: 0x3732e30 VA: 0x7595d4ae30
	private Void _OnExtraResPrefSelected(HotUpdateInfo updateInfo, CalcResult calcResult, Boolean isFull) { }
	// RVA: 0x3733138 VA: 0x7595d4b138
	private static Boolean _CheckIfShowVoiceResPrefDialog(CalcResult calcResult) { }
	// RVA: 0x3732f88 VA: 0x7595d4af88
	private Void _TryShowVoiceResPrefDialog(CalcResult calcResult, Action nextStep) { }
	// RVA: 0x3733208 VA: 0x7595d4b208
	private DownloadInterface _EnsureDownloadInterface() { }
	// RVA: 0x37334e0 VA: 0x7595d4b4e0
	private Void _OnPreferenceStepFinished(HotUpdateInfo updateInfo, CalcResult calcResult, ResPrefContext prefContext) { }
	// RVA: 0x3733f78 VA: 0x7595d4bf78
	private static Void _FillUpdateListWithCalcResult(CalcResult calcResult, ResPrefContext prefContext, out List`1 updateResList, out List`1 removeResList) { }
	// RVA: 0x373506c VA: 0x7595d4d06c
	private Void _OnDownloadAllowed(HotUpdateInfo updateInfo, List`1 downloadResList) { }
	// RVA: 0x3735344 VA: 0x7595d4d344
	private Void _OnABDownloadSizeChange(Int64 curSize, Int64 totalSize) { }
	// RVA: 0x37353f0 VA: 0x7595d4d3f0
	private Void _OnPausedByMobileDataPolicy(Int64 remainDownloadSize) { }
	// RVA: 0x3735558 VA: 0x7595d4d558
	private Void _OnABDownloadError(DownloadError errorInfo) { }
	// RVA: 0x37357d8 VA: 0x7595d4d7d8
	private Void _OnResourceDownloadFinish() { }
	// RVA: 0x373591c VA: 0x7595d4d91c
	private Void _OnConfirmError() { }
	// RVA: 0x3735764 VA: 0x7595d4d764
	private Void _OnTrivialError() { }
	// RVA: 0x3735990 VA: 0x7595d4d990
	public static String GenerateVersionFileUrl() { }
	// RVA: 0x3735aa0 VA: 0x7595d4daa0
	private static String _GenAssetsFolderUrl(String versionId, String lastUrlPart) { }
	// RVA: 0x3735ce8 VA: 0x7595d4dce8
	private static String _GenUpdateInfoUrl(String versionId) { }
	// RVA: 0x3730c94 VA: 0x7595d48c94
	public static String GetUpdateInfoPath() { }
	// RVA: 0x3734784 VA: 0x7595d4c784
	private static String _GetUpdateInfoCachePath() { }
	// RVA: 0x3735d68 VA: 0x7595d4dd68
	private static String _GenResZipUrl(String resName, String versionId) { }
	// RVA: 0x373107c VA: 0x7595d4907c
	private static HotUpdateInfo _LoadUpdateInfoFromFile(String path, Source source) { }
	// RVA: 0x3730f48 VA: 0x7595d48f48
	private IEnumerator _WaitForResourceUpdateStop(Action`1 cb) { }
	// RVA: 0x3730960 VA: 0x7595d48960
	private Void _StopBackgroundTasks() { }
	// RVA: 0x3735870 VA: 0x7595d4d870
	private IEnumerator _FinishResourceUpdate() { }
	// RVA: 0x37342bc VA: 0x7595d4c2bc
	private Void _CompleteCurrentHotUpdate(Boolean hasNothingChanged) { }
	// RVA: 0x3735de8 VA: 0x7595d4dde8
	private Void _OverwriteHotUpdateInfoWithCache() { }
	// RVA: 0x3735e94 VA: 0x7595d4de94
	private Void _DeleteLocalPersistentResInfoNoThrow() { }
	// RVA: 0x3735fb4 VA: 0x7595d4dfb4
	private static Void _DeleteUnusedFiles(PersistentResInfo persistentResInfo, List`1 removeResList) { }
	// RVA: 0x3731fec VA: 0x7595d49fec
	private static CalcResult _CalcUpdateResParams(HotUpdateInfo newUpdateInfo, PersistentResInfo persistentResInfo, DownloadPartEnum downloadPart) { }
	// RVA: 0x373628c VA: 0x7595d4e28c
	private static Boolean _ResCategoryMatched(ResLifetimeCategory category, DownloadPartEnum downloadPart) { }
	// RVA: 0x3736324 VA: 0x7595d4e324
	private static Boolean _CheckIfAssetDirty(ABInfo abInfo, Dictionary`2 oldHashMap, Dictionary`2 oldMD5Map, Dictionary`2 oldTypeMap) { }
	// RVA: 0x37364cc VA: 0x7595d4e4cc
	private static Void _DoLargePackExtension(HotUpdateInfo hotupdateInfo, CalcResult calcRet) { }
	// RVA: 0x3736b50 VA: 0x7595d4eb50
	private static Void _TryUseLargePackForList(Dictionary`2 packMap, List`1 updateList, Dictionary`2 packsToDownload, out Int64 downloadSize) { }
	// RVA: 0x3732d2c VA: 0x7595d4ad2c
	private static Boolean _CheckIfShowPreferencePanel(CalcResult calcRet) { }
	// RVA: 0x3736994 VA: 0x7595d4e994
	private static Int64 _CalcResListDownloadSize(IList`1 updateResList) { }
	// RVA: 0x3734860 VA: 0x7595d4c860
	private static Boolean _CalcAndStoreNewPersistentResInfoToCacheFolder(HotUpdateInfo hotUpdateInfo, PersistentResInfo oldPersistentInfo, List`1 updateResList, List`1 removeResList, Dictionary`2 updatedABInfos) { }
	// RVA: 0x3737088 VA: 0x7595d4f088
	private Void _SetUnzipProgress(Single progress) { }
	// RVA: 0x3737128 VA: 0x7595d4f128
	private Void _QuitGame() { }
	// RVA: 0x37371b4 VA: 0x7595d4f1b4
	private Boolean _CheckIfToRecoverPersistResInfo() { }
	// RVA: 0x3737224 VA: 0x7595d4f224
	private Void _RecoverPersistResInfoImpl(Action nextStep) { }
	// RVA: 0x3737348 VA: 0x7595d4f348
	private Void _FetchVersion() { }
	// RVA: 0x37374c0 VA: 0x7595d4f4c0
	private Void _UpdateWithVersion(String newVersion, HotUpdateInfo localUpdateInfo) { }
	// RVA: 0x3734548 VA: 0x7595d4c548
	private Boolean _PrepareResCacheDirectory(String newVersion, out HotUpdateInfo validInfoInResCache) { }
	// RVA: 0x37375fc VA: 0x7595d4f5fc
	private Void _UpdateHotUpdateInfo(String versionId, Action`1 callback) { }
	// RVA: 0x3731b4c VA: 0x7595d49b4c
	private Void _AlertNetworkError(String errorInfo, Action nextStep) { }
	// RVA: 0x37379a4 VA: 0x7595d4f9a4
	public static LocalResStatus LoadLocalResStatus(PersistentResInfo persistResInfo) { }
	// RVA: 0x3734f60 VA: 0x7595d4cf60
	private NetUsagePolicy _EnsureNetUsagePolicy() { }
	// RVA: 0x3737a7c VA: 0x7595d4fa7c
	public Void .ctor() { }
	// RVA: 0x3737c00 VA: 0x7595d4fc00
	private Void <StartHotUpdate>b__39_0() { }
}
```