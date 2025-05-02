# CooperateCommonGlobalBuff

**Namespace:** `Torappu.Battle`


## Fields

- `Single _reviveInterval`

- `Int32 _reviveLifePoint`

- `CooperateGameMode m_gameMode`

- `PlayerSide m_dyingSide`


## Properties

- `FP reviveInterval`

- `FP curReviveRemainingTime`


## Methods

- `FP get_reviveInterval()`

- `FP get_curReviveRemainingTime()`

- `Int32 _GetReviveLifePoint(Int32)`

- `Void _OnCooperateLifeZero(Object)`

- `Void _BeforeResting(Object)`

- `Void <>xLuaBaseProxy_OnInit(GlobalBuffData)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CooperateCommonGlobalBuff : GlobalBuff
{
	private Single _reviveInterval; // 0xdc
	private Int32 _reviveLifePoint; // 0xe0
	private CooperateGameMode m_gameMode; // 0xe8
	private readonly PeriodicTimer m_intervalTicker; // 0xf0
	private PlayerSide m_dyingSide; // 0xf8
	private static DelegateBridge __Hotfix0_get_reviveInterval; // 0x0
	private static DelegateBridge __Hotfix0_get_curReviveRemainingTime; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge __Hotfix0__GetReviveLifePoint; // 0x20
	private static DelegateBridge __Hotfix0__OnCooperateLifeZero; // 0x28
	private static DelegateBridge __Hotfix0__BeforeResting; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public FP reviveInterval { get; }
	public FP curReviveRemainingTime { get; }

	// RVA: 0x401503c VA: 0x759662d03c
	public FP get_reviveInterval() { }
	// RVA: 0x40150dc VA: 0x759662d0dc
	public FP get_curReviveRemainingTime() { }
	// RVA: 0x401519c VA: 0x759662d19c
	public override Void OnInit(GlobalBuffData data) { }
	// RVA: 0x40153dc VA: 0x759662d3dc
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x4015554 VA: 0x759662d554
	private Int32 _GetReviveLifePoint(Int32 currentLife) { }
	// RVA: 0x40156b8 VA: 0x759662d6b8
	private Void _OnCooperateLifeZero(Object arg) { }
	// RVA: 0x40157e0 VA: 0x759662d7e0
	private Void _BeforeResting(Object arg) { }
	// RVA: 0x4015894 VA: 0x759662d894
	public Void .ctor() { }
	// RVA: 0x4015954 VA: 0x759662d954
	private Void <>xLuaBaseProxy_OnInit(GlobalBuffData P0) { }
	// RVA: 0x4015958 VA: 0x759662d958
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```