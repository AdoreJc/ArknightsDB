# Debug

**Namespace:** `UnityEngine`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class Debug
{
	internal static readonly ILogger s_DefaultLogger; // 0x0
	internal static ILogger s_Logger; // 0x8

	public static ILogger unityLogger { get; }
	public static Boolean developerConsoleVisible { get; set; }
	public static Boolean isDebugBuild { get; }
	internal static DiagnosticSwitch[] diagnosticSwitches { get; }
	public static ILogger logger { get; }

	// RVA: 0x6856264 VA: 0x7598e6e264
	public static ILogger get_unityLogger() { }
	// RVA: 0x68562bc VA: 0x7598e6e2bc
	public static Void DrawLine(Vector3 start, Vector3 end, Color color, Single duration) { }
	// RVA: 0x6856480 VA: 0x7598e6e480
	public static Void DrawLine(Vector3 start, Vector3 end, Color color) { }
	// RVA: 0x6856568 VA: 0x7598e6e568
	public static Void DrawLine(Vector3 start, Vector3 end) { }
	// RVA: 0x68563cc VA: 0x7598e6e3cc
	public static Void DrawLine(Vector3 start, Vector3 end, Color color, Single duration, Boolean depthTest) { }
	// RVA: 0x6856684 VA: 0x7598e6e684
	public static Void DrawRay(Vector3 start, Vector3 dir, Color color, Single duration) { }
	// RVA: 0x68568a0 VA: 0x7598e6e8a0
	public static Void DrawRay(Vector3 start, Vector3 dir, Color color) { }
	// RVA: 0x6856988 VA: 0x7598e6e988
	public static Void DrawRay(Vector3 start, Vector3 dir) { }
	// RVA: 0x6856794 VA: 0x7598e6e794
	public static Void DrawRay(Vector3 start, Vector3 dir, Color color, Single duration, Boolean depthTest) { }
	// RVA: 0x6856a38 VA: 0x7598e6ea38
	public static Void Break() { }
	// RVA: 0x6856a60 VA: 0x7598e6ea60
	public static Void DebugBreak() { }
	// RVA: 0x6856a88 VA: 0x7598e6ea88
	public static Int32 ExtractStackTraceNoAlloc(Byte* buffer, Int32 bufferMax, String projectFolder) { }
	// RVA: 0x6856adc VA: 0x7598e6eadc
	public static Void Log(Object message) { }
	// RVA: 0x6856be4 VA: 0x7598e6ebe4
	public static Void Log(Object message, Object context) { }
	// RVA: 0x6856cfc VA: 0x7598e6ecfc
	public static Void LogFormat(String format, Object[] args) { }
	// RVA: 0x6856e14 VA: 0x7598e6ee14
	public static Void LogFormat(Object context, String format, Object[] args) { }
	// RVA: 0x6856f30 VA: 0x7598e6ef30
	public static Void LogFormat(LogType logType, LogOption logOptions, Object context, String format, Object[] args) { }
	// RVA: 0x6857208 VA: 0x7598e6f208
	public static Void LogError(Object message) { }
	// RVA: 0x6857310 VA: 0x7598e6f310
	public static Void LogError(Object message, Object context) { }
	// RVA: 0x6857428 VA: 0x7598e6f428
	public static Void LogErrorFormat(String format, Object[] args) { }
	// RVA: 0x6857540 VA: 0x7598e6f540
	public static Void LogErrorFormat(Object context, String format, Object[] args) { }
	// RVA: 0x685765c VA: 0x7598e6f65c
	public static Void ClearDeveloperConsole() { }
	// RVA: 0x6857684 VA: 0x7598e6f684
	public static Boolean get_developerConsoleVisible() { }
	// RVA: 0x68576ac VA: 0x7598e6f6ac
	public static Void set_developerConsoleVisible(Boolean value) { }
	// RVA: 0x6851574 VA: 0x7598e69574
	public static Void LogException(Exception exception) { }
	// RVA: 0x68576e8 VA: 0x7598e6f6e8
	public static Void LogException(Exception exception, Object context) { }
	// RVA: 0x68577fc VA: 0x7598e6f7fc
	public static Void LogWarning(Object message) { }
	// RVA: 0x6857904 VA: 0x7598e6f904
	public static Void LogWarning(Object message, Object context) { }
	// RVA: 0x6857a1c VA: 0x7598e6fa1c
	public static Void LogWarningFormat(String format, Object[] args) { }
	// RVA: 0x6857b34 VA: 0x7598e6fb34
	public static Void LogWarningFormat(Object context, String format, Object[] args) { }
	// RVA: 0x6857c50 VA: 0x7598e6fc50
	public static Void Assert(Boolean condition) { }
	// RVA: 0x6857d80 VA: 0x7598e6fd80
	public static Void Assert(Boolean condition, Object context) { }
	// RVA: 0x6857eb8 VA: 0x7598e6feb8
	public static Void Assert(Boolean condition, Object message) { }
	// RVA: 0x6857fd4 VA: 0x7598e6ffd4
	public static Void Assert(Boolean condition, String message) { }
	// RVA: 0x68580f0 VA: 0x7598e700f0
	public static Void Assert(Boolean condition, Object message, Object context) { }
	// RVA: 0x6858220 VA: 0x7598e70220
	public static Void Assert(Boolean condition, String message, Object context) { }
	// RVA: 0x6858350 VA: 0x7598e70350
	public static Void AssertFormat(Boolean condition, String format, Object[] args) { }
	// RVA: 0x6858480 VA: 0x7598e70480
	public static Void AssertFormat(Boolean condition, Object context, String format, Object[] args) { }
	// RVA: 0x68585b4 VA: 0x7598e705b4
	public static Void LogAssertion(Object message) { }
	// RVA: 0x68586bc VA: 0x7598e706bc
	public static Void LogAssertion(Object message, Object context) { }
	// RVA: 0x68587d4 VA: 0x7598e707d4
	public static Void LogAssertionFormat(String format, Object[] args) { }
	// RVA: 0x68588ec VA: 0x7598e708ec
	public static Void LogAssertionFormat(Object context, String format, Object[] args) { }
	// RVA: 0x6858a08 VA: 0x7598e70a08
	public static Boolean get_isDebugBuild() { }
	// RVA: 0x6858a30 VA: 0x7598e70a30
	internal static Void OpenConsoleFile() { }
	// RVA: 0x6858a58 VA: 0x7598e70a58
	internal static DiagnosticSwitch[] get_diagnosticSwitches() { }
	// RVA: 0x6858a80 VA: 0x7598e70a80
	internal static DiagnosticSwitch GetDiagnosticSwitch(String name) { }
	// RVA: 0x6858c20 VA: 0x7598e70c20
	internal static Boolean CallOverridenDebugHandler(Exception exception, Object obj) { }
	// RVA: 0x6859018 VA: 0x7598e71018
	internal static Boolean IsLoggingEnabled() { }
	// RVA: 0x685923c VA: 0x7598e7123c
	public static Void Assert(Boolean condition, String format, Object[] args) { }
	// RVA: 0x685936c VA: 0x7598e7136c
	public static ILogger get_logger() { }
	// RVA: 0x68593c4 VA: 0x7598e713c4
	public Void .ctor() { }
	// RVA: 0x68593cc VA: 0x7598e713cc
	private static Void .cctor() { }
	// RVA: 0x6856618 VA: 0x7598e6e618
	private static Void DrawLine_Injected(ref Vector3 start, ref Vector3 end, ref Color color, Single duration, Boolean depthTest) { }
}
```