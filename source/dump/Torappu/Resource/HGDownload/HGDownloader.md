# HGDownloader

**Namespace:** `Torappu.Resource.HGDownload`


## Fields

- `Adapter m_adapter`

- `HGConfig m_config`

- `TaskMgr m_taskMgr`

- `Boolean m_isIniting`

- `Int32 m_lastInitCode`


## Methods

- `Boolean Init(HGConfig)`

- `Adapter GetAdapter()`

- `TaskHandler StartTask(String, IList`1, Boolean)`

- `Void CleanWorkspace()`

- `Void CancelCurrentTask()`

- `Boolean ManualCheckIfTaskFinished()`

- `WorkState GetWorkState()`

- `HGDownloadTaskInfo AchieveTaskInfo()`

- `Int64 GetCachedTaskStatus()`

- `Boolean CheckIfInited()`

- `Int64 AchieveEstimatedDownloadSizeE(String, IList`1, out)`

- `Void ResumeCurrentTask()`

- `Void EnableCurrentMobileData()`

- `Void Tick()`

- `Boolean _TickToCheckIfInited()`

- `Void _OnSDKInited()`

- `Boolean _CheckIfInited(Boolean)`

- `Boolean _BreakIfNotInited(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Resource.HGDownload
public class HGDownloader
{
	private static HGDownloader m_inst; // 0x0
	private Adapter m_adapter; // 0x10
	private HGConfig m_config; // 0x18
	private TaskMgr m_taskMgr; // 0x20
	private Boolean m_isIniting; // 0x28
	private Int32 m_lastInitCode; // 0x2c

	public static HGDownloader instance { get; }

	// RVA: 0x3750758 VA: 0x7595d68758
	private Void .ctor() { }
	// RVA: 0x3750768 VA: 0x7595d68768
	public static HGDownloader get_instance() { }
	// RVA: 0x VA: 0x0
	public Boolean Init(HGConfig config) { }
	// RVA: 0x3750800 VA: 0x7595d68800
	public Adapter GetAdapter() { }
	// RVA: 0x3750808 VA: 0x7595d68808
	public TaskHandler StartTask(String versionId, IList`1 files, Boolean useMobileData) { }
	// RVA: 0x3750a0c VA: 0x7595d68a0c
	public Void CleanWorkspace() { }
	// RVA: 0x3750a7c VA: 0x7595d68a7c
	public Void CancelCurrentTask() { }
	// RVA: 0x3750bcc VA: 0x7595d68bcc
	public Boolean ManualCheckIfTaskFinished() { }
	// RVA: 0x3750cb4 VA: 0x7595d68cb4
	public WorkState GetWorkState() { }
	// RVA: 0x3750d00 VA: 0x7595d68d00
	public HGDownloadTaskInfo AchieveTaskInfo() { }
	// RVA: 0x3750dc4 VA: 0x7595d68dc4
	public Int64 GetCachedTaskStatus() { }
	// RVA: 0x3750ddc VA: 0x7595d68ddc
	public Boolean CheckIfInited() { }
	// RVA: 0x3750e0c VA: 0x7595d68e0c
	public Int64 AchieveEstimatedDownloadSizeE(String versionId, IList`1 files, out Int32 errorCode) { }
	// RVA: 0x3750eec VA: 0x7595d68eec
	public Void ResumeCurrentTask() { }
	// RVA: 0x3750f94 VA: 0x7595d68f94
	public Void EnableCurrentMobileData() { }
	// RVA: 0x3751080 VA: 0x7595d69080
	public Void Tick() { }
	// RVA: 0x3751830 VA: 0x7595d69830
	private static Void _RaiseSDKInternalError(Int64 errorCode) { }
	// RVA: 0x3751280 VA: 0x7595d69280
	private Boolean _TickToCheckIfInited() { }
	// RVA: 0x375186c VA: 0x7595d6986c
	private static Int32 _InvokeSDKInit(Adapter adapter, HGConfig config) { }
	// RVA: 0x37518b0 VA: 0x7595d698b0
	private Void _OnSDKInited() { }
	// RVA: 0x3750a40 VA: 0x7595d68a40
	private Boolean _CheckIfInited(Boolean allowIniting) { }
	// RVA: 0x3750954 VA: 0x7595d68954
	private Boolean _BreakIfNotInited(Boolean allowIniting) { }
	// RVA: 0x37518e8 VA: 0x7595d698e8
	private static Int32 _CancelTask(Int64 taskId, Adapter adapter) { }
	// RVA: 0x37518f0 VA: 0x7595d698f0
	private static Int32 _ResumeTask(Int64 taskId, Adapter adapter) { }
	// RVA: 0x37518f8 VA: 0x7595d698f8
	private static Int32 _EnableMobileData(Int64 taskId, Adapter adapter) { }
	// RVA: 0x3751900 VA: 0x7595d69900
	private static Int64 _StartDownload(DownloadTask task, Adapter adapter) { }
	// RVA: 0x3751b38 VA: 0x7595d69b38
	private static Int32 _Finish(Int64 taskId, Adapter adapter) { }
	// RVA: 0x37514dc VA: 0x7595d694dc
	private static Boolean _IsSucCode(Int64 code) { }
	// RVA: 0x3751b40 VA: 0x7595d69b40
	private static HGRetCodeType _CheckCodeType(Int64 code) { }
	// RVA: 0x3751b74 VA: 0x7595d69b74
	private static Boolean _IsTaskInvalidCode(Int64 code) { }
	// RVA: 0x3751b80 VA: 0x7595d69b80
	private static Boolean _IsTaskDuplicatedCode(Int64 code) { }
	// RVA: 0x3750990 VA: 0x7595d68990
	private static Boolean _CreateDirectoryIfNotExists(String folderPath) { }
}
```