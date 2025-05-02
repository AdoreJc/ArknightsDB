# BossRushPlugin

**Namespace:** `Torappu.Activity.Act1BossRush.Battle.UI`


## Fields

- `BossRushHintPanel _bossRushHintPanel`

- `BossRushTopbarStatus _bossRushTopbarStatus`


## Methods

- `Void <>xLuaBaseProxy_OnGameInit(Options)`

- `Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine)`

- `Void <>xLuaBaseProxy_OnGameReady()`

- `Void <>xLuaBaseProxy_OnGameStart()`

- `Void <>xLuaBaseProxy_UpdateGameInfo()`

- `Boolean <>xLuaBaseProxy_CanPressBackButton()`

- `Boolean <>xLuaBaseProxy_HookBattleSystemMenuSwitch()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush.Battle.UI
public class BossRushPlugin : Plugin
{
	private BossRushHintPanel _bossRushHintPanel; // 0x28
	private BossRushTopbarStatus _bossRushTopbarStatus; // 0x30
	private UIStateNode[] _states; // 0x38
	public static readonly Event ON_HINT_DANGER_AREA; // 0x0
	public static readonly Event ON_NEXT_BOSS_WAVE_WILL_START; // 0x4
	public static readonly Event ON_START_MOVE_CAMERA; // 0x8
	public static readonly Event ON_BONUS_WAVE_FINISH; // 0xc
	public static readonly UIStateEnum ON_BOSS_WAVE_START_STATE; // 0x10
	public static readonly UIStateEnum ON_MOVE_CAMERA_STATE; // 0x14
	public static readonly UIStateEnum ON_BOSSRUSH_SYSTEM_MENU; // 0x18
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x20
	private static DelegateBridge __Hotfix0_OnInitStateMachine; // 0x28
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x30
	private static DelegateBridge __Hotfix0_OnGameStart; // 0x38
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x40
	private static DelegateBridge __Hotfix0_CanPressBackButton; // 0x48
	private static DelegateBridge __Hotfix0_HookBattleSystemMenuSwitch; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x3196624 VA: 0x75957ae624
	public override Void OnGameInit(Options levelOptions) { }
	// RVA: 0x3196964 VA: 0x75957ae964
	public override Void OnInitStateMachine(UIStateMachine stateMachine) { }
	// RVA: 0x3196aa8 VA: 0x75957aeaa8
	public override Void OnGameReady() { }
	// RVA: 0x3196b60 VA: 0x75957aeb60
	public override Void OnGameStart() { }
	// RVA: 0x3196c44 VA: 0x75957aec44
	public override Void UpdateGameInfo() { }
	// RVA: 0x3196dc8 VA: 0x75957aedc8
	public override Boolean CanPressBackButton() { }
	// RVA: 0x3196f30 VA: 0x75957aef30
	public override Boolean HookBattleSystemMenuSwitch() { }
	// RVA: 0x319701c VA: 0x75957af01c
	public Void .ctor() { }
	// RVA: 0x31970d8 VA: 0x75957af0d8
	private static Void .cctor() { }
	// RVA: 0x319713c VA: 0x75957af13c
	private Void <>xLuaBaseProxy_OnGameInit(Options P0) { }
	// RVA: 0x3197144 VA: 0x75957af144
	private Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine P0) { }
	// RVA: 0x319714c VA: 0x75957af14c
	private Void <>xLuaBaseProxy_OnGameReady() { }
	// RVA: 0x3197154 VA: 0x75957af154
	private Void <>xLuaBaseProxy_OnGameStart() { }
	// RVA: 0x319715c VA: 0x75957af15c
	private Void <>xLuaBaseProxy_UpdateGameInfo() { }
	// RVA: 0x3197164 VA: 0x75957af164
	private Boolean <>xLuaBaseProxy_CanPressBackButton() { }
	// RVA: 0x319716c VA: 0x75957af16c
	private Boolean <>xLuaBaseProxy_HookBattleSystemMenuSwitch() { }
}
```