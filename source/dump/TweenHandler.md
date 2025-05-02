# TweenHandler

**Namespace:** ` `


## Fields

- `Tween m_alphaTweener`

- `Tween m_posTweener`


## Methods

- `Boolean IsPlaying()`

- `Void KillIfNecessary()`

- `ITweenHandler OnComplete(TweenCallback)`

- `ITweenHandler SetAutoKill(Boolean)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
private class TweenHandler : ITweenHandler, IHotfixable
{
	private Tween m_alphaTweener; // 0x10
	private Tween m_posTweener; // 0x18
	private static __XLua_Gen_Delegate87 _c__Hotfix0_ctor; // 0x0
	private static __XLua_Gen_Delegate8 __Hotfix0_IsPlaying; // 0x8
	private static __XLua_Gen_Delegate1 __Hotfix0_KillIfNecessary; // 0x10
	private static __XLua_Gen_Delegate102 __Hotfix0_OnComplete; // 0x18
	private static __XLua_Gen_Delegate103 __Hotfix0_SetAutoKill; // 0x20


	// RVA: 0x678ba64 VA: 0x7598da3a64
	public Void .ctor(Tween alpha, Tween pos) { }
	// RVA: 0x678be68 VA: 0x7598da3e68
	public Boolean IsPlaying() { }
	// RVA: 0x678befc VA: 0x7598da3efc
	public Void KillIfNecessary() { }
	// RVA: 0x678bfb0 VA: 0x7598da3fb0
	public ITweenHandler OnComplete(TweenCallback callback) { }
	// RVA: 0x678c058 VA: 0x7598da4058
	public ITweenHandler SetAutoKill(Boolean autoKill) { }
}
```