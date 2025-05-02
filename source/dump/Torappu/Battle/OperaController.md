# OperaController

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean m_isLocked`

- `CoroutineId m_coroutine`

- `Object m_param`


## Properties

- `Object param`


## Methods

- `Object get_param()`

- `Void PlayOpera(String, Object)`

- `Void Init(String, out)`

- `Void _LoadConfigIfNot(String)`

- `Void Clear()`

- `Void _Complete()`

- `Void <PlayOpera>b__7_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class OperaController : IHotfixable
{
	private List`1 m_commands; // 0x10
	private Boolean m_isLocked; // 0x18
	private CoroutineId m_coroutine; // 0x20
	private List`1 m_nodesOnCompletedCallback; // 0x30
	private Object m_param; // 0x38
	private static DelegateBridge __Hotfix0_get_param; // 0x0
	private static DelegateBridge __Hotfix0_PlayOpera; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0__LoadConfigIfNot; // 0x18
	private static DelegateBridge __Hotfix0_LoadOperaCommands; // 0x20
	private static DelegateBridge __Hotfix0_Clear; // 0x28
	private static DelegateBridge __Hotfix0__Complete; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Object param { get; }

	// RVA: 0x1c40cb0 VA: 0x7594258cb0
	public Object get_param() { }
	// RVA: 0x1c40d18 VA: 0x7594258d18
	public Void PlayOpera(String key, Object param) { }
	// RVA: 0x1c4107c VA: 0x759425907c
	public Void Init(String config, out PostprocessMask mask) { }
	// RVA: 0x1c41220 VA: 0x7594259220
	private Void _LoadConfigIfNot(String configPath) { }
	// RVA: 0x1c412c4 VA: 0x75942592c4
	public static List`1 LoadOperaCommands(String configPath) { }
	// RVA: 0x1c414e8 VA: 0x75942594e8
	public Void Clear() { }
	// RVA: 0x1c41618 VA: 0x7594259618
	private Void _Complete() { }
	// RVA: 0x1c41748 VA: 0x7594259748
	public Void .ctor() { }
	// RVA: 0x1c4180c VA: 0x759425980c
	private Void <PlayOpera>b__7_0() { }
}
```