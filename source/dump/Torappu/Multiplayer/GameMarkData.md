# GameMarkData

**Namespace:** `Torappu.Multiplayer`


## Fields

- `PlayerSide side`

- `PlayerMarkType opr`

- `PinType pinType`

- `GridPosition grid`

- `Direction dir`

- `Signiture sig`

- `String emojiGroup`

- `String emojiId`


## Methods

- `Void AssignPinData(PinType, GridPosition)`

- `Void AssignDummyDragData(Signiture, GridPosition, Direction)`

- `Void OnAllocate()`

- `Void OnRecycle()`

- `Void ReadFrom(IStreamReader)`

- `Void WriteTo(IStreamWriter)`

- `Void CopyFrom(GameMarkData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer
public class GameMarkData : IReusable
{
	private const Int32 PIN_INT_PARAM_CNT; // 0x0
	private const Int32 NONE_PARAM_CNT; // 0x0
	private const Int32 DUMMY_INT_PARAM_CNT; // 0x0
	private const Int32 DUMMY_STRING_PARAM_CNT; // 0x0
	private const Int32 EMOJI_STRING_PARAM_CNT; // 0x0
	public PlayerSide side; // 0x10
	public PlayerMarkType opr; // 0x14
	public PinType pinType; // 0x18
	public GridPosition grid; // 0x1c
	public Direction dir; // 0x24
	public Signiture sig; // 0x28
	public String emojiGroup; // 0x38
	public String emojiId; // 0x40


	// RVA: 0x358d038 VA: 0x7595ba5038
	public Void .ctor() { }
	// RVA: 0x358d0c4 VA: 0x7595ba50c4
	public Void AssignPinData(PinType pinType, GridPosition grid) { }
	// RVA: 0x358d0d0 VA: 0x7595ba50d0
	public Void AssignDummyDragData(Signiture sig, GridPosition grid, Direction dir) { }
	// RVA: 0x358d0f0 VA: 0x7595ba50f0
	public Void OnAllocate() { }
	// RVA: 0x358d054 VA: 0x7595ba5054
	public Void OnRecycle() { }
	// RVA: 0x358d0f4 VA: 0x7595ba50f4
	public Void ReadFrom(IStreamReader data) { }
	// RVA: 0x358d834 VA: 0x7595ba5834
	public Void WriteTo(IStreamWriter data) { }
	// RVA: 0x358df18 VA: 0x7595ba5f18
	public Void CopyFrom(GameMarkData data) { }
}
```