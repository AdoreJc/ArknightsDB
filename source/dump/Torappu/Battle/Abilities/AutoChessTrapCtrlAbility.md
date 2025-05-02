# AutoChessTrapCtrlAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _roundStartIdleAnim`

- `String _roundStartAnim`

- `String _roundEndIdleAnim`

- `String _roundEndAnim`

- `String _initShopStateAnim`

- `String _initBattleStateAnim`

- `String _planeAnim`

- `CoroutineId m_coroutine`


## Methods

- `Void _OnAutoChessExitShop(Object)`

- `Void _OnAutoChessRoundFinished(Object)`

- `Void _OnPlaneAnim(Object)`

- `Void _DoPlayAnim(String, String)`

- `Boolean _PlayAnimationInternal(String)`

- `Void _PlaySignal(String)`

- `Void _PreloadSignal(Action`2, String)`

- `Void <>xLuaBaseProxy_Reset()`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String, String, Action`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AutoChessTrapCtrlAbility : AbilityStandard
{
	private String _roundStartIdleAnim; // 0x108
	private String _roundStartAnim; // 0x110
	private String _roundEndIdleAnim; // 0x118
	private String _roundEndAnim; // 0x120
	private String _initShopStateAnim; // 0x128
	private String _initBattleStateAnim; // 0x130
	private String _planeAnim; // 0x138
	private CoroutineId m_coroutine; // 0x140
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x0
	private static DelegateBridge __Hotfix0_get_category; // 0x8
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x10
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x18
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x20
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x28
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x30
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x38
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x40
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x48
	private static DelegateBridge __Hotfix0_Reset; // 0x50
	private static DelegateBridge __Hotfix0_DoAttach; // 0x58
	private static DelegateBridge __Hotfix0_DoDetach; // 0x60
	private static DelegateBridge __Hotfix0__OnAutoChessExitShop; // 0x68
	private static DelegateBridge __Hotfix0__OnAutoChessRoundFinished; // 0x70
	private static DelegateBridge __Hotfix0__OnPlaneAnim; // 0x78
	private static DelegateBridge __Hotfix0__DoPlayAnim; // 0x80
	private static DelegateBridge __Hotfix0__PlayAnimationInternal; // 0x88
	private static DelegateBridge __Hotfix0__PlaySignal; // 0x90
	private static DelegateBridge __Hotfix0_PreloadSpecialAudioSignals; // 0x98
	private static DelegateBridge __Hotfix0__PreloadSignal; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public override FP cooldown { get; }
	public override Category category { get; }
	public override SelectTargetSource selectTargetSource { get; }
	protected override Boolean alwaysIncludeTarget { get; }

	// RVA: 0x1e67170 VA: 0x759447f170
	public override FP get_cooldown() { }
	// RVA: 0x1e67200 VA: 0x759447f200
	public override Category get_category() { }
	// RVA: 0x1e67268 VA: 0x759447f268
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e672cc VA: 0x759447f2cc
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e67330 VA: 0x759447f330
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e673a8 VA: 0x759447f3a8
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e6746c VA: 0x759447f46c
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e67530 VA: 0x759447f530
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e67594 VA: 0x759447f594
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e675f8 VA: 0x759447f5f8
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e67678 VA: 0x759447f678
	protected override Void Reset() { }
	// RVA: 0x1e67780 VA: 0x759447f780
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e67ab4 VA: 0x759447fab4
	protected override Void DoDetach() { }
	// RVA: 0x1e67cd4 VA: 0x759447fcd4
	private Void _OnAutoChessExitShop(Object arg) { }
	// RVA: 0x1e67f84 VA: 0x759447ff84
	private Void _OnAutoChessRoundFinished(Object arg) { }
	// RVA: 0x1e68034 VA: 0x7594480034
	private Void _OnPlaneAnim(Object arg) { }
	// RVA: 0x1e67d84 VA: 0x759447fd84
	protected Void _DoPlayAnim(String startAnim, String idleAnim) { }
	// RVA: 0x1e679e0 VA: 0x759447f9e0
	private Boolean _PlayAnimationInternal(String animName) { }
	// RVA: 0x1e680fc VA: 0x75944800fc
	private Void _PlaySignal(String animName) { }
	// RVA: 0x1e68324 VA: 0x7594480324
	public override Void PreloadSpecialAudioSignals(String abilityId, String tmplId, Action`2 preloader) { }
	// RVA: 0x1e68468 VA: 0x7594480468
	private Void _PreloadSignal(Action`2 preloader, String anim) { }
	// RVA: 0x1e685b0 VA: 0x75944805b0
	public Void .ctor() { }
	// RVA: 0x1e68718 VA: 0x7594480718
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1e68720 VA: 0x7594480720
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e68728 VA: 0x7594480728
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e68730 VA: 0x7594480730
	private Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String P0, String P1, Action`2 P2) { }
}
```