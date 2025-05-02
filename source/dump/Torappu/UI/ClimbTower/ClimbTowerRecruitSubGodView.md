# ClimbTowerRecruitSubGodView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Text _textTowerInfo`

- `Text _textMainCardInfo`

- `SimpleLayoutContent _subCardList`

- `UIAnimationLocation _animBtnConfirm`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `AnimationSwitchTween m_btnConfirmTween`

- `ClimbTowerRecruitSubGodModel m_recruitModel`


## Methods

- `Void set_onItemSelected(Action`1)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerRecruitSubGodView : DataBinder`1
{
	private Text _textTowerInfo; // 0x20
	private Text _textMainCardInfo; // 0x28
	private SimpleLayoutContent _subCardList; // 0x30
	private UIAnimationLocation _animBtnConfirm; // 0x38
	private Boolean m_hasInited; // 0x48
	private Adapter m_adapter; // 0x50
	private AnimationSwitchTween m_btnConfirmTween; // 0x58
	private ClimbTowerRecruitSubGodModel m_recruitModel; // 0x60
	private Action`1 <onItemSelected>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_onItemSelected; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemSelected; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onItemSelected { get; set; }

	// RVA: 0x2cadfc8 VA: 0x75952c5fc8
	private Action`1 get_onItemSelected() { }
	// RVA: 0x2cad14c VA: 0x75952c514c
	public Void set_onItemSelected(Action`1 value) { }
	// RVA: 0x2cae030 VA: 0x75952c6030
	public override Void OnValueChanged(ClimbTowerRecruitSubGodProp property) { }
	// RVA: 0x2cae1f0 VA: 0x75952c61f0
	private Void _InitIfNot() { }
	// RVA: 0x2cae3c4 VA: 0x75952c63c4
	public Void .ctor() { }
}
```