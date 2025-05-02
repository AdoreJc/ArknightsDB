# BuildingFloatArchSwitchView

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `Animator _switchAnimator`

- `Boolean m_isSwitchOn`


## Methods

- `Void UpdateSwitch(Boolean)`

- `Void OnEnable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatArchSwitchView : MonoBehaviour, IHotfixable
{
	private const String BUTTON_SWITCH_ON; // 0x0
	private Animator _switchAnimator; // 0x18
	private Boolean m_isSwitchOn; // 0x20
	private static DelegateBridge __Hotfix0_UpdateSwitch; // 0x0
	private static DelegateBridge __Hotfix0_OnEnable; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3e2c348 VA: 0x7596444348
	public Void UpdateSwitch(Boolean isActive) { }
	// RVA: 0x3e2c418 VA: 0x7596444418
	private Void OnEnable() { }
	// RVA: 0x3e2c4a8 VA: 0x75964444a8
	public Void .ctor() { }
}
```