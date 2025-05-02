# EnemyDuelRoomPlayerCard

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Text _name`

- `Button _btnKick`

- `EnemyDuelRoomPlayerCardModel m_model`

- `Boolean <kickValid>k__BackingField`


## Properties

- `Boolean kickValid`


## Methods

- `Void RenderViewModel(EnemyDuelRoomPlayerCardModel)`

- `Boolean get_kickValid()`

- `Void set_kickValid(Boolean)`

- `Void EventKick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelRoomPlayerCard : MonoBehaviour
{
	private Text _name; // 0x18
	private Button _btnKick; // 0x20
	private EnemyDuelRoomPlayerCardModel m_model; // 0x28
	private Boolean <kickValid>k__BackingField; // 0x30

	public Boolean kickValid { get; set; }

	// RVA: 0x29a0a88 VA: 0x7594fb8a88
	public Void RenderViewModel(EnemyDuelRoomPlayerCardModel model) { }
	// RVA: 0x29a0b24 VA: 0x7594fb8b24
	public Boolean get_kickValid() { }
	// RVA: 0x29a0b2c VA: 0x7594fb8b2c
	public Void set_kickValid(Boolean value) { }
	// RVA: 0x29a0b38 VA: 0x7594fb8b38
	public Void EventKick() { }
	// RVA: 0x29a0d1c VA: 0x7594fb8d1c
	public Void .ctor() { }
}
```