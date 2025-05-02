# BattleEventCenter

**Namespace:** `Torappu.Battle.Core`


## Methods

- `Void _OnCommonEvent(Int32, EventCallbackDelegate)`

- `Void _OnPluginEvent(Int32, EventCallbackDelegate)`

- `Void _EmitCommonEvent(Int32, ValueBundle)`

- `Void _EmitPluginEvent(Int32, ValueBundle)`

- `Void _EmitPluginEvent(Int32, Object)`

- `Void _RemoveCommonEvent(Int32, EventCallbackDelegate)`

- `Void _RemovePluginEvent(Int32, EventCallbackDelegate)`

- `Void _OnCommonEventCallback(Object, EventCallbackDelegate)`

- `Void _OnPluginEventCallback(Object, EventCallbackDelegate)`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Core
public class BattleEventCenter : SingletonWithMonoHost`2, IDisposable
{
	private EventPool`1 m_oriBattleEventPool; // 0x10
	private EventPool`1 m_eventPool; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_oriEventPool; // 0x8
	private static DelegateBridge __Hotfix0_OnCommonEvent; // 0x10
	private static DelegateBridge __Hotfix0_OnPluginEvent; // 0x18
	private static DelegateBridge __Hotfix0_EmitCommonEvent; // 0x20
	private static DelegateBridge __Hotfix1_EmitCommonEvent; // 0x28
	private static DelegateBridge __Hotfix0_EmitPluginEvent; // 0x30
	private static DelegateBridge __Hotfix1_EmitPluginEvent; // 0x38
	private static DelegateBridge __Hotfix2_EmitPluginEvent; // 0x40
	private static DelegateBridge __Hotfix0_RemoveCommonEvent; // 0x48
	private static DelegateBridge __Hotfix0_RemovePluginEvent; // 0x50
	private static DelegateBridge __Hotfix0__GetRealPluginEventNum; // 0x58
	private static DelegateBridge __Hotfix0__OnCommonEvent; // 0x60
	private static DelegateBridge __Hotfix0__OnPluginEvent; // 0x68
	private static DelegateBridge __Hotfix0__EmitCommonEvent; // 0x70
	private static DelegateBridge __Hotfix0__EmitPluginEvent; // 0x78
	private static DelegateBridge __Hotfix1__EmitPluginEvent; // 0x80
	private static DelegateBridge __Hotfix0__RemoveCommonEvent; // 0x88
	private static DelegateBridge __Hotfix0__RemovePluginEvent; // 0x90
	private static DelegateBridge __Hotfix0__OnCommonEventCallback; // 0x98
	private static DelegateBridge __Hotfix0__OnPluginEventCallback; // 0xa0
	private static DelegateBridge __Hotfix0_Dispose; // 0xa8

	public static EventPool`1 oriEventPool { get; }

	// RVA: 0x1dc5008 VA: 0x75943dd008
	private Void .ctor() { }
	// RVA: 0x1dc513c VA: 0x75943dd13c
	public static EventPool`1 get_oriEventPool() { }
	// RVA: 0x1dc51bc VA: 0x75943dd1bc
	public static Boolean OnCommonEvent(Int32 eventNum, EventCallbackDelegate battleDelegate) { }
	// RVA: 0x1dc53a8 VA: 0x75943dd3a8
	public static Boolean OnPluginEvent(Int32 eventNum, EventCallbackDelegate battleDelegate) { }
	// RVA: 0x1dc55a4 VA: 0x75943dd5a4
	public static Boolean EmitCommonEvent(Int32 eventNum) { }
	// RVA: 0x1dc5658 VA: 0x75943dd658
	public static Boolean EmitCommonEvent(Int32 eventNum, ValueBundle bundle) { }
	// RVA: 0x1dc57f8 VA: 0x75943dd7f8
	public static Boolean EmitPluginEvent(Int32 eventNum) { }
	// RVA: 0x1dc5968 VA: 0x75943dd968
	public static Boolean EmitPluginEvent(Int32 eventNum, Object arg) { }
	// RVA: 0x1dc58ac VA: 0x75943dd8ac
	public static Boolean EmitPluginEvent(Int32 eventNum, ValueBundle bundle) { }
	// RVA: 0x1dc5bb8 VA: 0x75943ddbb8
	public static Void RemoveCommonEvent(Int32 eventNum, EventCallbackDelegate battleDelegate) { }
	// RVA: 0x1dc5d14 VA: 0x75943ddd14
	public static Void RemovePluginEvent(Int32 eventNum, EventCallbackDelegate battleDelegate) { }
	// RVA: 0x1dc5e7c VA: 0x75943dde7c
	private static Int32 _GetRealPluginEventNum(Int32 eventNum) { }
	// RVA: 0x1dc5264 VA: 0x75943dd264
	private Void _OnCommonEvent(Int32 eventNum, EventCallbackDelegate battleDelegate) { }
	// RVA: 0x1dc5450 VA: 0x75943dd450
	private Void _OnPluginEvent(Int32 eventNum, EventCallbackDelegate battleDelegate) { }
	// RVA: 0x1dc5714 VA: 0x75943dd714
	private Void _EmitCommonEvent(Int32 eventNum, ValueBundle bundle) { }
	// RVA: 0x1dc5ac8 VA: 0x75943ddac8
	private Void _EmitPluginEvent(Int32 eventNum, ValueBundle bundle) { }
	// RVA: 0x1dc5a10 VA: 0x75943dda10
	private Void _EmitPluginEvent(Int32 eventNum, Object obj) { }
	// RVA: 0x1dc5c68 VA: 0x75943ddc68
	private Void _RemoveCommonEvent(Int32 eventNum, EventCallbackDelegate battleDelegate) { }
	// RVA: 0x1dc5dc4 VA: 0x75943dddc4
	private Void _RemovePluginEvent(Int32 eventNum, EventCallbackDelegate battleDelegate) { }
	// RVA: 0x1dc5ef8 VA: 0x75943ddef8
	private Void _OnCommonEventCallback(Object obj, EventCallbackDelegate battleDelegate) { }
	// RVA: 0x1dc5f9c VA: 0x75943ddf9c
	private Void _OnPluginEventCallback(Object obj, EventCallbackDelegate battleDelegate) { }
	// RVA: 0x1dc6040 VA: 0x75943de040
	public Void Dispose() { }
}
```