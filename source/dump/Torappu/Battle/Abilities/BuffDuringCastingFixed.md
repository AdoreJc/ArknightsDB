# BuffDuringCastingFixed

**Namespace:** `Torappu.Battle.Abilities`


## Methods

- `Void GatherEffects(List`1)`

- `Void GatherBuffs(List`1)`

- `Void _ClearBuffs()`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastFinish(FinishReason)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BuffDuringCastingFixed : Behaviour, IEffectSource, IBuffSource
{
	private BuffData[] _buffs; // 0x20
	private List`1 m_buffUid; // 0x28
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x0
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x18
	private static DelegateBridge __Hotfix0__ClearBuffs; // 0x20
	private static DelegateBridge __Hotfix0_OnEvent; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1ebd608 VA: 0x75944d5608
	public override Void OnCastStart() { }
	// RVA: 0x1ebd85c VA: 0x75944d585c
	public override Void OnCastFinish(FinishReason reason) { }
	// RVA: 0x1ebd8e8 VA: 0x75944d58e8
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ebd96c VA: 0x75944d596c
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1ebd76c VA: 0x75944d576c
	private Void _ClearBuffs() { }
	// RVA: 0x1ebda0c VA: 0x75944d5a0c
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ebdab0 VA: 0x75944d5ab0
	public Void .ctor() { }
	// RVA: 0x1ebdbb0 VA: 0x75944d5bb0
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1ebdbb8 VA: 0x75944d5bb8
	private Void <>xLuaBaseProxy_OnCastFinish(FinishReason P0) { }
	// RVA: 0x1ebdbc0 VA: 0x75944d5bc0
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
}
```