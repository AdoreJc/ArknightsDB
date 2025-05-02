# CrisisV2EntryAVGAdapter

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `UIPage <page>k__BackingField`

- `IStateEngine <se>k__BackingField`


## Properties

- `UIPage page`

- `IStateEngine se`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `IStateEngine get_se()`

- `Void set_se(IStateEngine)`

- `Boolean _OnResetToEntry(Command)`

- `IEnumerator _TryRouteToEntryState()`

- `Void OnEnable()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2EntryAVGAdapter : ExecutorComponent, IHotfixable
{
	private UIPage <page>k__BackingField; // 0x50
	private IStateEngine <se>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_get_se; // 0x10
	private static DelegateBridge __Hotfix0_set_se; // 0x18
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x20
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x28
	private static DelegateBridge __Hotfix0__OnResetToEntry; // 0x30
	private static DelegateBridge __Hotfix0__TryRouteToEntryState; // 0x38
	private static DelegateBridge __Hotfix0_OnEnable; // 0x40
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private UIPage page { get; set; }
	private IStateEngine se { get; set; }

	// RVA: 0x2c000f8 VA: 0x75952180f8
	private UIPage get_page() { }
	// RVA: 0x2c00160 VA: 0x7595218160
	public Void set_page(UIPage value) { }
	// RVA: 0x2c001e4 VA: 0x75952181e4
	private IStateEngine get_se() { }
	// RVA: 0x2c0024c VA: 0x759521824c
	public Void set_se(IStateEngine value) { }
	// RVA: 0x2c002d0 VA: 0x75952182d0
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x2c00470 VA: 0x7595218470
	protected override Void ForceCommandEnd() { }
	// RVA: 0x2c004d4 VA: 0x75952184d4
	private Boolean _OnResetToEntry(Command command) { }
	// RVA: 0x2c00724 VA: 0x7595218724
	private IEnumerator _TryRouteToEntryState() { }
	// RVA: 0x2c007f8 VA: 0x75952187f8
	private Void OnEnable() { }
	// RVA: 0x2c008b4 VA: 0x75952188b4
	private Void OnDestroy() { }
	// RVA: 0x2c00970 VA: 0x7595218970
	public Void .ctor() { }
}
```