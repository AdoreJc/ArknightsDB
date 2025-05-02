# BossHudTrap

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _useNormalHud`

- `Vector3 _hudOffset`

- `Vector3 _hudScale`

- `Vector2 _avatarOffset`

- `Vector2 _avatarSize`

- `Boolean _hideAvatarBackground`

- `Boolean _enableSpSliderWarning`

- `Single _hudDelayToAppear`

- `Boolean _hideHpSlider`

- `GiantBossInfoType _giantBossInfoType`


## Properties

- `Vector2 bossHudOffset`

- `Vector3 bossHudScale`

- `Vector2 bossAvatarOffset`

- `Vector2 bossAvatarSize`

- `Boolean hideAvatarBackground`

- `Boolean enableSpSliderWarning`

- `Boolean lockHudPosition`

- `Single hudDelayToAppear`

- `Boolean hideHpSlider`

- `GiantBossInfoType giantBossInfoType`

- `Boolean isSkillAffecting`

- `Boolean isSpCostSkill`

- `FP skillRemainingProgress`

- `Boolean useNormalHud`


## Methods

- `Vector2 get_bossHudOffset()`

- `Vector3 get_bossHudScale()`

- `Vector2 get_bossAvatarOffset()`

- `Vector2 get_bossAvatarSize()`

- `Boolean get_hideAvatarBackground()`

- `Boolean get_enableSpSliderWarning()`

- `Boolean get_lockHudPosition()`

- `Single get_hudDelayToAppear()`

- `Boolean get_hideHpSlider()`

- `GiantBossInfoType get_giantBossInfoType()`

- `Boolean get_isSkillAffecting()`

- `Boolean get_isSpCostSkill()`

- `FP get_skillRemainingProgress()`

- `Boolean get_useNormalHud()`

- `Void set_actionOnTakeDamage(Action`1)`

- `Void <>xLuaBaseProxy_OnTakeDamage(ref, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BossHudTrap : Trap, IUseGiantBossInfoPanel, IPtrObject
{
	private Boolean _useNormalHud; // 0x4f1
	private Vector3 _hudOffset; // 0x4f4
	private Vector3 _hudScale; // 0x500
	private Vector2 _avatarOffset; // 0x50c
	private Vector2 _avatarSize; // 0x514
	private Boolean _hideAvatarBackground; // 0x51c
	private Boolean _enableSpSliderWarning; // 0x51d
	private Single _hudDelayToAppear; // 0x520
	private Boolean _hideHpSlider; // 0x524
	private GiantBossInfoType _giantBossInfoType; // 0x528
	private Action`1 <actionOnTakeDamage>k__BackingField; // 0x530
	private static DelegateBridge __Hotfix0_get_bossHudOffset; // 0x0
	private static DelegateBridge __Hotfix0_get_bossHudScale; // 0x8
	private static DelegateBridge __Hotfix0_get_bossAvatarOffset; // 0x10
	private static DelegateBridge __Hotfix0_get_bossAvatarSize; // 0x18
	private static DelegateBridge __Hotfix0_get_hideAvatarBackground; // 0x20
	private static DelegateBridge __Hotfix0_get_enableSpSliderWarning; // 0x28
	private static DelegateBridge __Hotfix0_get_lockHudPosition; // 0x30
	private static DelegateBridge __Hotfix0_get_hudDelayToAppear; // 0x38
	private static DelegateBridge __Hotfix0_get_hideHpSlider; // 0x40
	private static DelegateBridge __Hotfix0_get_giantBossInfoType; // 0x48
	private static DelegateBridge __Hotfix0_get_isSkillAffecting; // 0x50
	private static DelegateBridge __Hotfix0_get_isSpCostSkill; // 0x58
	private static DelegateBridge __Hotfix0_get_skillRemainingProgress; // 0x60
	private static DelegateBridge __Hotfix0_get_useNormalHud; // 0x68
	private static DelegateBridge __Hotfix0_get_actionOnTakeDamage; // 0x70
	private static DelegateBridge __Hotfix0_set_actionOnTakeDamage; // 0x78
	private static DelegateBridge __Hotfix0_OnTakeDamage; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public Vector2 bossHudOffset { get; }
	public Vector3 bossHudScale { get; }
	public Vector2 bossAvatarOffset { get; }
	public Vector2 bossAvatarSize { get; }
	public Boolean hideAvatarBackground { get; }
	public Boolean enableSpSliderWarning { get; }
	public Boolean lockHudPosition { get; }
	public Single hudDelayToAppear { get; }
	public Boolean hideHpSlider { get; }
	public GiantBossInfoType giantBossInfoType { get; }
	public Boolean isSkillAffecting { get; }
	public Boolean isSpCostSkill { get; }
	public FP skillRemainingProgress { get; }
	public Boolean useNormalHud { get; }
	public Action`1 actionOnTakeDamage { get; set; }

	// RVA: 0x1bdf3c4 VA: 0x75941f73c4
	public Vector2 get_bossHudOffset() { }
	// RVA: 0x1bdf42c VA: 0x75941f742c
	public Vector3 get_bossHudScale() { }
	// RVA: 0x1bdf498 VA: 0x75941f7498
	public Vector2 get_bossAvatarOffset() { }
	// RVA: 0x1bdf500 VA: 0x75941f7500
	public Vector2 get_bossAvatarSize() { }
	// RVA: 0x1bdf568 VA: 0x75941f7568
	public Boolean get_hideAvatarBackground() { }
	// RVA: 0x1bdf5d0 VA: 0x75941f75d0
	public Boolean get_enableSpSliderWarning() { }
	// RVA: 0x1bdf638 VA: 0x75941f7638
	public Boolean get_lockHudPosition() { }
	// RVA: 0x1bdf6a0 VA: 0x75941f76a0
	public Single get_hudDelayToAppear() { }
	// RVA: 0x1bdf708 VA: 0x75941f7708
	public Boolean get_hideHpSlider() { }
	// RVA: 0x1bdf770 VA: 0x75941f7770
	public GiantBossInfoType get_giantBossInfoType() { }
	// RVA: 0x1bdf7d8 VA: 0x75941f77d8
	public Boolean get_isSkillAffecting() { }
	// RVA: 0x1bdf934 VA: 0x75941f7934
	public Boolean get_isSpCostSkill() { }
	// RVA: 0x1bdfa10 VA: 0x75941f7a10
	public FP get_skillRemainingProgress() { }
	// RVA: 0x1bdfa90 VA: 0x75941f7a90
	public Boolean get_useNormalHud() { }
	// RVA: 0x1bdfaf8 VA: 0x75941f7af8
	public Action`1 get_actionOnTakeDamage() { }
	// RVA: 0x1bdfb60 VA: 0x75941f7b60
	public Void set_actionOnTakeDamage(Action`1 value) { }
	// RVA: 0x1bdfbe4 VA: 0x75941f7be4
	protected override Void OnTakeDamage(ref Modifier modifier, Boolean force) { }
	// RVA: 0x1bdfcec VA: 0x75941f7cec
	public Void .ctor() { }
	// RVA: 0x1bdfe2c VA: 0x75941f7e2c
	private Void <>xLuaBaseProxy_OnTakeDamage(ref Modifier P0, Boolean P1) { }
}
```