# UQMMessageCenter

**Namespace:** `GCloud.UQM`


## Methods

- `Void Init()`

- `Void Uninit()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : GCloud.UQM
public class UQMMessageCenter : MonoBehaviour
{
	private static Boolean initialzed; // 0x0
	private static UQMMessageCenter instance; // 0x8

	public static UQMMessageCenter Instance { get; }

	// RVA: 0x66ddcd0 VA: 0x7598cf5cd0
	public static String OnUQMRet(Int32 methodId, Int32 crashType, Int32 logUploadResult) { }
	// RVA: 0x66de214 VA: 0x7598cf6214
	private static extern Void cs_setUnityCallback(UQMRetJsonEventHandler eventHandler) { }
	// RVA: 0x66dcc44 VA: 0x7598cf4c44
	public static UQMMessageCenter get_Instance() { }
	// RVA: 0x66dceac VA: 0x7598cf4eac
	public Void Init() { }
	// RVA: 0x66dd008 VA: 0x7598cf5008
	public Void Uninit() { }
	// RVA: 0x66dde40 VA: 0x7598cf5e40
	private static String SynchronousDelegate(Object arg) { }
	// RVA: 0x66de368 VA: 0x7598cf6368
	public Void .ctor() { }
}
```