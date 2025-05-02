# AutoChessSpellEffectBehaviour

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _battleEffect`

- `GridPosition m_cachedPos`

- `Boolean m_isPlaying`


## Methods

- `Void Update()`

- `Boolean NeedHook()`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class AutoChessSpellEffectBehaviour : Behaviour
{
	private String _battleEffect; // 0x20
	private ObjectPtr`1 m_battleEffect; // 0x28
	private GridPosition m_cachedPos; // 0x38
	private Boolean m_isPlaying; // 0x40
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0_OnFinish; // 0x10
	private static DelegateBridge __Hotfix0_NeedHook; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2009e8c VA: 0x7594621e8c
	public override Void OnPlay() { }
	// RVA: 0x2009f38 VA: 0x7594621f38
	private Void Update() { }
	// RVA: 0x200a408 VA: 0x7594622408
	public override Void OnFinish() { }
	// RVA: 0x200a144 VA: 0x7594622144
	private Boolean NeedHook() { }
	// RVA: 0x200a544 VA: 0x7594622544
	public Void .ctor() { }
	// RVA: 0x200a5e8 VA: 0x75946225e8
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x200a5f0 VA: 0x75946225f0
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```