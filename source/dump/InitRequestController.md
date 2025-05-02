# InitRequestController

**Namespace:** ` `


## Fields

- `Boolean m_isCallbackBinded`

- `InitState <state>k__BackingField`


## Properties

- `InitState state`


## Methods

- `InitState get_state()`

- `Void set_state(InitState)`

- `Void InvokeInit()`

- `Void Dispose()`

- `Void _OnInitCallback(HGSDKInitMessage)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class InitRequestController : IHotfixable, IDisposable
{
	private Boolean m_isCallbackBinded; // 0x10
	private InitState <state>k__BackingField; // 0x14
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_set_state; // 0x8
	private static DelegateBridge __Hotfix0_InvokeInit; // 0x10
	private static DelegateBridge __Hotfix0_Dispose; // 0x18
	private static DelegateBridge __Hotfix0__CreateInitParam; // 0x20
	private static DelegateBridge __Hotfix0__OnInitCallback; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public InitState state { get; set; }

	// RVA: 0x2f2e830 VA: 0x7595546830
	public InitState get_state() { }
	// RVA: 0x2f2f768 VA: 0x7595547768
	private Void set_state(InitState value) { }
	// RVA: 0x2f2e65c VA: 0x759554665c
	public Void InvokeInit() { }
	// RVA: 0x2f2e988 VA: 0x7595546988
	public Void Dispose() { }
	// RVA: 0x2f2f844 VA: 0x7595547844
	private static String _CreateInitParam() { }
	// RVA: 0x2f2f8c8 VA: 0x75955478c8
	private Void _OnInitCallback(HGSDKInitMessage msg) { }
	// RVA: 0x2f2f620 VA: 0x7595547620
	public Void .ctor() { }
}
```