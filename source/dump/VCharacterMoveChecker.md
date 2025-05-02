# VCharacterMoveChecker

**Namespace:** ` `


## Fields

- `VCharacterController m_controller`


## Properties

- `VCharacter character`

- `GridMap gridMap`


## Methods

- `VCharacter get_character()`

- `GridMap get_gridMap()`

- `Void Verify(ref, ref)`

- `Void _VerifyDoorState(ref)`

- `Void _VerifyDirection(DoorPosState, ref)`

- `Boolean _CheckMovePositionValid(DoorPosState, GridPosition, Boolean)`

- `Boolean _IsPositionDoor(GridPosition)`

- `Boolean _IsPositionNotBesideWall(GridPosition)`

- `Boolean _IsPositionFocusToDoor(GridPosition, Vector2)`

- `Void _FocusToDoorPosition(GridPosition, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class VCharacterMoveChecker
{
	private VCharacterController m_controller; // 0x10

	private VCharacter character { get; }
	private GridMap gridMap { get; }

	// RVA: 0x3cfffcc VA: 0x7596317fcc
	public Void .ctor(VCharacterController controller) { }
	// RVA: 0x3d01fb8 VA: 0x7596319fb8
	private VCharacter get_character() { }
	// RVA: 0x3d01fd0 VA: 0x7596319fd0
	private GridMap get_gridMap() { }
	// RVA: 0x3cfe330 VA: 0x7596316330
	public Void Verify(ref DoorPosState doorPosState, ref Vector2 direction) { }
	// RVA: 0x3d02208 VA: 0x759631a208
	private Void _VerifyDoorState(ref DoorPosState doorPosState) { }
	// RVA: 0x3d0232c VA: 0x759631a32c
	private Void _VerifyDirection(DoorPosState doorPosState, ref Vector2 direction) { }
	// RVA: 0x3d02534 VA: 0x759631a534
	private Boolean _CheckMovePositionValid(DoorPosState doorPosState, GridPosition pos, Boolean ignoreEmptyGridCheck) { }
	// RVA: 0x3d02628 VA: 0x759631a628
	private Boolean _IsPositionDoor(GridPosition pos) { }
	// RVA: 0x3d025ec VA: 0x759631a5ec
	private Boolean _IsPositionNotBesideWall(GridPosition pos) { }
	// RVA: 0x3d02690 VA: 0x759631a690
	private Boolean _IsPositionFocusToDoor(GridPosition pos, Vector2 direction) { }
	// RVA: 0x3d01ff0 VA: 0x7596319ff0
	private Void _FocusToDoorPosition(GridPosition pos, ref Vector2 direction) { }
}
```