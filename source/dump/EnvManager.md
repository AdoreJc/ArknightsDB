# EnvManager

**Namespace:** ` `


## Properties

- `Map map`


## Methods

- `Map get_map()`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnvManager : Behaviour
{
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x0
	private static DelegateBridge __Hotfix0_get_map; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_OnTrigger; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public virtual IEnumerable`1 eventGroups { get; }
	protected Map map { get; }

	// RVA: 0x4029e68 VA: 0x7596641e68
	public virtual IEnumerable`1 get_eventGroups() { }
	// RVA: 0x4029ee8 VA: 0x7596641ee8
	protected Map get_map() { }
	// RVA: 0x4029f64 VA: 0x7596641f64
	public override Void Init(GlobalEnvSystem system) { }
	// RVA: 0x402a314 VA: 0x7596642314
	public virtual Void OnTrigger(Object param) { }
	// RVA: 0x402a38c VA: 0x759664238c
	public Void .ctor() { }
	// RVA: 0x402a3f8 VA: 0x75966423f8
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
}
```