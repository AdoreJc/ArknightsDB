# SyncEffectScaleViaBuffBlackboard

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _buffKey`

- `String _blackboardKey`

- `Single _updateInterval`

- `Single _minScale`

- `Boolean _includeZaxis`

- `Single m_lastValue`

- `Single m_updateInterval`


## Methods

- `Void Update()`

- `Void _UpdateEffect()`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class SyncEffectScaleViaBuffBlackboard : Behaviour
{
	private String _buffKey; // 0x20
	private String _blackboardKey; // 0x28
	private Single _updateInterval; // 0x30
	private Single _minScale; // 0x34
	private Boolean _includeZaxis; // 0x38
	private Single m_lastValue; // 0x3c
	private Single m_updateInterval; // 0x40
	private ObjectPtr`1 m_holdBuff; // 0x48
	private static DelegateBridge __Hotfix0_get_holdBuff; // 0x0
	private static DelegateBridge __Hotfix0_OnPlay; // 0x8
	private static DelegateBridge __Hotfix0_OnFinish; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge __Hotfix0__UpdateEffect; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private ObjectPtr`1 holdBuff { get; }

	// RVA: 0x2013268 VA: 0x759462b268
	private ObjectPtr`1 get_holdBuff() { }
	// RVA: 0x20133b8 VA: 0x759462b3b8
	public override Void OnPlay() { }
	// RVA: 0x2013634 VA: 0x759462b634
	public override Void OnFinish() { }
	// RVA: 0x2013708 VA: 0x759462b708
	private Void Update() { }
	// RVA: 0x2013438 VA: 0x759462b438
	private Void _UpdateEffect() { }
	// RVA: 0x20137c8 VA: 0x759462b7c8
	public Void .ctor() { }
	// RVA: 0x2013888 VA: 0x759462b888
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x2013890 VA: 0x759462b890
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```