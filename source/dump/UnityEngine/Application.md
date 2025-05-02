# Application

**Namespace:** `UnityEngine`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class Application
{
	private static LowMemoryCallback lowMemory; // 0x0
	private static LogCallback s_LogCallbackHandler; // 0x8
	private static LogCallback s_LogCallbackHandlerThreaded; // 0x10
	private static Action`1 focusChanged; // 0x18
	private static Action`1 deepLinkActivated; // 0x20
	private static Func`1 wantsToQuit; // 0x28
	private static Action quitting; // 0x30
	private static Action unloading; // 0x38
	private static LogCallback s_RegisterLogCallbackDeprecated; // 0x40

	public static Boolean isPlaying { get; }
	public static Boolean isFocused { get; }
	public static Boolean isBatchMode { get; }
	public static String dataPath { get; }
	public static String streamingAssetsPath { get; }
	public static String persistentDataPath { get; }
	public static String unityVersion { get; }
	public static String version { get; }
	public static Int32 targetFrameRate { get; set; }
	public static RuntimePlatform platform { get; }
	public static Boolean isMobilePlatform { get; }
	public static NetworkReachability internetReachability { get; }
	public static Boolean isEditor { get; }

	// RVA: 0x6850a58 VA: 0x7598e68a58
	public static Void Quit(Int32 exitCode) { }
	// RVA: 0x6850a94 VA: 0x7598e68a94
	public static Void Quit() { }
	// RVA: 0x6850ac4 VA: 0x7598e68ac4
	public static Boolean get_isPlaying() { }
	// RVA: 0x6850aec VA: 0x7598e68aec
	public static Boolean get_isFocused() { }
	// RVA: 0x6850b14 VA: 0x7598e68b14
	public static Boolean get_isBatchMode() { }
	// RVA: 0x6850b3c VA: 0x7598e68b3c
	public static String get_dataPath() { }
	// RVA: 0x6850b64 VA: 0x7598e68b64
	public static String get_streamingAssetsPath() { }
	// RVA: 0x6850b8c VA: 0x7598e68b8c
	public static String get_persistentDataPath() { }
	// RVA: 0x6850bb4 VA: 0x7598e68bb4
	public static String get_unityVersion() { }
	// RVA: 0x6850bdc VA: 0x7598e68bdc
	public static String get_version() { }
	// RVA: 0x6850c04 VA: 0x7598e68c04
	public static Void OpenURL(String url) { }
	// RVA: 0x6850c40 VA: 0x7598e68c40
	public static Int32 get_targetFrameRate() { }
	// RVA: 0x6850c68 VA: 0x7598e68c68
	public static Void set_targetFrameRate(Int32 value) { }
	// RVA: 0x6850ca4 VA: 0x7598e68ca4
	private static Void SetLogCallbackDefined(Boolean defined) { }
	// RVA: 0x6850ce0 VA: 0x7598e68ce0
	public static RuntimePlatform get_platform() { }
	// RVA: 0x6850d08 VA: 0x7598e68d08
	public static Boolean get_isMobilePlatform() { }
	// RVA: 0x6850d8c VA: 0x7598e68d8c
	public static NetworkReachability get_internetReachability() { }
	// RVA: 0x6850db4 VA: 0x7598e68db4
	public static Void add_lowMemory(LowMemoryCallback value) { }
	// RVA: 0x6850e6c VA: 0x7598e68e6c
	public static Void remove_lowMemory(LowMemoryCallback value) { }
	// RVA: 0x6850f24 VA: 0x7598e68f24
	internal static Void CallLowMemory() { }
	// RVA: 0x6850f88 VA: 0x7598e68f88
	public static Void add_logMessageReceived(LogCallback value) { }
	// RVA: 0x6851064 VA: 0x7598e69064
	public static Void remove_logMessageReceived(LogCallback value) { }
	// RVA: 0x6851118 VA: 0x7598e69118
	public static Void add_logMessageReceivedThreaded(LogCallback value) { }
	// RVA: 0x68511f4 VA: 0x7598e691f4
	public static Void remove_logMessageReceivedThreaded(LogCallback value) { }
	// RVA: 0x68512a8 VA: 0x7598e692a8
	private static Void CallLogCallback(String logString, String stackTrace, LogType type, Boolean invokedOnMainThread) { }
	// RVA: 0x6851364 VA: 0x7598e69364
	public static Void CaptureScreenshot(String filename) { }
	// RVA: 0x68513b4 VA: 0x7598e693b4
	private static Boolean Internal_ApplicationWantsToQuit() { }
	// RVA: 0x685167c VA: 0x7598e6967c
	private static Void Internal_ApplicationQuit() { }
	// RVA: 0x68516e0 VA: 0x7598e696e0
	private static Void Internal_ApplicationUnload() { }
	// RVA: 0x6851744 VA: 0x7598e69744
	internal static Void InvokeOnBeforeRender() { }
	// RVA: 0x685192c VA: 0x7598e6992c
	internal static Void InvokeFocusChanged(Boolean focus) { }
	// RVA: 0x6851998 VA: 0x7598e69998
	internal static Void InvokeDeepLinkActivated(String url) { }
	// RVA: 0x6851a04 VA: 0x7598e69a04
	public static Void RegisterLogCallback(LogCallback handler) { }
	// RVA: 0x6851a0c VA: 0x7598e69a0c
	private static Void RegisterLogCallback(LogCallback handler, Boolean threaded) { }
	// RVA: 0x6851ae0 VA: 0x7598e69ae0
	public static Boolean get_isEditor() { }
}
```