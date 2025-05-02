# ActMultiV3InverseToggleView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `UIAnimationLocation _animSwitch`

- `TwoStateToggle _inverseUnlockState`

- `GameObject _newTrackGO`

- `Action <onToggleClick>k__BackingField`

- `AnimationSwitchTween m_switchTween`


## Properties

- `Action onToggleClick`


## Methods

- `Action get_onToggleClick()`

- `Void set_onToggleClick(Action)`

- `Void Render(Boolean, Boolean, Boolean)`

- `Void EventOnToggleClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3InverseToggleView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _animSwitch; // 0x18
	private TwoStateToggle _inverseUnlockState; // 0x28
	private GameObject _newTrackGO; // 0x30
	private Action <onToggleClick>k__BackingField; // 0x38
	private AnimationSwitchTween m_switchTween; // 0x40
	private static DelegateBridge __Hotfix0_get_onToggleClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onToggleClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnToggleClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action onToggleClick { get; set; }

	// RVA: 0x30e3d08 VA: 0x75956fbd08
	private Action get_onToggleClick() { }
	// RVA: 0x30e3d70 VA: 0x75956fbd70
	public Void set_onToggleClick(Action value) { }
	// RVA: 0x30e3df4 VA: 0x75956fbdf4
	public Void Render(Boolean isInverseSelect, Boolean isInverseUnlock, Boolean showNewTrack) { }
	// RVA: 0x30e3f44 VA: 0x75956fbf44
	public Void EventOnToggleClick() { }
	// RVA: 0x30e3fe0 VA: 0x75956fbfe0
	public Void .ctor() { }
}
```