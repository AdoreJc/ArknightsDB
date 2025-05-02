# DIYTestScene

**Namespace:** `Torappu.Building.DIY.Test`


## Fields

- `MockFurnitureManager _furnitureManager`

- `MockFurnitureFromTableManager _furnitureFromTableManager`

- `MockDIYRoomModifierManager _DIYRoomModifierManager`

- `MockDIYRoomInfoManager _DIYRoomInfoManager`

- `Boolean _useTable`

- `DIYRoom _room`

- `Int32 m_controllerIndex`

- `Single m_outlineWidth`

- `Single m_outlineZ`

- `Int32 m_roomCount`

- `Int32 m_roomIndex`

- `Furniture m_currentFurniture`

- `Vector2 m_scrollVecRoomFurniture`

- `Vector2 m_scrollVecStackFurniture`

- `Vector2 m_scrollVecStackModifier`

- `Boolean m_uiCollapsed`

- `Texture2D m_backTexture0`

- `Texture2D m_backTexture1`

- `IFurnitureManager m_currentFurnitureManager`


## Methods

- `Void Awake()`

- `Void Start()`

- `Void Update()`

- `Void SetupRoom(Int32)`

- `IFurnitureController _GetFurnitureController(Furniture)`

- `Void OnGUI()`

- `Void MoveUp()`

- `Void MoveLeft()`

- `Void MoveDown()`

- `Void MoveRight()`

- `Void SwitchForward()`

- `Void SwitchBackward()`

- `Void <Start>b__22_1(DIYRoomInfo)`

- `Void <SetupRoom>b__24_0(IFurnitureController)`

- `Boolean <SetupRoom>b__24_1(Furniture)`

- `Void <SetupRoom>b__24_2(Furniture)`

- `Boolean <SwitchForward>b__31_0(Furniture)`

- `Void <SwitchForward>b__31_1(Furniture)`

- `Boolean <SwitchBackward>b__32_0(Furniture)`

- `Void <SwitchBackward>b__32_1(Furniture)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.Test
public class DIYTestScene : MonoBehaviour
{
	private MockFurnitureManager _furnitureManager; // 0x18
	private MockFurnitureFromTableManager _furnitureFromTableManager; // 0x20
	private MockDIYRoomModifierManager _DIYRoomModifierManager; // 0x28
	private MockDIYRoomInfoManager _DIYRoomInfoManager; // 0x30
	private Boolean _useTable; // 0x38
	private DIYRoom _room; // 0x40
	private AbstractTable[] _tablesToLoad; // 0x48
	private List`1 m_controllerList; // 0x50
	private Int32 m_controllerIndex; // 0x58
	private Single m_outlineWidth; // 0x5c
	private Single m_outlineZ; // 0x60
	private Int32 m_roomCount; // 0x64
	private Int32 m_roomIndex; // 0x68
	private Furniture m_currentFurniture; // 0x70
	private Vector2 m_scrollVecRoomFurniture; // 0x78
	private Vector2 m_scrollVecStackFurniture; // 0x80
	private Vector2 m_scrollVecStackModifier; // 0x88
	private Boolean m_uiCollapsed; // 0x90
	private Texture2D m_backTexture0; // 0x98
	private Texture2D m_backTexture1; // 0xa0
	private IFurnitureManager m_currentFurnitureManager; // 0xa8


	// RVA: 0x37ed4f0 VA: 0x7595e054f0
	private Void Awake() { }
	// RVA: 0x37edd84 VA: 0x7595e05d84
	private Void Start() { }
	// RVA: 0x37ee494 VA: 0x7595e06494
	private Void Update() { }
	// RVA: 0x37ee03c VA: 0x7595e0603c
	private Void SetupRoom(Int32 index) { }
	// RVA: 0x37eed10 VA: 0x7595e06d10
	private IFurnitureController _GetFurnitureController(Furniture furniture) { }
	// RVA: 0x37eee08 VA: 0x7595e06e08
	private Void OnGUI() { }
	// RVA: 0x37ee508 VA: 0x7595e06508
	private Void MoveUp() { }
	// RVA: 0x37ee708 VA: 0x7595e06708
	private Void MoveLeft() { }
	// RVA: 0x37ee90c VA: 0x7595e0690c
	private Void MoveDown() { }
	// RVA: 0x37eeb0c VA: 0x7595e06b0c
	private Void MoveRight() { }
	// RVA: 0x37f0564 VA: 0x7595e08564
	private Void SwitchForward() { }
	// RVA: 0x37f09fc VA: 0x7595e089fc
	private Void SwitchBackward() { }
	// RVA: 0x37f0ca8 VA: 0x7595e08ca8
	public Void .ctor() { }
	// RVA: 0x37f0d48 VA: 0x7595e08d48
	private Void <Start>b__22_1(DIYRoomInfo x) { }
	// RVA: 0x37f0d58 VA: 0x7595e08d58
	private Void <SetupRoom>b__24_0(IFurnitureController x) { }
	// RVA: 0x37f0e08 VA: 0x7595e08e08
	private Boolean <SetupRoom>b__24_1(Furniture x) { }
	// RVA: 0x37f0edc VA: 0x7595e08edc
	private Void <SetupRoom>b__24_2(Furniture x) { }
	// RVA: 0x37f0ee4 VA: 0x7595e08ee4
	private Boolean <SwitchForward>b__31_0(Furniture x) { }
	// RVA: 0x37f0fb8 VA: 0x7595e08fb8
	private Void <SwitchForward>b__31_1(Furniture x) { }
	// RVA: 0x37f0fc0 VA: 0x7595e08fc0
	private Boolean <SwitchBackward>b__32_0(Furniture x) { }
	// RVA: 0x37f1094 VA: 0x7595e09094
	private Void <SwitchBackward>b__32_1(Furniture x) { }
}
```