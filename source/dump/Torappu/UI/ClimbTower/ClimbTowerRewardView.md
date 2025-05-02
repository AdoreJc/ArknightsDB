# ClimbTowerRewardView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `GameObject _panelReceiveAll`

- `SimpleLayoutContent _rewardContainer`

- `ClimbTowerRewardConfirmdEvent _onRewardConfirmedEvent`

- `Boolean m_inited`

- `ClimbTowerViewModel m_cachedModel`

- `Adapter m_adapter`


## Methods

- `Void _InitIfNot()`

- `Void OnBtnReceiveAllClicked()`

- `Void _OnBtnReceiveRewardClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerRewardView : DataBinder`1
{
	private GameObject _panelReceiveAll; // 0x20
	private SimpleLayoutContent _rewardContainer; // 0x28
	private ClimbTowerRewardConfirmdEvent _onRewardConfirmedEvent; // 0x30
	private Boolean m_inited; // 0x38
	private ClimbTowerViewModel m_cachedModel; // 0x40
	private Adapter m_adapter; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnBtnReceiveAllClicked; // 0x10
	private static DelegateBridge __Hotfix0__OnBtnReceiveRewardClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2c76be0 VA: 0x759528ebe0
	private Void _InitIfNot() { }
	// RVA: 0x2c76d44 VA: 0x759528ed44
	public override Void OnValueChanged(ClimbTowerProperty property) { }
	// RVA: 0x2c76e54 VA: 0x759528ee54
	public Void OnBtnReceiveAllClicked() { }
	// RVA: 0x2c76ef8 VA: 0x759528eef8
	private Void _OnBtnReceiveRewardClicked(Int32 layerNum) { }
	// RVA: 0x2c77068 VA: 0x759528f068
	public Void .ctor() { }
}
```