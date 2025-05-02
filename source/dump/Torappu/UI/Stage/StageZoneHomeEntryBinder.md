# StageZoneHomeEntryBinder

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageZoneHomeEntryLayout _entryLayout`


## Methods

- `Void set_onEntryClicked(Action`1)`

- `Void _OnEntryClicked(ZoneHomeEntryItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeEntryBinder : DataBinder`1, IHotfixable
{
	private StageZoneHomeEntryLayout _entryLayout; // 0x20
	private Action`1 <onEntryClicked>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_onEntryClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onEntryClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__OnEntryClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onEntryClicked { get; set; }

	// RVA: 0x2efc128 VA: 0x7595514128
	private Action`1 get_onEntryClicked() { }
	// RVA: 0x2efc190 VA: 0x7595514190
	public Void set_onEntryClicked(Action`1 value) { }
	// RVA: 0x2efc214 VA: 0x7595514214
	public override Void OnValueChanged(ZoneHomeEntryGroupProp property) { }
	// RVA: 0x2efc3d0 VA: 0x75955143d0
	private Void _OnEntryClicked(ZoneHomeEntryItemModel viewModel) { }
	// RVA: 0x2efc488 VA: 0x7595514488
	public Void .ctor() { }
}
```