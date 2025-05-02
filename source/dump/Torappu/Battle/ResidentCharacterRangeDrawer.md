# ResidentCharacterRangeDrawer

**Namespace:** `Torappu.Battle`


## Fields

- `Vector2 m_centerOffset`


## Methods

- `Void _UpdateRange()`

- `Void TurnOnAircraft(IList`1)`

- `Void _TurnOnInternalAircraft(IList`1, Material)`

- `Mesh _CreateAircraftMesh(IList`1)`

- `Void ClearResidentRanges()`

- `Void <>xLuaBaseProxy__TurnOnInternal(IList`1, Material)`

- `Void <>xLuaBaseProxy_TurnOff()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ResidentCharacterRangeDrawer : GridRangeDrawer
{
	private HashSet`1 m_meshPonitGridPositions; // 0xc0
	private HashSet`1 m_meshPonits; // 0xc8
	private Vector2 m_centerOffset; // 0xd0
	private List`1 m_residentRanges; // 0xd8
	private static DelegateBridge __Hotfix0__TurnOnInternal; // 0x0
	private static DelegateBridge __Hotfix0__UpdateRange; // 0x8
	private static DelegateBridge __Hotfix0_TurnOnAircraft; // 0x10
	private static DelegateBridge __Hotfix0__TurnOnInternalAircraft; // 0x18
	private static DelegateBridge __Hotfix0__CreateAircraftMesh; // 0x20
	private static DelegateBridge __Hotfix0_ClearResidentRanges; // 0x28
	private static DelegateBridge __Hotfix0_TurnOff; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x1c52fe0 VA: 0x759426afe0
	protected override Void _TurnOnInternal(IList`1 ranges, Material material) { }
	// RVA: 0x1c538c4 VA: 0x759426b8c4
	public Void _UpdateRange() { }
	// RVA: 0x VA: 0x0
	public Void TurnOnAircraft(IList`1 units) { }
	// RVA: 0x1c539dc VA: 0x759426b9dc
	private Void _TurnOnInternalAircraft(IList`1 ranges, Material material) { }
	// RVA: 0x1c5315c VA: 0x759426b15c
	private Mesh _CreateAircraftMesh(IList`1 ranges) { }
	// RVA: 0x1c53ad8 VA: 0x759426bad8
	public Void ClearResidentRanges() { }
	// RVA: 0x1c53b80 VA: 0x759426bb80
	public override Void TurnOff() { }
	// RVA: 0x1c53c30 VA: 0x759426bc30
	public Void .ctor() { }
	// RVA: 0x1c53dac VA: 0x759426bdac
	private Void <>xLuaBaseProxy__TurnOnInternal(IList`1 P0, Material P1) { }
	// RVA: 0x1c53db4 VA: 0x759426bdb4
	private Void <>xLuaBaseProxy_TurnOff() { }
}
```