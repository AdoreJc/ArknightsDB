# Aircraft

**Namespace:** `Torappu.Battle`


## Fields

- `Single _speed`

- `Int32 _moveHeight`

- `Int32 _moveWidth`

- `Single _defaultZ`

- `Single _maxMovementPerFrame`

- `GameObject _skillGridRangeDrawerPrefab`

- `Single _charColloderR`

- `Tiles2D m_tiles`

- `Border m_border`

- `Vector3 m_beginPos`

- `Vector3 m_endPos`

- `GameObject m_skillGridRangeDrawer`

- `ResidentCharacterRangeDrawer m_gridRangeDrawer`

- `Int32 m_touchFingerId`

- `Int32 m_touchCount`

- `Boolean m_hasInit`


## Properties

- `Int32 width`

- `Int32 height`

- `Tiles2D Tile`

- `Single charColliderR`

- `Single defaultZ`


## Methods

- `Int32 get_width()`

- `Int32 get_height()`

- `Tiles2D get_Tile()`

- `Single get_charColliderR()`

- `Single get_defaultZ()`

- `Void AddCharacter(Character)`

- `Void RemoveCharacter(Character)`

- `Void InitAircraft()`

- `Void ImportTiles()`

- `Void Update()`

- `Void _OnBegin(Vector2)`

- `Void _OnMove(Vector2)`

- `Void _OnKeyboard()`

- `Void _MoveAircraft(Vector3)`

- `Tile GetTileFromScreenPos(Vector2, out)`

- `Boolean GetMapPosByScreenPos(Vector2, out)`

- `Vector2 WorldToMapPosition(Vector3)`

- `Void CheckBorder()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Aircraft : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private Single _speed; // 0x18
	private Int32 _moveHeight; // 0x1c
	private Int32 _moveWidth; // 0x20
	private Single _defaultZ; // 0x24
	private Single _maxMovementPerFrame; // 0x28
	private GameObject _skillGridRangeDrawerPrefab; // 0x30
	private Single _charColloderR; // 0x38
	private Tiles2D m_tiles; // 0x40
	private Border m_border; // 0x48
	private Vector3 m_beginPos; // 0x50
	private Vector3 m_endPos; // 0x5c
	private GameObject m_skillGridRangeDrawer; // 0x68
	private ResidentCharacterRangeDrawer m_gridRangeDrawer; // 0x70
	private List`1 m_characterContainer; // 0x78
	private Int32 m_touchFingerId; // 0x80
	private Int32 m_touchCount; // 0x84
	private Boolean m_hasInit; // 0x88
	private IList`1 m_characters; // 0x90
	private static DelegateBridge __Hotfix0_get_width; // 0x0
	private static DelegateBridge __Hotfix0_get_height; // 0x8
	private static DelegateBridge __Hotfix0_get_Tile; // 0x10
	private static DelegateBridge __Hotfix0_get_charColliderR; // 0x18
	private static DelegateBridge __Hotfix0_get_defaultZ; // 0x20
	private static DelegateBridge __Hotfix0_AddCharacter; // 0x28
	private static DelegateBridge __Hotfix0_RemoveCharacter; // 0x30
	private static DelegateBridge __Hotfix0_InitAircraft; // 0x38
	private static DelegateBridge __Hotfix0_ImportTiles; // 0x40
	private static DelegateBridge __Hotfix0_Update; // 0x48
	private static DelegateBridge __Hotfix0__OnBegin; // 0x50
	private static DelegateBridge __Hotfix0__OnMove; // 0x58
	private static DelegateBridge __Hotfix0__OnKeyboard; // 0x60
	private static DelegateBridge __Hotfix0__MoveAircraft; // 0x68
	private static DelegateBridge __Hotfix0_GetTileFromScreenPos; // 0x70
	private static DelegateBridge __Hotfix0_GetMapPosByScreenPos; // 0x78
	private static DelegateBridge __Hotfix0_WorldToMapPosition; // 0x80
	private static DelegateBridge __Hotfix0_CheckBorder; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public Int32 width { get; }
	public Int32 height { get; }
	public Tiles2D Tile { get; }
	public Single charColliderR { get; }
	public Single defaultZ { get; }

	// RVA: 0x3fe64c0 VA: 0x75965fe4c0
	public Int32 get_width() { }
	// RVA: 0x3fe6534 VA: 0x75965fe534
	public Int32 get_height() { }
	// RVA: 0x3fe65a8 VA: 0x75965fe5a8
	public Tiles2D get_Tile() { }
	// RVA: 0x3fe6610 VA: 0x75965fe610
	public Single get_charColliderR() { }
	// RVA: 0x3fe6678 VA: 0x75965fe678
	public Single get_defaultZ() { }
	// RVA: 0x3fe66e0 VA: 0x75965fe6e0
	public Void AddCharacter(Character character) { }
	// RVA: 0x3fe68f4 VA: 0x75965fe8f4
	public Void RemoveCharacter(Character character) { }
	// RVA: 0x3fe6a48 VA: 0x75965fea48
	public Void InitAircraft() { }
	// RVA: 0x3fe6f54 VA: 0x75965fef54
	public Void ImportTiles() { }
	// RVA: 0x3fe70cc VA: 0x75965ff0cc
	private Void Update() { }
	// RVA: 0x3fe7264 VA: 0x75965ff264
	private Void _OnBegin(Vector2 scrPos) { }
	// RVA: 0x3fe7318 VA: 0x75965ff318
	private Void _OnMove(Vector2 scrPos) { }
	// RVA: 0x3fe7840 VA: 0x75965ff840
	private Void _OnKeyboard() { }
	// RVA: 0x3fe7524 VA: 0x75965ff524
	private Void _MoveAircraft(Vector3 offset) { }
	// RVA: 0x3fe7cdc VA: 0x75965ffcdc
	public Tile GetTileFromScreenPos(Vector2 screenPos, out Vector2 mapPos) { }
	// RVA: 0x3fe7e74 VA: 0x75965ffe74
	private Boolean GetMapPosByScreenPos(Vector2 screenPos, out Vector2 mapPos) { }
	// RVA: 0x3fe7fa4 VA: 0x75965fffa4
	private Vector2 WorldToMapPosition(Vector3 worldPos) { }
	// RVA: 0x3fe79e0 VA: 0x75965ff9e0
	private Void CheckBorder() { }
	// RVA: 0x3fe8054 VA: 0x7596600054
	public Void .ctor() { }
}
```