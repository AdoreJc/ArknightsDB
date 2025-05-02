# SendMouseEvents

**Namespace:** `UnityEngine`


## Dump
```C#
// Dll : UnityEngine.InputLegacyModule.dll
// Namespace : UnityEngine
internal class SendMouseEvents
{
	private static Boolean s_MouseUsed; // 0x0
	private static readonly HitInfo[] m_LastHit; // 0x8
	private static readonly HitInfo[] m_MouseDownHit; // 0x10
	private static readonly HitInfo[] m_CurrentHit; // 0x18
	private static Camera[] m_Cameras; // 0x20
	public static Func`1 s_GetMouseState; // 0x28
	private static Vector2 s_MousePosition; // 0x30
	private static Boolean s_MouseButtonPressedThisFrame; // 0x38
	private static Boolean s_MouseButtonIsPressed; // 0x39


	// RVA: 0x68cf2a4 VA: 0x7598ee72a4
	private static Void UpdateMouse() { }
	// RVA: 0x68cf468 VA: 0x7598ee7468
	private static Void SetMouseMoved() { }
	// RVA: 0x68cf4c4 VA: 0x7598ee74c4
	private static Void DoSendMouseEvents(Int32 skipRTCameras) { }
	// RVA: 0x68cfe50 VA: 0x7598ee7e50
	private static Void SendEvents(Int32 i, HitInfo hit) { }
	// RVA: 0x68d03f4 VA: 0x7598ee83f4
	private static Void .cctor() { }
}
```