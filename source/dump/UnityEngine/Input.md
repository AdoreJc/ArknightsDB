# Input

**Namespace:** `UnityEngine`


## Dump
```C#
// Dll : UnityEngine.InputLegacyModule.dll
// Namespace : UnityEngine
public class Input
{
	private static Gyroscope s_MainGyro; // 0x0

	public static Vector3 mousePosition { get; }
	public static Vector2 mouseScrollDelta { get; }
	public static IMECompositionMode imeCompositionMode { get; set; }
	public static String compositionString { get; }
	public static Vector2 compositionCursorPos { get; set; }
	public static Boolean mousePresent { get; }
	public static Int32 touchCount { get; }
	public static Boolean touchSupported { get; }
	public static DeviceOrientation deviceOrientation { get; }
	public static Gyroscope gyro { get; }
	public static Touch[] touches { get; }

	// RVA: 0x68ce950 VA: 0x7598ee6950
	private static Boolean GetKeyInt(KeyCode key) { }
	// RVA: 0x68ce98c VA: 0x7598ee698c
	private static Boolean GetKeyUpInt(KeyCode key) { }
	// RVA: 0x68ce9c8 VA: 0x7598ee69c8
	private static Boolean GetKeyDownInt(KeyCode key) { }
	// RVA: 0x68cea04 VA: 0x7598ee6a04
	public static Single GetAxis(String axisName) { }
	// RVA: 0x68cea40 VA: 0x7598ee6a40
	public static Single GetAxisRaw(String axisName) { }
	// RVA: 0x68cea7c VA: 0x7598ee6a7c
	public static Boolean GetButton(String buttonName) { }
	// RVA: 0x68ceab8 VA: 0x7598ee6ab8
	public static Boolean GetButtonDown(String buttonName) { }
	// RVA: 0x68ceaf4 VA: 0x7598ee6af4
	public static Boolean GetMouseButton(Int32 button) { }
	// RVA: 0x68ceb30 VA: 0x7598ee6b30
	public static Boolean GetMouseButtonDown(Int32 button) { }
	// RVA: 0x68ceb6c VA: 0x7598ee6b6c
	public static Boolean GetMouseButtonUp(Int32 button) { }
	// RVA: 0x68ceba8 VA: 0x7598ee6ba8
	public static Touch GetTouch(Int32 index) { }
	// RVA: 0x68cec5c VA: 0x7598ee6c5c
	public static Boolean GetKey(KeyCode key) { }
	// RVA: 0x68cec98 VA: 0x7598ee6c98
	public static Boolean GetKeyUp(KeyCode key) { }
	// RVA: 0x68cecd4 VA: 0x7598ee6cd4
	public static Boolean GetKeyDown(KeyCode key) { }
	// RVA: 0x68ced10 VA: 0x7598ee6d10
	public static Vector3 get_mousePosition() { }
	// RVA: 0x68ced98 VA: 0x7598ee6d98
	public static Vector2 get_mouseScrollDelta() { }
	// RVA: 0x68cee18 VA: 0x7598ee6e18
	public static IMECompositionMode get_imeCompositionMode() { }
	// RVA: 0x68cee40 VA: 0x7598ee6e40
	public static Void set_imeCompositionMode(IMECompositionMode value) { }
	// RVA: 0x68cee7c VA: 0x7598ee6e7c
	public static String get_compositionString() { }
	// RVA: 0x68ceea4 VA: 0x7598ee6ea4
	public static Vector2 get_compositionCursorPos() { }
	// RVA: 0x68cef24 VA: 0x7598ee6f24
	public static Void set_compositionCursorPos(Vector2 value) { }
	// RVA: 0x68cefa0 VA: 0x7598ee6fa0
	public static Boolean get_mousePresent() { }
	// RVA: 0x68cefc8 VA: 0x7598ee6fc8
	public static Int32 get_touchCount() { }
	// RVA: 0x68ceff0 VA: 0x7598ee6ff0
	public static Boolean get_touchSupported() { }
	// RVA: 0x68cf018 VA: 0x7598ee7018
	public static DeviceOrientation get_deviceOrientation() { }
	// RVA: 0x68cf040 VA: 0x7598ee7040
	private static Int32 GetGyroInternal() { }
	// RVA: 0x68cf068 VA: 0x7598ee7068
	public static Gyroscope get_gyro() { }
	// RVA: 0x68cf13c VA: 0x7598ee713c
	public static Touch[] get_touches() { }
	// RVA: 0x68cf27c VA: 0x7598ee727c
	internal static Boolean CheckDisabled() { }
	// RVA: 0x68cec18 VA: 0x7598ee6c18
	private static Void GetTouch_Injected(Int32 index, out Touch ret) { }
	// RVA: 0x68ced5c VA: 0x7598ee6d5c
	private static Void get_mousePosition_Injected(out Vector3 ret) { }
	// RVA: 0x68ceddc VA: 0x7598ee6ddc
	private static Void get_mouseScrollDelta_Injected(out Vector2 ret) { }
	// RVA: 0x68ceee8 VA: 0x7598ee6ee8
	private static Void get_compositionCursorPos_Injected(out Vector2 ret) { }
	// RVA: 0x68cef64 VA: 0x7598ee6f64
	private static Void set_compositionCursorPos_Injected(ref Vector2 value) { }
}
```