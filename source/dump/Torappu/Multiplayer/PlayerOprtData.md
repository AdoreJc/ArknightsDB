# PlayerOprtData

**Namespace:** `Torappu.Multiplayer`


## Fields

- `PlayerSide side`

- `PlayerOperator oprt`

- `CharacterAction action`

- `Direction dir`

- `GridPosition grid`

- `Signiture sig`

- `Int32 status`


## Methods

- `Void OnAllocate()`

- `Void OnRecycle()`

- `Void ReadFrom(IStreamReader)`

- `Void WriteTo(IStreamWriter)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer
public class PlayerOprtData : IReusable
{
	private const Int32 CHARATCER_INT_PARAM_CNT; // 0x0
	private const Int32 CHARATCER_STRING_PARAM_CNT; // 0x0
	private const Int32 OTHER_INT_PARAM_CNT; // 0x0
	private const Int32 OTHER_STRING_PARAM_CNT; // 0x0
	public PlayerSide side; // 0x10
	public PlayerOperator oprt; // 0x14
	public CharacterAction action; // 0x18
	public Direction dir; // 0x1c
	public GridPosition grid; // 0x20
	public Signiture sig; // 0x28
	public Int32 status; // 0x38


	// RVA: 0x358ca5c VA: 0x7595ba4a5c
	public Void .ctor() { }
	// RVA: 0x358cad8 VA: 0x7595ba4ad8
	public Void OnAllocate() { }
	// RVA: 0x358ca78 VA: 0x7595ba4a78
	public Void OnRecycle() { }
	// RVA: 0x358c484 VA: 0x7595ba4484
	public Void ReadFrom(IStreamReader data) { }
	// RVA: 0x358cadc VA: 0x7595ba4adc
	public Void WriteTo(IStreamWriter data) { }
}
```