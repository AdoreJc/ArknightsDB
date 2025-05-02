# NativeInputSystem

**Namespace:** `UnityEngineInternal.Input`


## Dump
```C#
// Dll : UnityEngine.InputModule.dll
// Namespace : UnityEngineInternal.Input
internal class NativeInputSystem
{
	public static NativeUpdateCallback onUpdate; // 0x0
	public static Action`1 onBeforeUpdate; // 0x8
	public static Func`2 onShouldRunUpdate; // 0x10
	private static Action`2 s_OnDeviceDiscoveredCallback; // 0x18

	internal static Boolean hasDeviceDiscoveredCallback { set; }

	// RVA: 0x68d15a0 VA: 0x7598ee95a0
	private static Void .cctor() { }
	// RVA: 0x68d160c VA: 0x7598ee960c
	internal static Void NotifyBeforeUpdate(NativeInputUpdateType updateType) { }
	// RVA: 0x68d1688 VA: 0x7598ee9688
	internal static Void NotifyUpdate(NativeInputUpdateType updateType, IntPtr eventBuffer) { }
	// RVA: 0x68d1724 VA: 0x7598ee9724
	internal static Void NotifyDeviceDiscovered(Int32 deviceId, String deviceDescriptor) { }
	// RVA: 0x68d17b4 VA: 0x7598ee97b4
	internal static Void ShouldRunUpdate(NativeInputUpdateType updateType, out Boolean retval) { }
	// RVA: 0x68d15d0 VA: 0x7598ee95d0
	internal static Void set_hasDeviceDiscoveredCallback(Boolean value) { }
}
```