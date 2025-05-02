# PageComponent

**Namespace:** `Torappu.UI`


## Fields

- `UIPageListener m_pageListener`


## Methods

- `UIPage GetPage()`

- `Void Awake()`

- `Void TriggerCreate()`

- `Void TriggerReuse()`

- `Void TriggerStart()`

- `Void TriggerStop()`

- `Void TriggerRecycle()`

- `Void TriggerRouted()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class PageComponent : MonoBehaviour, IHotfixable
{
	private UIPageListener m_pageListener; // 0x18
	private static DelegateBridge __Hotfix0_GetPage; // 0x0
	private static DelegateBridge __Hotfix0_OnAwake; // 0x8
	private static DelegateBridge __Hotfix0_OnCreate; // 0x10
	private static DelegateBridge __Hotfix0_OnReuse; // 0x18
	private static DelegateBridge __Hotfix0_OnStart; // 0x20
	private static DelegateBridge __Hotfix0_OnPageRouted; // 0x28
	private static DelegateBridge __Hotfix0_OnStop; // 0x30
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x38
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x40
	private static DelegateBridge __Hotfix0_Awake; // 0x48
	private static DelegateBridge __Hotfix0_TriggerCreate; // 0x50
	private static DelegateBridge __Hotfix0_TriggerReuse; // 0x58
	private static DelegateBridge __Hotfix0_TriggerStart; // 0x60
	private static DelegateBridge __Hotfix0_TriggerStop; // 0x68
	private static DelegateBridge __Hotfix0_TriggerRecycle; // 0x70
	private static DelegateBridge __Hotfix0_TriggerRouted; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x2150068 VA: 0x7594768068
	public UIPage GetPage() { }
	// RVA: 0x2150140 VA: 0x7594768140
	protected virtual Void OnAwake() { }
	// RVA: 0x21501a4 VA: 0x75947681a4
	protected virtual Void OnCreate() { }
	// RVA: 0x2150208 VA: 0x7594768208
	protected virtual Void OnReuse() { }
	// RVA: 0x215026c VA: 0x759476826c
	protected virtual Void OnStart() { }
	// RVA: 0x21502d0 VA: 0x75947682d0
	protected virtual Void OnPageRouted() { }
	// RVA: 0x2150334 VA: 0x7594768334
	protected virtual Void OnStop() { }
	// RVA: 0x2150398 VA: 0x7594768398
	protected virtual Void OnRecycle() { }
	// RVA: 0x21503fc VA: 0x75947683fc
	protected virtual Void OnDestroy() { }
	// RVA: 0x2150460 VA: 0x7594768460
	private Void Awake() { }
	// RVA: 0x2150980 VA: 0x7594768980
	public Void TriggerCreate() { }
	// RVA: 0x21509f0 VA: 0x75947689f0
	public Void TriggerReuse() { }
	// RVA: 0x2150a60 VA: 0x7594768a60
	public Void TriggerStart() { }
	// RVA: 0x2150ad0 VA: 0x7594768ad0
	public Void TriggerStop() { }
	// RVA: 0x2150b40 VA: 0x7594768b40
	public Void TriggerRecycle() { }
	// RVA: 0x2150bb0 VA: 0x7594768bb0
	public Void TriggerRouted() { }
	// RVA: 0x2150c20 VA: 0x7594768c20
	public Void .ctor() { }
}
```