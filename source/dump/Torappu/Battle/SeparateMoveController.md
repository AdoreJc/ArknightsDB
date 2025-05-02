# SeparateMoveController

**Namespace:** `Torappu.Battle`


## Fields

- `Single _separationForceFactor`

- `Single _separationRadius`

- `Single _minSeparationSumDelta`

- `Int32 _separationTickPeriod`


## Methods

- `Vector2 _CalculateSeparationForce()`

- `Void <>xLuaBaseProxy_CalculateIsHanging(Vector2, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SeparateMoveController : MoveController
{
	private Single _separationForceFactor; // 0x60
	private Single _separationRadius; // 0x64
	private Single _minSeparationSumDelta; // 0x68
	private Int32 _separationTickPeriod; // 0x6c
	private readonly List`1 m_relevantUnitsPtr; // 0x70
	private static DelegateBridge __Hotfix0_CalculateIsHanging; // 0x0
	private static DelegateBridge __Hotfix0__CalculateSeparationForce; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x40e55dc VA: 0x75966fd5dc
	protected override Void CalculateIsHanging(Vector2 direction, ref Vector2 resultForce) { }
	// RVA: 0x40e5758 VA: 0x75966fd758
	private Vector2 _CalculateSeparationForce() { }
	// RVA: 0x40e5c48 VA: 0x75966fdc48
	public Void .ctor() { }
	// RVA: 0x40e5d28 VA: 0x75966fdd28
	private Void <>xLuaBaseProxy_CalculateIsHanging(Vector2 P0, ref Vector2 P1) { }
}
```