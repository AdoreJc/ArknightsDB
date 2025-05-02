# AdjacentAllyToggleChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `DistanceType _distanceType`

- `Int32 _minManhattan`

- `Int32 _maxManhattan`

- `Int32 _minSquareDistance`

- `Int32 _maxSquareDistance`

- `String _rangeId`

- `CheckType _checkType`

- `Boolean _needProfessionMask`

- `ProfessionCategory _professionMask`

- `Boolean _needBuildableType`

- `BuildableType _buildableType`

- `Boolean _forceCheckSide`

- `SideType _checkSide`

- `Boolean _reverseToggle`


## Properties

- `Boolean isManhatten`

- `Boolean isSquare`

- `Boolean isInRange`

- `Boolean needProfessionMask`

- `Boolean needBuildableType`

- `Boolean forceCheckSide`


## Methods

- `Boolean get_isManhatten()`

- `Boolean get_isSquare()`

- `Boolean get_isInRange()`

- `Boolean get_needProfessionMask()`

- `Boolean get_needBuildableType()`

- `Boolean get_forceCheckSide()`

- `Void _OnAdjacentChanged(Object)`

- `Boolean _CheckCondition()`

- `Boolean _CheckDetail(Unit)`

- `Boolean _CheckDistance(Unit)`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AdjacentAllyToggleChecker : Checker
{
	private DistanceType _distanceType; // 0x20
	private Int32 _minManhattan; // 0x24
	private Int32 _maxManhattan; // 0x28
	private Int32 _minSquareDistance; // 0x2c
	private Int32 _maxSquareDistance; // 0x30
	private String _rangeId; // 0x38
	private CheckType _checkType; // 0x40
	private Boolean _needProfessionMask; // 0x44
	public ProfessionCategory _professionMask; // 0x48
	private Boolean _needBuildableType; // 0x4c
	public BuildableType _buildableType; // 0x50
	private Boolean _forceCheckSide; // 0x54
	private SideType _checkSide; // 0x58
	private Boolean _reverseToggle; // 0x5c
	private static DelegateBridge __Hotfix0_get_isManhatten; // 0x0
	private static DelegateBridge __Hotfix0_get_isSquare; // 0x8
	private static DelegateBridge __Hotfix0_get_isInRange; // 0x10
	private static DelegateBridge __Hotfix0_get_needProfessionMask; // 0x18
	private static DelegateBridge __Hotfix0_get_needBuildableType; // 0x20
	private static DelegateBridge __Hotfix0_get_forceCheckSide; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0_OnAttached; // 0x38
	private static DelegateBridge __Hotfix0_OnDetached; // 0x40
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x48
	private static DelegateBridge __Hotfix0__OnAdjacentChanged; // 0x50
	private static DelegateBridge __Hotfix0__CheckCondition; // 0x58
	private static DelegateBridge __Hotfix0__CheckDetail; // 0x60
	private static DelegateBridge __Hotfix0__CheckDistance; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	protected Boolean isManhatten { get; }
	protected Boolean isSquare { get; }
	protected Boolean isInRange { get; }
	protected Boolean needProfessionMask { get; }
	protected Boolean needBuildableType { get; }
	protected Boolean forceCheckSide { get; }

	// RVA: 0x1e56a38 VA: 0x759446ea38
	protected Boolean get_isManhatten() { }
	// RVA: 0x1e56aa8 VA: 0x759446eaa8
	protected Boolean get_isSquare() { }
	// RVA: 0x1e56b18 VA: 0x759446eb18
	protected Boolean get_isInRange() { }
	// RVA: 0x1e56b88 VA: 0x759446eb88
	protected Boolean get_needProfessionMask() { }
	// RVA: 0x1e56bf0 VA: 0x759446ebf0
	protected Boolean get_needBuildableType() { }
	// RVA: 0x1e56c58 VA: 0x759446ec58
	protected Boolean get_forceCheckSide() { }
	// RVA: 0x1e56cc0 VA: 0x759446ecc0
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e56d38 VA: 0x759446ed38
	public override Void OnAttached() { }
	// RVA: 0x1e56f08 VA: 0x759446ef08
	public override Void OnDetached() { }
	// RVA: 0x1e570d8 VA: 0x759446f0d8
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e57438 VA: 0x759446f438
	private Void _OnAdjacentChanged(Object arg) { }
	// RVA: 0x1e57158 VA: 0x759446f158
	private Boolean _CheckCondition() { }
	// RVA: 0x1e575a4 VA: 0x759446f5a4
	private Boolean _CheckDetail(Unit other) { }
	// RVA: 0x1e5778c VA: 0x759446f78c
	private Boolean _CheckDistance(Unit other) { }
	// RVA: 0x1e57a64 VA: 0x759446fa64
	public Void .ctor() { }
	// RVA: 0x1e57b1c VA: 0x759446fb1c
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1e57b20 VA: 0x759446fb20
	private Void <>xLuaBaseProxy_OnDetached() { }
}
```