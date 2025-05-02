# BuildingLoader

**Namespace:** `Torappu.Building.EditorTools`


## Fields

- `String _layoutId`

- `TextAsset _playerDataText`

- `Boolean _usePlayerDataText`

- `TextAsset _visitBuildingText`

- `Boolean _useVisitBuildingText`


## Methods

- `Void Start()`

- `Void InitTestData()`

- `Void _LoadBuildingForCurrentPlayer()`

- `Void _LoadBuildingForVisiting(VisitBuildingResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.EditorTools
public class BuildingLoader : MonoBehaviour
{
	private String _layoutId; // 0x18
	private TextAsset _playerDataText; // 0x20
	private Boolean _usePlayerDataText; // 0x28
	private TextAsset _visitBuildingText; // 0x30
	private Boolean _useVisitBuildingText; // 0x38


	// RVA: 0x3d11430 VA: 0x7596329430
	private Void Start() { }
	// RVA: 0x3d11a2c VA: 0x7596329a2c
	public Void InitTestData() { }
	// RVA: 0x3d114d8 VA: 0x75963294d8
	private Void _LoadBuildingForCurrentPlayer() { }
	// RVA: 0x3d117a4 VA: 0x75963297a4
	private Void _LoadBuildingForVisiting(VisitBuildingResponse visitResponse) { }
	// RVA: 0x3d11bf4 VA: 0x7596329bf4
	public Void .ctor() { }
}
```