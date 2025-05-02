# ExtraPassiveBuff

**Namespace:** `Torappu.Battle.Abilities`


## Methods

- `Void GatherBuffs(List`1)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ExtraPassiveBuff : Behaviour, IBuffSource
{
	private BuffData[] _passiveBuffs; // 0x20
	private List`1 m_buffUids; // 0x28
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x0
	private static DelegateBridge __Hotfix0_OnEvent; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1ebfae0 VA: 0x75944d7ae0
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1ebfb80 VA: 0x75944d7b80
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ebfd9c VA: 0x75944d7d9c
	public Void .ctor() { }
	// RVA: 0x1ebfe9c VA: 0x75944d7e9c
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
}
```