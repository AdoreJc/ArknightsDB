# UIBattleSandboxMapView

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `UIAtlasImage _tile`

- `GameObject _emptyTile`

- `GameObject _warning`

- `GameObject _OutLine`

- `GridLayoutGroup _mapTileRoot`

- `Transform _outLineRoot`

- `Int32 m_horizonNum`

- `Int32 m_verticalNum`


## Properties

- `GridLayoutGroup mapTileRoot`


## Methods

- `GridLayoutGroup get_mapTileRoot()`

- `Void _GenerataOffset(LevelData, List`1)`

- `Int32 GetLeftOffset()`

- `Int32 GetRightOffset()`

- `Int32 GetUpOffset()`

- `Int32 GetBottomOffset()`

- `Void _PrepareList(Int32, Int32)`

- `Void _GenerateOutLine(List`1, Boolean, Single)`

- `Void Render(LevelData, Color, Color, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxMapView : MonoBehaviour
{
	private UIAtlasImage _tile; // 0x18
	private GameObject _emptyTile; // 0x20
	private GameObject _warning; // 0x28
	private GameObject _OutLine; // 0x30
	private GridLayoutGroup _mapTileRoot; // 0x38
	private Transform _outLineRoot; // 0x40
	private List`1 m_haveUpperOutLine; // 0x48
	private List`1 m_haveBottomOutLine; // 0x50
	private List`1 m_haveLeftOutLine; // 0x58
	private List`1 m_haveRightOutLine; // 0x60
	private Int32 m_horizonNum; // 0x68
	private Int32 m_verticalNum; // 0x6c
	private List`1 m_verticalOffset; // 0x70
	private List`1 m_horizontalOffset; // 0x78

	public GridLayoutGroup mapTileRoot { get; }

	// RVA: 0x209af44 VA: 0x75946b2f44
	public GridLayoutGroup get_mapTileRoot() { }
	// RVA: 0x209af4c VA: 0x75946b2f4c
	private Void _GenerataOffset(LevelData data, List`1 hiddens) { }
	// RVA: 0x209b334 VA: 0x75946b3334
	public Int32 GetLeftOffset() { }
	// RVA: 0x209b390 VA: 0x75946b3390
	public Int32 GetRightOffset() { }
	// RVA: 0x209b3ec VA: 0x75946b33ec
	public Int32 GetUpOffset() { }
	// RVA: 0x209b448 VA: 0x75946b3448
	public Int32 GetBottomOffset() { }
	// RVA: 0x209b4a4 VA: 0x75946b34a4
	private Void _PrepareList(Int32 width, Int32 height) { }
	// RVA: 0x209b95c VA: 0x75946b395c
	private Void _GenerateOutLine(List`1 lists, Boolean isVertical, Single offset) { }
	// RVA: 0x209bebc VA: 0x75946b3ebc
	public Void Render(LevelData data, Color lowLandColor, Color highlandColor, Boolean needGenerateOutLine) { }
	// RVA: 0x209c544 VA: 0x75946b4544
	public Void .ctor() { }
}
```