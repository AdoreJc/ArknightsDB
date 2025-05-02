# TweenWrapper

**Namespace:** ` `


## Fields

- `Tween m_tween`


## Methods

- `Boolean IsActive()`

- `Boolean IsPlaying()`

- `Void KillIfNecessary()`

- `ITweenHandler OnComplete(TweenCallback)`

- `ITweenHandler SetAutoKill(Boolean)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
public class TweenWrapper : ITweenHandler, IHotfixable
{
	private Tween m_tween; // 0x10
	private static __XLua_Gen_Delegate0 _c__Hotfix0_ctor; // 0x0
	private static __XLua_Gen_Delegate8 __Hotfix0_IsActive; // 0x8
	private static __XLua_Gen_Delegate8 __Hotfix0_IsPlaying; // 0x10
	private static __XLua_Gen_Delegate1 __Hotfix0_KillIfNecessary; // 0x18
	private static __XLua_Gen_Delegate102 __Hotfix0_OnComplete; // 0x20
	private static __XLua_Gen_Delegate103 __Hotfix0_SetAutoKill; // 0x28


	// RVA: 0x678a3e4 VA: 0x7598da23e4
	public Void .ctor(Tween tween) { }
	// RVA: 0x678a480 VA: 0x7598da2480
	public Boolean IsActive() { }
	// RVA: 0x678a4f4 VA: 0x7598da24f4
	public Boolean IsPlaying() { }
	// RVA: 0x678a568 VA: 0x7598da2568
	public Void KillIfNecessary() { }
	// RVA: 0x678a5fc VA: 0x7598da25fc
	public ITweenHandler OnComplete(TweenCallback callback) { }
	// RVA: 0x678a6a4 VA: 0x7598da26a4
	public ITweenHandler SetAutoKill(Boolean autoKill) { }
}
```