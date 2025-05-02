# ClimbTowerMenuAdapter

**Namespace:** `Torappu.UI.ClimbTower`


## Methods

- `Void NotifyAdapterChanged(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerMenuAdapter : IHotfixable
{
	public Action`1 observer; // 0x10
	private static DelegateBridge __Hotfix0_get_showMenu; // 0x0
	private static DelegateBridge __Hotfix0_get_preferredMenuShowType; // 0x8
	private static DelegateBridge __Hotfix0_get_hideBuffBtnWithHolder; // 0x10
	private static DelegateBridge __Hotfix0_get_showTrapBtn; // 0x18
	private static DelegateBridge __Hotfix0_get_showSquadBtn; // 0x20
	private static DelegateBridge __Hotfix0_get_trapBtnState; // 0x28
	private static DelegateBridge __Hotfix0_get_squadBtnState; // 0x30
	private static DelegateBridge __Hotfix0_get_showProfessionBtns; // 0x38
	private static DelegateBridge __Hotfix0_get_overrideGetProfessionCharCount; // 0x40
	private static DelegateBridge __Hotfix0_get_onProfessionClickedCallback; // 0x48
	private static DelegateBridge __Hotfix0_get_buttonPrefab; // 0x50
	private static DelegateBridge __Hotfix0_get_buttonDataSource; // 0x58
	private static DelegateBridge __Hotfix0_get_buttonCallback; // 0x60
	private static DelegateBridge __Hotfix0_get_showEffect; // 0x68
	private static DelegateBridge __Hotfix0_NotifyAdapterChanged; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public virtual Boolean showMenu { get; }
	public virtual TweenType preferredMenuShowType { get; }
	public virtual Boolean hideBuffBtnWithHolder { get; }
	public virtual Boolean showTrapBtn { get; }
	public virtual Boolean showSquadBtn { get; }
	public virtual ButtonState trapBtnState { get; }
	public virtual ButtonState squadBtnState { get; }
	public virtual Boolean showProfessionBtns { get; }
	public virtual GetProfessionCharCount overrideGetProfessionCharCount { get; }
	public virtual Action`1 onProfessionClickedCallback { get; }
	public virtual ClimbTowerMenuButton buttonPrefab { get; }
	public virtual IClimbTowerMenuButtonDataSource buttonDataSource { get; }
	public virtual Action buttonCallback { get; }
	public virtual Boolean showEffect { get; }

	// RVA: 0x2c811b8 VA: 0x75952991b8
	public virtual Boolean get_showMenu() { }
	// RVA: 0x2c8121c VA: 0x759529921c
	public virtual TweenType get_preferredMenuShowType() { }
	// RVA: 0x2c81284 VA: 0x7595299284
	public virtual Boolean get_hideBuffBtnWithHolder() { }
	// RVA: 0x2c812e8 VA: 0x75952992e8
	public virtual Boolean get_showTrapBtn() { }
	// RVA: 0x2c81350 VA: 0x7595299350
	public virtual Boolean get_showSquadBtn() { }
	// RVA: 0x2c813b8 VA: 0x75952993b8
	public virtual ButtonState get_trapBtnState() { }
	// RVA: 0x2c8141c VA: 0x759529941c
	public virtual ButtonState get_squadBtnState() { }
	// RVA: 0x2c81480 VA: 0x7595299480
	public virtual Boolean get_showProfessionBtns() { }
	// RVA: 0x2c814e8 VA: 0x75952994e8
	public virtual GetProfessionCharCount get_overrideGetProfessionCharCount() { }
	// RVA: 0x2c8154c VA: 0x759529954c
	public virtual Action`1 get_onProfessionClickedCallback() { }
	// RVA: 0x2c815b0 VA: 0x75952995b0
	public virtual ClimbTowerMenuButton get_buttonPrefab() { }
	// RVA: 0x2c81614 VA: 0x7595299614
	public virtual IClimbTowerMenuButtonDataSource get_buttonDataSource() { }
	// RVA: 0x2c81678 VA: 0x7595299678
	public virtual Action get_buttonCallback() { }
	// RVA: 0x2c816dc VA: 0x75952996dc
	public virtual Boolean get_showEffect() { }
	// RVA: 0x2c81744 VA: 0x7595299744
	public Void NotifyAdapterChanged(Boolean fastMode) { }
	// RVA: 0x2c817e4 VA: 0x75952997e4
	public Void .ctor() { }
}
```