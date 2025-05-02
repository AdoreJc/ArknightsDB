# CriAtomOutputDeviceObserver

**Namespace:** `CriWare`


## Fields

- `Boolean dontDestroyOnLoad`

- `Boolean lastIsConnected`

- `Boolean isConnected`

- `OutputDeviceType lastDeviceType`

- `OutputDeviceType deviceType`


## Methods

- `Void Awake()`

- `Void OnDestroy()`

- `Void CallbackFromObserver_ANDROID(String)`

- `Void CheckOutputDevice_ANDROID()`

- `IEnumerator CoroutineForCheck_ANDROID()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomOutputDeviceObserver : CriMonoBehaviour
{
	private Boolean dontDestroyOnLoad; // 0x28
	private Boolean lastIsConnected; // 0x29
	private Boolean isConnected; // 0x2a
	private OutputDeviceType lastDeviceType; // 0x2c
	private OutputDeviceType deviceType; // 0x30
	private static CriAtomOutputDeviceObserver instance; // 0x0
	private static DeviceConnectionChangeCallback _onDeviceConnectionChanged; // 0x8
	private static AndroidJavaObject checker; // 0x10

	public static Boolean IsDeviceConnected { get; }
	public static OutputDeviceType DeviceType { get; }

	// RVA: 0x4115ec0 VA: 0x759672dec0
	public static Void add_OnDeviceConnectionChanged(DeviceConnectionChangeCallback value) { }
	// RVA: 0x411618c VA: 0x759672e18c
	public static Void remove_OnDeviceConnectionChanged(DeviceConnectionChangeCallback value) { }
	// RVA: 0x4116044 VA: 0x759672e044
	public static Boolean get_IsDeviceConnected() { }
	// RVA: 0x41160ec VA: 0x759672e0ec
	public static OutputDeviceType get_DeviceType() { }
	// RVA: 0x4115f88 VA: 0x759672df88
	private static Void add__onDeviceConnectionChanged(DeviceConnectionChangeCallback value) { }
	// RVA: 0x4116190 VA: 0x759672e190
	private static Void remove__onDeviceConnectionChanged(DeviceConnectionChangeCallback value) { }
	// RVA: 0x411624c VA: 0x759672e24c
	private Void Awake() { }
	// RVA: 0x41168a4 VA: 0x759672e8a4
	private Void OnDestroy() { }
	// RVA: 0x4116a90 VA: 0x759672ea90
	public override Void CriInternalUpdate() { }
	// RVA: 0x4116b3c VA: 0x759672eb3c
	public override Void CriInternalLateUpdate() { }
	// RVA: 0x4116b40 VA: 0x759672eb40
	private Void CallbackFromObserver_ANDROID(String message) { }
	// RVA: 0x41166f8 VA: 0x759672e6f8
	private Void CheckOutputDevice_ANDROID() { }
	// RVA: 0x4116bec VA: 0x759672ebec
	private IEnumerator CoroutineForCheck_ANDROID() { }
	// RVA: 0x4116c88 VA: 0x759672ec88
	public Void .ctor() { }
}
```