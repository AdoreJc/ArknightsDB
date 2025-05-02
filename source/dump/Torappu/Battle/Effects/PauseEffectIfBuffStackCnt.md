# PauseEffectIfBuffStackCnt

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _buffKey`

- `Int32 _targetCnt`

- `CompareType _compareType`

- `Single _interval`

- `Boolean _checkBuffCntFromAllBuffs`

- `Boolean _unpauseIf`

- `PeriodicTimer m_timer`


## Methods

- `Void Update()`

- `Int32 _GetBuffStackCnt()`

- `Void <>xLuaBaseProxy_OnPlay()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class PauseEffectIfBuffStackCnt : Behaviour, IHotfixable
{
	private String _buffKey; // 0x20
	private Int32 _targetCnt; // 0x28
	private CompareType _compareType; // 0x2c
	private Single _interval; // 0x30
	private Boolean _checkBuffCntFromAllBuffs; // 0x34
	private Boolean _unpauseIf; // 0x35
	private PeriodicTimer m_timer; // 0x38
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0__GetBuffStackCnt; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2004db8 VA: 0x759461cdb8
	public override Void OnPlay() { }
	// RVA: 0x2004e78 VA: 0x759461ce78
	private Void Update() { }
	// RVA: 0x200500c VA: 0x759461d00c
	private Int32 _GetBuffStackCnt() { }
	// RVA: 0x2005114 VA: 0x759461d114
	public Void .ctor() { }
	// RVA: 0x20051cc VA: 0x759461d1cc
	private Void <>xLuaBaseProxy_OnPlay() { }
}
```