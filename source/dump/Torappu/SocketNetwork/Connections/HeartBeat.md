# HeartBeat

**Namespace:** `Torappu.SocketNetwork.Connections`


## Fields

- `UInt32 m_beatCnt`

- `Thread m_beatThread`

- `Stopwatch m_watch`

- `PingCalculator m_estimate`

- `PingCalculator m_determinate`

- `PingCalculator m_calculator`

- `Int64 m_tickMS`

- `Int32 m_ping`

- `Int64 m_lastRetTick`

- `Int32 m_noRespCnt`


## Properties

- `Int32 ping`


## Methods

- `Int32 get_ping()`

- `Int32 _Estimate()`

- `Int32 _Determinate()`

- `Void _SetDeterminate(Int32)`

- `Void Start()`

- `Void NetLost()`

- `Void _Beat()`

- `Boolean ProcHeartBeatRet(NetMsg)`

- `Int64 _GetTicks()`

- `Double _GetMiliSecond()`

- `Double _GetSecond()`

- `Stopwatch _StopWatch()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.SocketNetwork.Connections
public class HeartBeat : IHotfixable
{
	private readonly Connection m_connection; // 0x10
	private UInt32 m_beatCnt; // 0x18
	private Thread m_beatThread; // 0x20
	private Stopwatch m_watch; // 0x28
	private PingCalculator m_estimate; // 0x30
	private PingCalculator m_determinate; // 0x38
	private PingCalculator m_calculator; // 0x40
	private Int64 m_tickMS; // 0x48
	private Int32 m_ping; // 0x50
	private Int64 m_lastRetTick; // 0x58
	private Int32 m_noRespCnt; // 0x60
	private static DelegateBridge __Hotfix0_get_ping; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0__Estimate; // 0x10
	private static DelegateBridge __Hotfix0__Determinate; // 0x18
	private static DelegateBridge __Hotfix0__SetDeterminate; // 0x20
	private static DelegateBridge __Hotfix0_Start; // 0x28
	private static DelegateBridge __Hotfix0_NetLost; // 0x30
	private static DelegateBridge __Hotfix0__Beat; // 0x38
	private static DelegateBridge __Hotfix0_ProcHeartBeatRet; // 0x40
	private static DelegateBridge __Hotfix0__GetTicks; // 0x48
	private static DelegateBridge __Hotfix0__GetMiliSecond; // 0x50
	private static DelegateBridge __Hotfix0__GetSecond; // 0x58
	private static DelegateBridge __Hotfix0__StopWatch; // 0x60

	public Int32 ping { get; }

	// RVA: 0x35747e0 VA: 0x7595b8c7e0
	public Int32 get_ping() { }
	// RVA: 0x35743c4 VA: 0x7595b8c3c4
	public Void .ctor(Connection connection) { }
	// RVA: 0x3575564 VA: 0x7595b8d564
	private Int32 _Estimate() { }
	// RVA: 0x35756a8 VA: 0x7595b8d6a8
	private Int32 _Determinate() { }
	// RVA: 0x35754dc VA: 0x7595b8d4dc
	private Void _SetDeterminate(Int32 ping) { }
	// RVA: 0x3575108 VA: 0x7595b8d108
	public Void Start() { }
	// RVA: 0x3575250 VA: 0x7595b8d250
	public Void NetLost() { }
	// RVA: 0x3575710 VA: 0x7595b8d710
	private Void _Beat() { }
	// RVA: 0x3574f48 VA: 0x7595b8cf48
	public Boolean ProcHeartBeatRet(NetMsg msg) { }
	// RVA: 0x3575630 VA: 0x7595b8d630
	private Int64 _GetTicks() { }
	// RVA: 0x3575924 VA: 0x7595b8d924
	private Double _GetMiliSecond() { }
	// RVA: 0x3575aa0 VA: 0x7595b8daa0
	private Double _GetSecond() { }
	// RVA: 0x35759e0 VA: 0x7595b8d9e0
	private Stopwatch _StopWatch() { }
}
```