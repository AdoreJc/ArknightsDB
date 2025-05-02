# Act6FunMainEnemyHudPlugin

**Namespace:** `Torappu.Battle.UI`


## Fields

- `MountPointType _followMountPoint`

- `UIFollower _uiFollower`

- `AnimationWrapper _animWrapper`

- `String _animName`

- `CanvasGroup _defaultMarkCanvasGroup`

- `CanvasGroup _inCombatMarkCanvasGroup`

- `Boolean m_cachedIsInCombat`

- `FadeSwitchTween m_defaultMarkFadeTween`

- `FadeSwitchTween m_inCombatMarkFadeTween`


## Methods

- `Void Update()`

- `Void _UpdateBlockedState()`

- `Void _ToggleInCombatMark()`

- `Void <>xLuaBaseProxy_DoAttach(Unit, UIPluginTalent)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class Act6FunMainEnemyHudPlugin : UnitTalentUIPlugin
{
	private MountPointType _followMountPoint; // 0x30
	private UIFollower _uiFollower; // 0x38
	private AnimationWrapper _animWrapper; // 0x40
	private String _animName; // 0x48
	private CanvasGroup _defaultMarkCanvasGroup; // 0x50
	private CanvasGroup _inCombatMarkCanvasGroup; // 0x58
	private Boolean m_cachedIsInCombat; // 0x60
	private FadeSwitchTween m_defaultMarkFadeTween; // 0x68
	private FadeSwitchTween m_inCombatMarkFadeTween; // 0x70
	private static DelegateBridge __Hotfix0_DoAttach; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0__UpdateBlockedState; // 0x10
	private static DelegateBridge __Hotfix0__ToggleInCombatMark; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2018f1c VA: 0x7594630f1c
	protected override Void DoAttach(Unit owner, UIPluginTalent talent) { }
	// RVA: 0x2019270 VA: 0x7594631270
	private Void Update() { }
	// RVA: 0x20192d8 VA: 0x75946312d8
	private Void _UpdateBlockedState() { }
	// RVA: 0x201911c VA: 0x759463111c
	private Void _ToggleInCombatMark() { }
	// RVA: 0x2019454 VA: 0x7594631454
	public Void .ctor() { }
	// RVA: 0x20194c4 VA: 0x75946314c4
	private Void <>xLuaBaseProxy_DoAttach(Unit P0, UIPluginTalent P1) { }
}
```