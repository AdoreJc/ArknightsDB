# Token

**Namespace:** `Torappu.Battle`


## Fields

- `SideType _sideType`

- `EntityCategory _category`

- `CardPolicy _cardPolicy`

- `Boolean _alwaysShowHp`

- `Boolean _alwaysHideHp`

- `Boolean _forceUseAllyHud`

- `Boolean _isInfinity`

- `Boolean _ignoreExcludeFromBattle`

- `Boolean _notShowInDeck`

- `Boolean _asRewardCardInLegionMode`

- `Boolean _rechargeOnlyOnce`


## Properties

- `Boolean isEnemySideToken`

- `CardPolicy cardPolicy`

- `Boolean isUnique`

- `Boolean rechargeOnlyOnce`

- `Boolean isInfinity`

- `Boolean ignoreExcludeFromBattle`

- `Boolean notShowInDeck`

- `Boolean asRewardCardInLegionMode`

- `Boolean alwaysShowHp`

- `Boolean alwaysHideHp`

- `Boolean forceUseAllyHud`


## Methods

- `Boolean get_isEnemySideToken()`

- `CardPolicy get_cardPolicy()`

- `Boolean get_isUnique()`

- `Boolean get_rechargeOnlyOnce()`

- `Boolean get_isInfinity()`

- `Boolean get_ignoreExcludeFromBattle()`

- `Boolean get_notShowInDeck()`

- `Boolean get_asRewardCardInLegionMode()`

- `Boolean get_alwaysShowHp()`

- `Boolean get_alwaysHideHp()`

- `Boolean get_forceUseAllyHud()`

- `SideType <>xLuaBaseProxy_get_initSideType()`

- `EntityCategory <>xLuaBaseProxy_get_category()`

- `Boolean <>xLuaBaseProxy_get_allowWithdrawGainCost()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Token : Character
{
	private SideType _sideType; // 0x4a0
	protected EntityCategory _category; // 0x4a4
	private CardPolicy _cardPolicy; // 0x4a8
	private Boolean _alwaysShowHp; // 0x4ac
	private Boolean _alwaysHideHp; // 0x4ad
	private Boolean _forceUseAllyHud; // 0x4ae
	private Boolean _isInfinity; // 0x4af
	private Boolean _ignoreExcludeFromBattle; // 0x4b0
	private Boolean _notShowInDeck; // 0x4b1
	private Boolean _asRewardCardInLegionMode; // 0x4b2
	private Boolean _rechargeOnlyOnce; // 0x4b3
	private static DelegateBridge __Hotfix0_get_isEnemySideToken; // 0x0
	private static DelegateBridge __Hotfix0_get_initSideType; // 0x8
	private static DelegateBridge __Hotfix0_get_category; // 0x10
	private static DelegateBridge __Hotfix0_get_cardPolicy; // 0x18
	private static DelegateBridge __Hotfix0_get_isUnique; // 0x20
	private static DelegateBridge __Hotfix0_get_showHpSlider; // 0x28
	private static DelegateBridge __Hotfix0_get_rechargeOnlyOnce; // 0x30
	private static DelegateBridge __Hotfix0_get_isInfinity; // 0x38
	private static DelegateBridge __Hotfix0_get_ignoreExcludeFromBattle; // 0x40
	private static DelegateBridge __Hotfix0_get_notShowInDeck; // 0x48
	private static DelegateBridge __Hotfix0_get_asRewardCardInLegionMode; // 0x50
	private static DelegateBridge __Hotfix0_get_alwaysShowHp; // 0x58
	private static DelegateBridge __Hotfix0_get_alwaysHideHp; // 0x60
	private static DelegateBridge __Hotfix0_get_forceUseAllyHud; // 0x68
	private static DelegateBridge __Hotfix0_get_allowWithdrawGainCost; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	protected Boolean isEnemySideToken { get; }
	protected override SideType initSideType { get; }
	public override EntityCategory category { get; }
	public CardPolicy cardPolicy { get; }
	public Boolean isUnique { get; }
	public virtual Boolean showHpSlider { get; }
	public Boolean rechargeOnlyOnce { get; }
	public Boolean isInfinity { get; }
	public Boolean ignoreExcludeFromBattle { get; }
	public Boolean notShowInDeck { get; }
	public Boolean asRewardCardInLegionMode { get; }
	public Boolean alwaysShowHp { get; }
	public Boolean alwaysHideHp { get; }
	public Boolean forceUseAllyHud { get; }
	protected override Boolean allowWithdrawGainCost { get; }

	// RVA: 0x1c29838 VA: 0x7594241838
	protected Boolean get_isEnemySideToken() { }
	// RVA: 0x1c298a8 VA: 0x75942418a8
	protected override SideType get_initSideType() { }
	// RVA: 0x1c257d0 VA: 0x759423d7d0
	public override EntityCategory get_category() { }
	// RVA: 0x1c29910 VA: 0x7594241910
	public CardPolicy get_cardPolicy() { }
	// RVA: 0x1c29978 VA: 0x7594241978
	public Boolean get_isUnique() { }
	// RVA: 0x1c299e8 VA: 0x75942419e8
	public virtual Boolean get_showHpSlider() { }
	// RVA: 0x1c29a74 VA: 0x7594241a74
	public Boolean get_rechargeOnlyOnce() { }
	// RVA: 0x1c29adc VA: 0x7594241adc
	public Boolean get_isInfinity() { }
	// RVA: 0x1c29b44 VA: 0x7594241b44
	public Boolean get_ignoreExcludeFromBattle() { }
	// RVA: 0x1c29bac VA: 0x7594241bac
	public Boolean get_notShowInDeck() { }
	// RVA: 0x1c29c14 VA: 0x7594241c14
	public Boolean get_asRewardCardInLegionMode() { }
	// RVA: 0x1c29c7c VA: 0x7594241c7c
	public Boolean get_alwaysShowHp() { }
	// RVA: 0x1c29ce4 VA: 0x7594241ce4
	public Boolean get_alwaysHideHp() { }
	// RVA: 0x1c29dd4 VA: 0x7594241dd4
	public Boolean get_forceUseAllyHud() { }
	// RVA: 0x1c29e3c VA: 0x7594241e3c
	protected override Boolean get_allowWithdrawGainCost() { }
	// RVA: 0x1c29ea0 VA: 0x7594241ea0
	public Void .ctor() { }
	// RVA: 0x1c29f40 VA: 0x7594241f40
	private SideType <>xLuaBaseProxy_get_initSideType() { }
	// RVA: 0x1c29f48 VA: 0x7594241f48
	private EntityCategory <>xLuaBaseProxy_get_category() { }
	// RVA: 0x1c29fb4 VA: 0x7594241fb4
	private Boolean <>xLuaBaseProxy_get_allowWithdrawGainCost() { }
}
```