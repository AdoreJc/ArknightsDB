# CriWareErrorHandler

**Namespace:** `CriWare`


## Fields

- `Boolean enableDebugPrintOnTerminal`

- `Boolean enableForceCrashOnError`

- `Boolean dontDestroyOnLoad`

- `UInt32 messageBufferCounts`


## Methods

- `Void Initialize()`

- `Void OnDestroy()`

- `Void DequeueErrorMessages()`

- `Void HandleMessage(String)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriWareErrorHandler : CriMonoBehaviour
{
	public Boolean enableDebugPrintOnTerminal; // 0x28
	public Boolean enableForceCrashOnError; // 0x29
	public Boolean dontDestroyOnLoad; // 0x2a
	private static String <errorMessage>k__BackingField; // 0x0
	public static readonly String logPrefix; // 0x8
	private static Callback _onCallback; // 0x10
	public static Callback callback; // 0x18
	public UInt32 messageBufferCounts; // 0x2c
	private ConcurrentQueue`1 unThreadSafeMessages; // 0x30
	private static Int32 initializationCount; // 0x20

	public static String errorMessage { get; set; }

	// RVA: 0x4148970 VA: 0x7596760970
	public static String get_errorMessage() { }
	// RVA: 0x41489c8 VA: 0x75967609c8
	public static Void set_errorMessage(String value) { }
	// RVA: 0x4148a30 VA: 0x7596760a30
	private static Void add__onCallback(Callback value) { }
	// RVA: 0x4148b0c VA: 0x7596760b0c
	private static Void remove__onCallback(Callback value) { }
	// RVA: 0x4148be8 VA: 0x7596760be8
	public static Void add_OnCallback(Callback value) { }
	// RVA: 0x4148dc4 VA: 0x7596760dc4
	public static Void remove_OnCallback(Callback value) { }
	// RVA: 0x4148e1c VA: 0x7596760e1c
	public Void Initialize() { }
	// RVA: 0x41493d0 VA: 0x75967613d0
	protected override Void OnEnable() { }
	// RVA: 0x41494ec VA: 0x75967614ec
	protected override Void OnDisable() { }
	// RVA: 0x4149770 VA: 0x7596761770
	public override Void CriInternalUpdate() { }
	// RVA: 0x41498c0 VA: 0x75967618c0
	public override Void CriInternalLateUpdate() { }
	// RVA: 0x41498c4 VA: 0x75967618c4
	private Void OnDestroy() { }
	// RVA: 0x4148c80 VA: 0x7596760c80
	private static Boolean IsEnableNativePrintMessageFunc() { }
	// RVA: 0x4148d08 VA: 0x7596760d08
	private static Void RegisterErrorCallback() { }
	// RVA: 0x4149774 VA: 0x7596761774
	private Void DequeueErrorMessages() { }
	// RVA: 0x4149b24 VA: 0x7596761b24
	private Void HandleMessage(String errmsg) { }
	// RVA: 0x4149c08 VA: 0x7596761c08
	private static Void OutputDefaultLog(String errmsg) { }
	// RVA: 0x4149dd0 VA: 0x7596761dd0
	public Void .ctor() { }
	// RVA: 0x4149e78 VA: 0x7596761e78
	private static Void .cctor() { }
}
```