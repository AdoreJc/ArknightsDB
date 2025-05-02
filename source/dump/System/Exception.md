# Exception

**Namespace:** `System`


## Fields

- `String _className`

- `IDictionary _data`

- `Exception _innerException`

- `String _helpURL`

- `Object _stackTrace`

- `String _stackTraceString`

- `String _remoteStackTraceString`

- `Int32 _remoteStackIndex`

- `Object _dynamicMethods`

- `String _source`

- `SafeSerializationManager _safeSerializationManager`

- `Int32 caught_in_unmanaged`


## Properties

- `Exception InnerException`

- `MethodBase TargetSite`

- `Int32 HResult`


## Methods

- `Void Init()`

- `String GetClassName()`

- `Exception get_InnerException()`

- `MethodBase get_TargetSite()`

- `String GetStackTrace(Boolean)`

- `String ToString(Boolean, Boolean)`

- `Void OnDeserialized(StreamingContext)`

- `String StripFileInfo(String, Boolean)`

- `Int32 get_HResult()`

- `Void set_HResult(Int32)`

- `Type GetType()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
public class Exception : ISerializable
{
	private static Object s_EDILock; // 0x0
	private String _className; // 0x10
	internal String _message; // 0x18
	private IDictionary _data; // 0x20
	private Exception _innerException; // 0x28
	private String _helpURL; // 0x30
	private Object _stackTrace; // 0x38
	private String _stackTraceString; // 0x40
	private String _remoteStackTraceString; // 0x48
	private Int32 _remoteStackIndex; // 0x50
	private Object _dynamicMethods; // 0x58
	internal Int32 _HResult; // 0x60
	private String _source; // 0x68
	private SafeSerializationManager _safeSerializationManager; // 0x70
	internal StackTrace[] captured_traces; // 0x78
	private IntPtr[] native_trace_ips; // 0x80
	private Int32 caught_in_unmanaged; // 0x88
	private const Int32 _COMPlusExceptionCode; // 0x0

	public virtual String Message { get; }
	public virtual IDictionary Data { get; }
	public Exception InnerException { get; }
	public MethodBase TargetSite { get; }
	public virtual String StackTrace { get; }
	public virtual String Source { get; }
	public Int32 HResult { get; set; }

	// RVA: 0x60eaa14 VA: 0x7598702a14
	private Void Init() { }
	// RVA: 0x60eaabc VA: 0x7598702abc
	public Void .ctor() { }
	// RVA: 0x60eaad8 VA: 0x7598702ad8
	public Void .ctor(String message) { }
	// RVA: 0x60eab10 VA: 0x7598702b10
	public Void .ctor(String message, Exception innerException) { }
	// RVA: 0x60eab5c VA: 0x7598702b5c
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x60eb0b8 VA: 0x75987030b8
	public virtual String get_Message() { }
	// RVA: 0x60eb1f8 VA: 0x75987031f8
	public virtual IDictionary get_Data() { }
	// RVA: 0x60eb1ac VA: 0x75987031ac
	private String GetClassName() { }
	// RVA: 0x60eb278 VA: 0x7598703278
	public Exception get_InnerException() { }
	// RVA: 0x60eb280 VA: 0x7598703280
	public MethodBase get_TargetSite() { }
	// RVA: 0x60eb32c VA: 0x759870332c
	public virtual String get_StackTrace() { }
	// RVA: 0x60eb334 VA: 0x7598703334
	private String GetStackTrace(Boolean needFileInfo) { }
	// RVA: 0x60eb388 VA: 0x7598703388
	internal Void SetErrorCode(Int32 hr) { }
	// RVA: 0x60eb390 VA: 0x7598703390
	public virtual String get_Source() { }
	// RVA: 0x60eb4a8 VA: 0x75987034a8
	public override String ToString() { }
	// RVA: 0x60eb4b4 VA: 0x75987034b4
	private String ToString(Boolean needFileLineInfo, Boolean needMessage) { }
	// RVA: 0x60eb7c0 VA: 0x75987037c0
	public virtual Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x60ebc7c VA: 0x7598703c7c
	private Void OnDeserialized(StreamingContext context) { }
	// RVA: 0x60eb380 VA: 0x7598703380
	private String StripFileInfo(String stackTrace, Boolean isRemoteStackTrace) { }
	// RVA: 0x60ebd14 VA: 0x7598703d14
	internal Void RestoreExceptionDispatchInfo(ExceptionDispatchInfo exceptionDispatchInfo) { }
	// RVA: 0x60ebdf0 VA: 0x7598703df0
	public Int32 get_HResult() { }
	// RVA: 0x60ebdf8 VA: 0x7598703df8
	protected Void set_HResult(Int32 value) { }
	// RVA: 0x60eb270 VA: 0x7598703270
	public Type GetType() { }
	// RVA: 0x60ebe00 VA: 0x7598703e00
	internal static String GetMessageFromNativeResources(ExceptionMessageKind kind) { }
	// RVA: 0x60ebe84 VA: 0x7598703e84
	internal Exception FixRemotingException() { }
	// RVA: 0x60ebf88 VA: 0x7598703f88
	internal static Void ReportUnhandledException(Exception exception) { }
	// RVA: 0x60ebf8c VA: 0x7598703f8c
	private static Void .cctor() { }
}
```