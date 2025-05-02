# SetAnimatorIntByBuffStackCnt

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _buffKey`

- `String _paramName`

- `Int32 _paramInitVal`

- `Single _checkInterval`

- `Animator m_animator`

- `Int32 m_paramID`

- `PeriodicTimer m_timer`

- `Int32 m_paramVal`


## Methods

- `Void _SetIntByBuffStackCntIfNecessary()`

- `Boolean _TryCacheBuff()`

- `Void Update()`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnRecycle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class SetAnimatorIntByBuffStackCnt : Behaviour
{
	private String _buffKey; // 0x20
	private String _paramName; // 0x28
	private Int32 _paramInitVal; // 0x30
	private Single _checkInterval; // 0x34
	private Animator m_animator; // 0x38
	private Int32 m_paramID; // 0x40
	private PeriodicTimer m_timer; // 0x48
	private Int32 m_paramVal; // 0x50
	private ObjectPtr`1 m_buffPtr; // 0x58
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x8
	private static DelegateBridge __Hotfix0__SetIntByBuffStackCntIfNecessary; // 0x10
	private static DelegateBridge __Hotfix0__TryCacheBuff; // 0x18
	private static DelegateBridge __Hotfix0_Update; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2008cc0 VA: 0x7594620cc0
	public override Void OnPlay() { }
	// RVA: 0x2008fac VA: 0x7594620fac
	public override Void OnRecycle() { }
	// RVA: 0x2009050 VA: 0x7594621050
	private Void _SetIntByBuffStackCntIfNecessary() { }
	// RVA: 0x2008e58 VA: 0x7594620e58
	private Boolean _TryCacheBuff() { }
	// RVA: 0x2009164 VA: 0x7594621164
	private Void Update() { }
	// RVA: 0x200925c VA: 0x759462125c
	public Void .ctor() { }
	// RVA: 0x20092cc VA: 0x75946212cc
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x20092d4 VA: 0x75946212d4
	private Void <>xLuaBaseProxy_OnRecycle() { }
}
```