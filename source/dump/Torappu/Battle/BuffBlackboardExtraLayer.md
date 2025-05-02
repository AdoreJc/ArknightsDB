# BuffBlackboardExtraLayer

**Namespace:** `Torappu.Battle`


## Fields

- `AnimConfig m_lastConfig`


## Methods

- `Void _TryUpdateNewAnimConfig(Unit)`

- `Boolean _KeepOldAnimState()`

- `Void <>xLuaBaseProxy_Init(SpineMixExtraLayer, ObjectPtr`1)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BuffBlackboardExtraLayer : LayerAnimPlayer
{
	private List`1 _animConfigs; // 0x38
	private ObjectPtr`1 m_lastBuff; // 0x40
	private AnimConfig m_lastConfig; // 0x50
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0__TryUpdateNewAnimConfig; // 0x10
	private static DelegateBridge __Hotfix0__KeepOldAnimState; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3f295ac VA: 0x75965415ac
	public override Void Init(SpineMixExtraLayer layer, ObjectPtr`1 owner) { }
	// RVA: 0x3f29778 VA: 0x7596541778
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x3f29a7c VA: 0x7596541a7c
	private Void _TryUpdateNewAnimConfig(Unit ownerObj) { }
	// RVA: 0x3f2995c VA: 0x759654195c
	private Boolean _KeepOldAnimState() { }
	// RVA: 0x3f29e00 VA: 0x7596541e00
	public Void .ctor() { }
	// RVA: 0x3f29edc VA: 0x7596541edc
	private Void <>xLuaBaseProxy_Init(SpineMixExtraLayer P0, ObjectPtr`1 P1) { }
	// RVA: 0x3f29ee0 VA: 0x7596541ee0
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```