# ActMultiV3PrepareMainSquadPanelReserveCharCard

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `ActMultiV3PrepareMainSmallCharCard _cardPrefab`

- `Transform _container`

- `UIAnimationLocation _animInOut`

- `AnimationSwitchTween m_animSwitch`

- `ActMultiV3PrepareMainSmallCharCard m_charCard`


## Methods

- `Void set_onClick(Action`1)`

- `Void Render(ActMultiV3PrepareMainSquadPanelReserveCharCardModel, Boolean)`

- `Void _InitIfNot(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainSquadPanelReserveCharCard : MonoBehaviour, IHotfixable
{
	private ActMultiV3PrepareMainSmallCharCard _cardPrefab; // 0x18
	private Transform _container; // 0x20
	private UIAnimationLocation _animInOut; // 0x28
	private AnimationSwitchTween m_animSwitch; // 0x38
	private ActMultiV3PrepareMainSmallCharCard m_charCard; // 0x40
	private Action`1 <onClick>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_onClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onClick { get; set; }

	// RVA: 0x31762d0 VA: 0x759578e2d0
	private Action`1 get_onClick() { }
	// RVA: 0x31755dc VA: 0x759578d5dc
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x3175660 VA: 0x759578d660
	public Void Render(ActMultiV3PrepareMainSquadPanelReserveCharCardModel model, Boolean isPlayAudio) { }
	// RVA: 0x3176338 VA: 0x759578e338
	private Void _InitIfNot(Boolean initVisible) { }
	// RVA: 0x31764b0 VA: 0x759578e4b0
	public Void .ctor() { }
}
```