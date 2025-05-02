# TimeCheatingDetector

**Namespace:** `CodeStage.AntiCheat.Detectors`


## Fields

- `Action CheckPassed`

- `Single interval`

- `Int32 threshold`

- `String timeServer`

- `Boolean <IsCheckingForCheat>k__BackingField`

- `ErrorKind <LastError>k__BackingField`

- `TimeCheatingDetectorResult <LastResult>k__BackingField`

- `Socket asyncSocket`

- `IPEndPoint targetEndpoint`

- `SocketAsyncEventArgs connectArgs`

- `SocketAsyncEventArgs sendArgs`

- `SocketAsyncEventArgs receiveArgs`

- `Single timeElapsed`

- `Double lastOnlineTime`

- `Boolean gettingOnlineTimeAsync`

- `ErrorKind asyncError`


## Properties

- `Boolean IsCheckingForCheat`

- `ErrorKind LastError`

- `TimeCheatingDetectorResult LastResult`


## Methods

- `Void add_Error(Action`1)`

- `Void remove_Error(Action`1)`

- `Void add_CheckPassed(Action)`

- `Void remove_CheckPassed(Action)`

- `Boolean get_IsCheckingForCheat()`

- `Void set_IsCheckingForCheat(Boolean)`

- `ErrorKind get_LastError()`

- `Void set_LastError(ErrorKind)`

- `TimeCheatingDetectorResult get_LastResult()`

- `Void set_LastResult(TimeCheatingDetectorResult)`

- `Void Awake()`

- `Void OnLevelWasLoadedNew(Scene, LoadSceneMode)`

- `Void OnLevelLoadedCallback()`

- `Void OnApplicationPause(Boolean)`

- `Void Update()`

- `Boolean ForceCheck()`

- `IEnumerator ForceCheckEnumerator()`

- `Void StartDetectionInternal(Single, Action, Action, Action`1)`

- `IEnumerator CheckForCheat()`

- `IEnumerator GetOnlineTimeInternal()`

- `Void OnSocketConnectedOrSent(Object, SocketAsyncEventArgs)`

- `Void OnSocketReceive(Object, SocketAsyncEventArgs)`

- `Void CloseSocket()`

- `Void HandleSocketException(Exception)`

- `Double GetLocalTime()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : CodeStage.AntiCheat.Detectors
public class TimeCheatingDetector : ActDetectorBase
{
	internal const String ComponentName; // 0x0
	private const String LogPrefix; // 0x0
	private static Int32 instancesInScene; // 0x0
	private const Int32 NtpDataBufferLength; // 0x0
	private Action`1 Error; // 0x38
	private Action CheckPassed; // 0x40
	public Single interval; // 0x48
	public Int32 threshold; // 0x4c
	public String timeServer; // 0x50
	private Boolean <IsCheckingForCheat>k__BackingField; // 0x58
	private ErrorKind <LastError>k__BackingField; // 0x5c
	private TimeCheatingDetectorResult <LastResult>k__BackingField; // 0x60
	private readonly DateTime date1900; // 0x68
	private readonly WaitForEndOfFrame cachedEndOfFrame; // 0x70
	private Socket asyncSocket; // 0x78
	private Byte[] ntpData; // 0x80
	private Byte[] targetIP; // 0x88
	private IPEndPoint targetEndpoint; // 0x90
	private SocketAsyncEventArgs connectArgs; // 0x98
	private SocketAsyncEventArgs sendArgs; // 0xa0
	private SocketAsyncEventArgs receiveArgs; // 0xa8
	private Single timeElapsed; // 0xb0
	private Double lastOnlineTime; // 0xb8
	private Boolean gettingOnlineTimeAsync; // 0xc0
	private ErrorKind asyncError; // 0xc4
	private static TimeCheatingDetector <Instance>k__BackingField; // 0x8

	public Boolean IsCheckingForCheat { get; set; }
	public ErrorKind LastError { get; set; }
	public TimeCheatingDetectorResult LastResult { get; set; }
	public static TimeCheatingDetector Instance { get; set; }
	private static TimeCheatingDetector GetOrCreateInstance { get; }

	// RVA: 0x66b368c VA: 0x7598ccb68c
	public Void add_Error(Action`1 value) { }
	// RVA: 0x66b373c VA: 0x7598ccb73c
	public Void remove_Error(Action`1 value) { }
	// RVA: 0x66b37ec VA: 0x7598ccb7ec
	public Void add_CheckPassed(Action value) { }
	// RVA: 0x66b3888 VA: 0x7598ccb888
	public Void remove_CheckPassed(Action value) { }
	// RVA: 0x66b3924 VA: 0x7598ccb924
	public Boolean get_IsCheckingForCheat() { }
	// RVA: 0x66b392c VA: 0x7598ccb92c
	private Void set_IsCheckingForCheat(Boolean value) { }
	// RVA: 0x66b3938 VA: 0x7598ccb938
	public ErrorKind get_LastError() { }
	// RVA: 0x66b3940 VA: 0x7598ccb940
	private Void set_LastError(ErrorKind value) { }
	// RVA: 0x66b3948 VA: 0x7598ccb948
	public TimeCheatingDetectorResult get_LastResult() { }
	// RVA: 0x66b3950 VA: 0x7598ccb950
	private Void set_LastResult(TimeCheatingDetectorResult value) { }
	// RVA: 0x66b3958 VA: 0x7598ccb958
	public static TimeCheatingDetector get_Instance() { }
	// RVA: 0x66b39a0 VA: 0x7598ccb9a0
	private static Void set_Instance(TimeCheatingDetector value) { }
	// RVA: 0x66b39f0 VA: 0x7598ccb9f0
	private static TimeCheatingDetector get_GetOrCreateInstance() { }
	// RVA: 0x66b3bc0 VA: 0x7598ccbbc0
	public static Void StartDetection(Action detectionCallback, Int32 interval) { }
	// RVA: 0x66b3c18 VA: 0x7598ccbc18
	public static Void StartDetection(Action detectionCallback, Action`1 errorCallback, Int32 interval) { }
	// RVA: 0x66b3c24 VA: 0x7598ccbc24
	public static TimeCheatingDetector AddToSceneOrGetExisting() { }
	// RVA: 0x66b3c28 VA: 0x7598ccbc28
	public static Void StartDetection(Action detectionCallback, Action`1 errorCallback, Action checkPassedCallback) { }
	// RVA: 0x66b3bd0 VA: 0x7598ccbbd0
	public static Void StartDetection(Single intervalMinutes, Action detectionCallback, Action`1 errorCallback, Action checkPassedCallback) { }
	// RVA: 0x66b3f44 VA: 0x7598ccbf44
	public static Void StopDetection() { }
	// RVA: 0x66b401c VA: 0x7598ccc01c
	public static Void SetErrorCallback(Action`1 errorCallback) { }
	// RVA: 0x66b4020 VA: 0x7598ccc020
	public static Void Dispose() { }
	// RVA: 0x66b40f8 VA: 0x7598ccc0f8
	private Void Awake() { }
	// RVA: 0x66b4254 VA: 0x7598ccc254
	protected override Void OnDestroy() { }
	// RVA: 0x66b42b0 VA: 0x7598ccc2b0
	private Void OnLevelWasLoadedNew(Scene scene, LoadSceneMode mode) { }
	// RVA: 0x66b42b4 VA: 0x7598ccc2b4
	private Void OnLevelLoadedCallback() { }
	// RVA: 0x66b439c VA: 0x7598ccc39c
	private Void OnApplicationPause(Boolean pauseStatus) { }
	// RVA: 0x66b43c0 VA: 0x7598ccc3c0
	private Void Update() { }
	// RVA: 0x66b44b8 VA: 0x7598ccc4b8
	public Boolean ForceCheck() { }
	// RVA: 0x66b45d0 VA: 0x7598ccc5d0
	public IEnumerator ForceCheckEnumerator() { }
	// RVA: 0x66b466c VA: 0x7598ccc66c
	public Task`1 ForceCheckTask() { }
	// RVA: 0x66b3d8c VA: 0x7598ccbd8c
	private Void StartDetectionInternal(Single checkInterval, Action detectionCallback, Action checkPassedCallback, Action`1 errorCallback) { }
	// RVA: 0x66b4778 VA: 0x7598ccc778
	protected override Void StartDetectionAutomatically() { }
	// RVA: 0x66b478c VA: 0x7598ccc78c
	protected override Boolean DetectorHasCallbacks() { }
	// RVA: 0x66b47bc VA: 0x7598ccc7bc
	protected override Void PauseDetector() { }
	// RVA: 0x66b47d0 VA: 0x7598ccc7d0
	protected override Void StopDetectionInternal() { }
	// RVA: 0x66b486c VA: 0x7598ccc86c
	protected override Void DisposeInternal() { }
	// RVA: 0x66b4444 VA: 0x7598ccc444
	private IEnumerator CheckForCheat() { }
	// RVA: 0x66b4964 VA: 0x7598ccc964
	private IEnumerator GetOnlineTimeInternal() { }
	// RVA: 0x66b4a00 VA: 0x7598ccca00
	private Void OnSocketConnectedOrSent(Object sender, SocketAsyncEventArgs e) { }
	// RVA: 0x66b4c88 VA: 0x7598cccc88
	private Void OnSocketReceive(Object sender, SocketAsyncEventArgs e) { }
	// RVA: 0x66b4814 VA: 0x7598ccc814
	private Void CloseSocket() { }
	// RVA: 0x66b4f34 VA: 0x7598cccf34
	private Void HandleSocketException(Exception exception) { }
	// RVA: 0x66b5084 VA: 0x7598ccd084
	private Double GetLocalTime() { }
	// RVA: 0x66b5134 VA: 0x7598ccd134
	public static Double GetOnlineTime(String server) { }
	// RVA: 0x66b54c4 VA: 0x7598ccd4c4
	public Void .ctor() { }
}
```