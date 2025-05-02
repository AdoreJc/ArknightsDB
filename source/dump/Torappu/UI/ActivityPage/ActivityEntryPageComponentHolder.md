# ActivityEntryPageComponentHolder

**Namespace:** `Torappu.UI.ActivityPage`


## Fields

- `ActivityEntryPage m_page`


## Methods

- `Void _BindPlugins()`

- `Void _UnBindPlugins()`

- `Void <>xLuaBaseProxy_OnCreate()`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityPage
public class ActivityEntryPageComponentHolder : PageSingleComponent
{
	private List`1 _pluginList; // 0x20
	protected ActivityEntryPage m_page; // 0x28
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x8
	private static DelegateBridge __Hotfix0__BindPlugins; // 0x10
	private static DelegateBridge __Hotfix0__UnBindPlugins; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2eef268 VA: 0x7595507268
	protected override Void OnCreate() { }
	// RVA: 0x2eef578 VA: 0x7595507578
	protected override Void OnDestroy() { }
	// RVA: 0x2eef37c VA: 0x759550737c
	private Void _BindPlugins() { }
	// RVA: 0x2eef5ec VA: 0x75955075ec
	private Void _UnBindPlugins() { }
	// RVA: 0x2eef80c VA: 0x759550780c
	public Void .ctor() { }
	// RVA: 0x2eef87c VA: 0x759550787c
	private Void <>xLuaBaseProxy_OnCreate() { }
	// RVA: 0x2eef884 VA: 0x7595507884
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```