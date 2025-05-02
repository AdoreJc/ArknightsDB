# FunLiveEventDataTransmission

**Namespace:** `Torappu.Battle`


## Fields

- `FunLiveGameMode m_gameMode`


## Methods

- `Void GetRareEventFromBlackboard()`

- `Void <>xLuaBaseProxy_OnInit(GlobalBuffData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class FunLiveEventDataTransmission : GlobalBuff, IHotfixable
{
	private FunLiveGameMode m_gameMode; // 0xe0
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_GetRareEventFromBlackboard; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x401816c VA: 0x759663016c
	public override Void OnInit(GlobalBuffData data) { }
	// RVA: 0x40182e0 VA: 0x75966302e0
	private Void GetRareEventFromBlackboard() { }
	// RVA: 0x40184a0 VA: 0x75966304a0
	public Void .ctor() { }
	// RVA: 0x401850c VA: 0x759663050c
	private Void <>xLuaBaseProxy_OnInit(GlobalBuffData P0) { }
}
```