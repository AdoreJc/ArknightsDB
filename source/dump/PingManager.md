# PingManager

**Namespace:** ` `


## Fields

- `HGSDK m_sdk`

- `Options m_options`

- `Int32 m_nextPingInterval`

- `Single m_accumTimeSinceLastPing`


## Properties

- `Int32 intervalSinceLastPingAsInt`


## Methods

- `Int32 get_intervalSinceLastPingAsInt()`

- `Void FirstPing(Action, Action)`

- `Void UpdatePing(Single)`

- `Void _DoPeriodicPing(Int32)`

- `PingServiceHandler _CallPingService(Int32)`

- `Boolean _CheckPingable()`

- `Void _SetNoPeriodicPing()`

- `Void _SetNextPeriodicPing(Int32)`

- `Void _DoQuit()`

- `Void <_DoPeriodicPing>b__13_0(PingResponse)`

- `Void <_DoPeriodicPing>b__13_2()`

- `Void <_DoPeriodicPing>b__13_1(ResponseError)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PingManager : IHotfixable
{
	private static readonly String[] PINGABLE_SCENES; // 0x0
	private HGSDK m_sdk; // 0x10
	private Options m_options; // 0x18
	private Int32 m_nextPingInterval; // 0x20
	private Single m_accumTimeSinceLastPing; // 0x24
	private Nullable`1 m_cachedLatestInterval; // 0x28
	private static DelegateBridge __Hotfix0_get_intervalSinceLastPingAsInt; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_FirstPing; // 0x18
	private static DelegateBridge __Hotfix0_UpdatePing; // 0x20
	private static DelegateBridge __Hotfix0__DoPeriodicPing; // 0x28
	private static DelegateBridge __Hotfix0__CallPingService; // 0x30
	private static DelegateBridge __Hotfix0__CheckPingable; // 0x38
	private static DelegateBridge __Hotfix0__SetNoPeriodicPing; // 0x40
	private static DelegateBridge __Hotfix0__SetNextPeriodicPing; // 0x48
	private static DelegateBridge __Hotfix0__HandleToastEvent; // 0x50
	private static DelegateBridge __Hotfix0__ShowToastCoroutine; // 0x58
	private static DelegateBridge __Hotfix0__DoQuit; // 0x60

	private Int32 intervalSinceLastPingAsInt { get; }

	// RVA: 0x2f267c4 VA: 0x759553e7c4
	private Int32 get_intervalSinceLastPingAsInt() { }
	// RVA: 0x2f23668 VA: 0x759553b668
	public Void .ctor(HGSDK sdk, Options options) { }
	// RVA: 0x2f26990 VA: 0x759553e990
	public Void FirstPing(Action onSuc, Action onFail) { }
	// RVA: 0x2f1d9f8 VA: 0x75955359f8
	public Void UpdatePing(Single deltaTime) { }
	// RVA: 0x2f26fbc VA: 0x759553efbc
	private Void _DoPeriodicPing(Int32 interval) { }
	// RVA: 0x2f26b54 VA: 0x759553eb54
	private PingServiceHandler _CallPingService(Int32 interval) { }
	// RVA: 0x2f26eb0 VA: 0x759553eeb0
	private Boolean _CheckPingable() { }
	// RVA: 0x2f26914 VA: 0x759553e914
	private Void _SetNoPeriodicPing() { }
	// RVA: 0x2f27124 VA: 0x759553f124
	private Void _SetNextPeriodicPing(Int32 interval) { }
	// RVA: 0x2f271e4 VA: 0x759553f1e4
	private static Void _HandleToastEvent(PingResponse response) { }
	// RVA: 0x2f272cc VA: 0x759553f2cc
	private static IEnumerator _ShowToastCoroutine(String content) { }
	// RVA: 0x2f273b0 VA: 0x759553f3b0
	private Void _DoQuit() { }
	// RVA: 0x2f2744c VA: 0x759553f44c
	private static Void .cctor() { }
	// RVA: 0x2f275ec VA: 0x759553f5ec
	private Void <_DoPeriodicPing>b__13_0(PingResponse response) { }
	// RVA: 0x2f277c0 VA: 0x759553f7c0
	private Void <_DoPeriodicPing>b__13_2() { }
	// RVA: 0x2f277c4 VA: 0x759553f7c4
	private Void <_DoPeriodicPing>b__13_1(ResponseError error) { }
}
```