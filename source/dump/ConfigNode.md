# ConfigNode

**Namespace:** ` `


## Fields

- `ConfigHandler m_networkRouterHandler`

- `IEnumerator m_fetchRoutine`


## Methods

- `IEnumerator _FetchConfigsCoroutine()`

- `IEnumerator _FetchNetworkConfigRoutine()`

- `IEnumerator _FetchRemoteConfigRoutine()`

- `IEnumerator _FetchResVersionRoutine()`

- `Boolean _ValidateClientVersion(String)`

- `Void <>xLuaBaseProxy_OnDispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ConfigNode : Node
{
	private ConfigHandler m_networkRouterHandler; // 0x20
	private IEnumerator m_fetchRoutine; // 0x28
	private static DelegateBridge __Hotfix0_get_type; // 0x0
	private static DelegateBridge __Hotfix0_Work; // 0x8
	private static DelegateBridge __Hotfix0__FetchConfigsCoroutine; // 0x10
	private static DelegateBridge __Hotfix0__FetchNetworkConfigRoutine; // 0x18
	private static DelegateBridge __Hotfix0__FetchRemoteConfigRoutine; // 0x20
	private static DelegateBridge __Hotfix0__FetchResVersionRoutine; // 0x28
	private static DelegateBridge __Hotfix0__MakeNotOverrideRouterForClientUpgrade; // 0x30
	private static DelegateBridge __Hotfix0__ValidateClientVersion; // 0x38
	private static DelegateBridge __Hotfix0_OnDispose; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override ENode type { get; }

	// RVA: 0x27c6aa0 VA: 0x7594ddeaa0
	public override ENode get_type() { }
	// RVA: 0x27c6b08 VA: 0x7594ddeb08
	public override CustomYieldInstruction Work() { }
	// RVA: 0x27c6d04 VA: 0x7594dded04
	private IEnumerator _FetchConfigsCoroutine() { }
	// RVA: 0x27c6dd8 VA: 0x7594ddedd8
	private IEnumerator _FetchNetworkConfigRoutine() { }
	// RVA: 0x27c6eac VA: 0x7594ddeeac
	private IEnumerator _FetchRemoteConfigRoutine() { }
	// RVA: 0x27c6f80 VA: 0x7594ddef80
	private IEnumerator _FetchResVersionRoutine() { }
	// RVA: 0x27c7054 VA: 0x7594ddf054
	private static Content _MakeNotOverrideRouterForClientUpgrade() { }
	// RVA: 0x27c7228 VA: 0x7594ddf228
	private Boolean _ValidateClientVersion(String requiredClientVersion) { }
	// RVA: 0x27c72e4 VA: 0x7594ddf2e4
	public override Void OnDispose() { }
	// RVA: 0x27bf974 VA: 0x7594dd7974
	public Void .ctor() { }
	// RVA: 0x27c742c VA: 0x7594ddf42c
	private Void <>xLuaBaseProxy_OnDispose() { }
}
```