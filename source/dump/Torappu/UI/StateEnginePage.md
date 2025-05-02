# StateEnginePage

**Namespace:** `Torappu.UI`


## Fields

- `StateEngine m_stateEngine`

- `Boolean m_createFlag`

- `InvokeWhenUnlock m_startStateEngine`


## Properties

- `StateEngine stateEngine`

- `Plugin plugin`


## Methods

- `Boolean IsStateEngineTransiting()`

- `StateEngine get_stateEngine()`

- `InvokeWhenUnlock StartStateEngine()`

- `Plugin get_plugin()`

- `Void <>xLuaBaseProxy_OnStart()`

- `Void <>xLuaBaseProxy_OnStop()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(Boolean)`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(Boolean)`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class StateEnginePage : UIPage, IMaintainer
{
	private StateEngine m_stateEngine; // 0xd0
	private Boolean m_createFlag; // 0xd8
	private InvokeWhenUnlock m_startStateEngine; // 0xe0
	private static DelegateBridge __Hotfix0_IsStateEngineTransiting; // 0x0
	private static DelegateBridge __Hotfix0_get_stateEngine; // 0x8
	private static DelegateBridge __Hotfix0_OnStart; // 0x10
	private static DelegateBridge __Hotfix0_OnStop; // 0x18
	private static DelegateBridge __Hotfix0_StartStateEngine; // 0x20
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x28
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x30
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x38
	private static DelegateBridge __Hotfix0_OnStateEngineReady; // 0x40
	private static DelegateBridge __Hotfix0_get_plugin; // 0x48
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x50
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x58
	private static DelegateBridge __Hotfix0_OnCreate; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	protected StateEngine stateEngine { get; }
	protected Plugin plugin { get; }

	// RVA: 0x2165e84 VA: 0x759477de84
	public Boolean IsStateEngineTransiting() { }
	// RVA: 0x2165f60 VA: 0x759477df60
	protected StateEngine get_stateEngine() { }
	// RVA: 0x21660ac VA: 0x759477e0ac
	protected override Void OnStart() { }
	// RVA: 0x216612c VA: 0x759477e12c
	protected override Void OnStop() { }
	// RVA: 0x2166230 VA: 0x759477e230
	public InvokeWhenUnlock StartStateEngine() { }
	// RVA: 0x2166298 VA: 0x759477e298
	protected virtual IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x2166388 VA: 0x759477e388
	protected virtual IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x2166478 VA: 0x759477e478
	protected virtual IEnumerator InitStateEngine() { }
	// RVA: 0x216654c VA: 0x759477e54c
	protected virtual Void OnStateEngineReady(Boolean isFromStack) { }
	// RVA: 0x21665c4 VA: 0x759477e5c4
	protected Plugin get_plugin() { }
	// RVA: 0x2166678 VA: 0x759477e678
	public sealed override IEnumerator ShowCoroutine(Boolean isFromStack) { }
	// RVA: 0x2166768 VA: 0x759477e768
	protected sealed override IEnumerator HideCoroutine(Boolean isIntoStack) { }
	// RVA: 0x2166858 VA: 0x759477e858
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x21668ec VA: 0x759477e8ec
	public Void .ctor() { }
	// RVA: 0x216699c VA: 0x759477e99c
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x21669a4 VA: 0x759477e9a4
	private Void <>xLuaBaseProxy_OnStop() { }
	// RVA: 0x21669ac VA: 0x759477e9ac
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(Boolean P0) { }
	// RVA: 0x21669b8 VA: 0x759477e9b8
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(Boolean P0) { }
	// RVA: 0x21669c4 VA: 0x759477e9c4
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
}
```