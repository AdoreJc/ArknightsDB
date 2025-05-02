# IdelPeriodGameServerProbe

**Namespace:** `Torappu.Network`


## Fields

- `Timer m_timer`

- `Boolean m_isActive`

- `Single m_idelSecs`


## Methods

- `Void OnBeforeRequest()`

- `Void OnHandleResponse()`

- `Void Dispose()`

- `Void _OnIdelIntervalEnd()`

- `Void _OnPingServiceResponse(PingResponse)`

- `Boolean _OnPingServiceFail(ResponseError)`

- `Void _OnEnterGame()`

- `Void _OnStopGame()`

- `Void _BeforeSceneTransition(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Network
public class IdelPeriodGameServerProbe : Singleton`1, IDisposable
{
	public const Int64 IDEL_SECS_DEFAULT; // 0x0
	public const Int64 IDEL_SECS_MIN; // 0x0
	private Timer m_timer; // 0x10
	private Boolean m_isActive; // 0x18
	private Single m_idelSecs; // 0x1c
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnBeforeRequest; // 0x8
	private static DelegateBridge __Hotfix0_OnHandleResponse; // 0x10
	private static DelegateBridge __Hotfix0_Dispose; // 0x18
	private static DelegateBridge __Hotfix0__OnIdelIntervalEnd; // 0x20
	private static DelegateBridge __Hotfix0__OnPingServiceResponse; // 0x28
	private static DelegateBridge __Hotfix0__OnPingServiceFail; // 0x30
	private static DelegateBridge __Hotfix0__OnEnterGame; // 0x38
	private static DelegateBridge __Hotfix0__OnStopGame; // 0x40
	private static DelegateBridge __Hotfix0__BeforeSceneTransition; // 0x48


	// RVA: 0x3585718 VA: 0x7595b9d718
	private Void .ctor() { }
	// RVA: 0x358597c VA: 0x7595b9d97c
	public Void OnBeforeRequest() { }
	// RVA: 0x3585ab0 VA: 0x7595b9dab0
	public Void OnHandleResponse() { }
	// RVA: 0x3585bf8 VA: 0x7595b9dbf8
	public Void Dispose() { }
	// RVA: 0x3585cd4 VA: 0x7595b9dcd4
	private Void _OnIdelIntervalEnd() { }
	// RVA: 0x3585f14 VA: 0x7595b9df14
	private Void _OnPingServiceResponse(PingResponse response) { }
	// RVA: 0x358601c VA: 0x7595b9e01c
	private Boolean _OnPingServiceFail(ResponseError respError) { }
	// RVA: 0x3586100 VA: 0x7595b9e100
	private Void _OnEnterGame() { }
	// RVA: 0x358616c VA: 0x7595b9e16c
	private Void _OnStopGame() { }
	// RVA: 0x35861e4 VA: 0x7595b9e1e4
	private Void _BeforeSceneTransition(String prev, String target) { }
}
```