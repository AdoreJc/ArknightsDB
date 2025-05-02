# CammouTrait

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Single _initAtkScale`

- `Single _deltaAtkScale`

- `Single _maxAtkScale`

- `Int32 _maxStack`

- `Single m_curAtkScale`

- `Single m_initAtkScale`

- `Single m_deltaAtkScale`

- `Single m_maxAtkScale`

- `Single m_maxStack`

- `Int32 m_curStack`


## Methods

- `Single SetFunnelAtkScale(Entity)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class CammouTrait : PassiveBuffAbility
{
	private Single _initAtkScale; // 0x110
	private Single _deltaAtkScale; // 0x114
	private Single _maxAtkScale; // 0x118
	private Int32 _maxStack; // 0x11c
	private Single m_curAtkScale; // 0x120
	private Single m_initAtkScale; // 0x124
	private Single m_deltaAtkScale; // 0x128
	private Single m_maxAtkScale; // 0x12c
	private Single m_maxStack; // 0x130
	private Int32 m_curStack; // 0x134
	private ObjectPtr`1 m_lastTarget; // 0x138
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_SetFunnelAtkScale; // 0x8
	private static DelegateBridge __Hotfix0_Reset; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1e6f5c0 VA: 0x75944875c0
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e6f7a0 VA: 0x75944877a0
	public Single SetFunnelAtkScale(Entity target) { }
	// RVA: 0x1e6f94c VA: 0x759448794c
	protected override Void Reset() { }
	// RVA: 0x1e6f9f4 VA: 0x75944879f4
	public Void .ctor() { }
	// RVA: 0x1e6faa4 VA: 0x7594487aa4
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e6facc VA: 0x7594487acc
	private Void <>xLuaBaseProxy_Reset() { }
}
```