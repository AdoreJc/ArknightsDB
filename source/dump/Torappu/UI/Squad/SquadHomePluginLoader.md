# SquadHomePluginLoader

**Namespace:** `Torappu.UI.Squad`


## Fields

- `Transform _pluginContainer`

- `SquadHomePlugin m_plugin`


## Methods

- `SquadHomePluginView Init(PluginInputParams)`

- `Void _Release()`

- `Void Release()`

- `Void _CreatePlugin(PluginInputParams, SquadHomePluginView)`

- `SquadHomePlugin GetActivePlugin()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadHomePluginLoader : PageSingleComponent
{
	private Transform _pluginContainer; // 0x20
	private SquadHomePlugin m_plugin; // 0x28
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0__Release; // 0x8
	private static DelegateBridge __Hotfix0_Release; // 0x10
	private static DelegateBridge __Hotfix0__CreatePlugin; // 0x18
	private static DelegateBridge __Hotfix0_GetActivePlugin; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x23cc498 VA: 0x75949e4498
	public SquadHomePluginView Init(PluginInputParams param) { }
	// RVA: 0x23cc6c8 VA: 0x75949e46c8
	private Void _Release() { }
	// RVA: 0x23cc894 VA: 0x75949e4894
	public Void Release() { }
	// RVA: 0x23cc79c VA: 0x75949e479c
	private Void _CreatePlugin(PluginInputParams param, SquadHomePluginView view) { }
	// RVA: 0x23cc8fc VA: 0x75949e48fc
	public SquadHomePlugin GetActivePlugin() { }
	// RVA: 0x23cc964 VA: 0x75949e4964
	public Void .ctor() { }
}
```