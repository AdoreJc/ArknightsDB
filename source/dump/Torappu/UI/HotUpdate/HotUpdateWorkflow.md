# HotUpdateWorkflow

**Namespace:** `Torappu.UI.HotUpdate`


## Fields

- `IContext m_context`

- `FWork m_work`

- `Worker m_worker`

- `IEnumerator m_mainRoutine`

- `Content <clientOutOfDateReason>k__BackingField`

- `Boolean <isDisposed>k__BackingField`


## Properties

- `Content clientOutOfDateReason`

- `Boolean isDisposed`


## Methods

- `Content get_clientOutOfDateReason()`

- `Void set_clientOutOfDateReason(Content)`

- `Boolean get_isDisposed()`

- `Void set_isDisposed(Boolean)`

- `Coroutine StartWorkflow()`

- `IEnumerator _DoWorkFlowRoutine()`

- `Void Dispose()`

- `Boolean PeekFallbackStatus(out)`

- `Boolean Fallback(ENode, Boolean)`

- `Boolean CancelAndFallback(ENode, Boolean)`

- `Void SendEvent(ViewEvent)`

- `Void SendEvent(ViewEvent, ValueBundle)`

- `Void AddEventReceiver(IEventReceiver)`

- `Boolean UpdateOnce(IWorkerUpdateOnce)`

- `Boolean _HandleGlobalEvent(ViewEvent, ValueBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HotUpdate
public class HotUpdateWorkflow : IDisposable
{
	private static readonly ENode[] NODE_ORDER; // 0x0
	private readonly List`1 m_nodes; // 0x10
	private IContext m_context; // 0x18
	private FWork m_work; // 0x20
	private Worker m_worker; // 0x30
	private IEnumerator m_mainRoutine; // 0x38
	private HashSet`1 m_evtRecvrs; // 0x40
	private List`1 m_recvrBuffer; // 0x48
	private Content <clientOutOfDateReason>k__BackingField; // 0x50
	private Boolean <isDisposed>k__BackingField; // 0x58

	public Content clientOutOfDateReason { get; set; }
	public Boolean isDisposed { get; set; }

	// RVA: 0x27d315c VA: 0x7594deb15c
	public Content get_clientOutOfDateReason() { }
	// RVA: 0x27d3164 VA: 0x7594deb164
	private Void set_clientOutOfDateReason(Content value) { }
	// RVA: 0x27d316c VA: 0x7594deb16c
	public Boolean get_isDisposed() { }
	// RVA: 0x27d3174 VA: 0x7594deb174
	private Void set_isDisposed(Boolean value) { }
	// RVA: 0x27d3180 VA: 0x7594deb180
	private Void .ctor() { }
	// RVA: 0x27d32ec VA: 0x7594deb2ec
	public static HotUpdateWorkflow Create(Options options) { }
	// RVA: 0x27d35b8 VA: 0x7594deb5b8
	public Coroutine StartWorkflow() { }
	// RVA: 0x27d369c VA: 0x7594deb69c
	private IEnumerator _DoWorkFlowRoutine() { }
	// RVA: 0x27d3738 VA: 0x7594deb738
	public Void Dispose() { }
	// RVA: 0x27d3acc VA: 0x7594debacc
	public Boolean PeekFallbackStatus(out ENode fallbackNode) { }
	// RVA: 0x27d3bc4 VA: 0x7594debbc4
	public Boolean Fallback(ENode target, Boolean validCheck) { }
	// RVA: 0x27d3f1c VA: 0x7594debf1c
	public Boolean CancelAndFallback(ENode target, Boolean validCheck) { }
	// RVA: 0x27d3fa0 VA: 0x7594debfa0
	public Void SendEvent(ViewEvent evt) { }
	// RVA: 0x27d4024 VA: 0x7594dec024
	public Void SendEvent(ViewEvent evt, ValueBundle param) { }
	// RVA: 0x27d4678 VA: 0x7594dec678
	public Void AddEventReceiver(IEventReceiver receiver) { }
	// RVA: 0x27d46e0 VA: 0x7594dec6e0
	public Boolean UpdateOnce(IWorkerUpdateOnce inst) { }
	// RVA: 0x27d475c VA: 0x7594dec75c
	public static Boolean IsBeforeWork(ENode curNode, ENode check) { }
	// RVA: 0x27d47cc VA: 0x7594dec7cc
	public static Boolean IsOnOrAfterWork(ENode curNode, ENode check) { }
	// RVA: 0x27d4888 VA: 0x7594dec888
	public static Boolean IsAfterWork(ENode target, ENode check) { }
	// RVA: 0x27d4384 VA: 0x7594dec384
	private Boolean _HandleGlobalEvent(ViewEvent evt, ValueBundle param) { }
	// RVA: 0x27d4938 VA: 0x7594dec938
	private static Void .cctor() { }
}
```