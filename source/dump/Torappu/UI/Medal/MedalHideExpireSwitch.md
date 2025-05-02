# MedalHideExpireSwitch

**Namespace:** `Torappu.UI.Medal`


## Fields

- `TwoStateToggle _toggle`

- `Action <onToggleClicked>k__BackingField`


## Properties

- `Action onToggleClicked`


## Methods

- `Action get_onToggleClicked()`

- `Void set_onToggleClicked(Action)`

- `Void Render(MedalListViewModel)`

- `Void EventOnToggleClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalHideExpireSwitch : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _toggle; // 0x18
	private Action <onToggleClicked>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_get_onToggleClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onToggleClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnToggleClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action onToggleClicked { get; set; }

	// RVA: 0x27a8e0c VA: 0x7594dc0e0c
	private Action get_onToggleClicked() { }
	// RVA: 0x27a8e74 VA: 0x7594dc0e74
	public Void set_onToggleClicked(Action value) { }
	// RVA: 0x27a8ef8 VA: 0x7594dc0ef8
	public Void Render(MedalListViewModel viewModel) { }
	// RVA: 0x27a8f98 VA: 0x7594dc0f98
	public Void EventOnToggleClicked() { }
	// RVA: 0x27a9034 VA: 0x7594dc1034
	public Void .ctor() { }
}
```