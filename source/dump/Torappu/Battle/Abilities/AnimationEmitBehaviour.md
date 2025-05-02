# AnimationEmitBehaviour

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _hookAbilityAnim`

- `AbstractAnimatedAbility m_animatedAbility`


## Methods

- `Void _DealWithDirection(AnimationSetting)`

- `Void _DoPlayAnimation(AnimationSetting)`

- `String _HookAnimationIfNot(String)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnCastStart()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AnimationEmitBehaviour : Behaviour
{
	private AnimationSetting[] _settings; // 0x20
	private BuffAnimationHookSetting[] _hookSettings; // 0x28
	private Boolean _hookAbilityAnim; // 0x30
	private AbstractAnimatedAbility m_animatedAbility; // 0x38
	private static DelegateBridge __Hotfix0_OnEvent; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x10
	private static DelegateBridge __Hotfix0__DealWithDirection; // 0x18
	private static DelegateBridge __Hotfix0__DoPlayAnimation; // 0x20
	private static DelegateBridge __Hotfix0__HookAnimationIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1eb89e8 VA: 0x75944d09e8
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1eb8cd4 VA: 0x75944d0cd4
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1eb8df4 VA: 0x75944d0df4
	public override Void OnCastStart() { }
	// RVA: 0x1eb8fec VA: 0x75944d0fec
	private Void _DealWithDirection(AnimationSetting setting) { }
	// RVA: 0x1eb8bb8 VA: 0x75944d0bb8
	private Void _DoPlayAnimation(AnimationSetting setting) { }
	// RVA: 0x1eb9160 VA: 0x75944d1160
	private String _HookAnimationIfNot(String fromAnimKey) { }
	// RVA: 0x1eb9270 VA: 0x75944d1270
	public Void .ctor() { }
	// RVA: 0x1eb92e0 VA: 0x75944d12e0
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
	// RVA: 0x1eb92e8 VA: 0x75944d12e8
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1eb92f0 VA: 0x75944d12f0
	private Void <>xLuaBaseProxy_OnCastStart() { }
}
```