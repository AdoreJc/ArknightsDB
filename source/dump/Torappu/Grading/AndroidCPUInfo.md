# AndroidCPUInfo

**Namespace:** `Torappu.Grading`


## Fields

- `String m_hardware`

- `String m_modelName`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `String GetHardware()`

- `String GetModelName()`

- `Void _OnReadCPUInfoLine(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Grading
public class AndroidCPUInfo : Singleton`1
{
	private const String CPU_INFO_PATH; // 0x0
	private const String KEY_HARDWARD; // 0x0
	private const String KEY_MODENAME; // 0x0
	private const Int32 IO_RETRY_COUNT; // 0x0
	private String m_hardware; // 0x10
	private String m_modelName; // 0x18
	private Boolean m_isInited; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetHardware; // 0x8
	private static DelegateBridge __Hotfix0_GetModelName; // 0x10
	private static DelegateBridge __Hotfix0__OnReadCPUInfoLine; // 0x18
	private static DelegateBridge __Hotfix0__ReadLineContent; // 0x20
	private static DelegateBridge __Hotfix0__ReadCPUInfoFileWithRetry; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x35c1988 VA: 0x7595bd9988
	private Void _InitIfNot() { }
	// RVA: 0x35c1ef0 VA: 0x7595bd9ef0
	public String GetHardware() { }
	// RVA: 0x35c1f60 VA: 0x7595bd9f60
	public String GetModelName() { }
	// RVA: 0x35c1fd0 VA: 0x7595bd9fd0
	private Void _OnReadCPUInfoLine(String line) { }
	// RVA: 0x35c20f8 VA: 0x7595bda0f8
	private static String _ReadLineContent(String line) { }
	// RVA: 0x35c1a58 VA: 0x7595bd9a58
	private static Void _ReadCPUInfoFileWithRetry(Action`1 onReadLine) { }
	// RVA: 0x35c21d0 VA: 0x7595bda1d0
	private Void .ctor() { }
}
```