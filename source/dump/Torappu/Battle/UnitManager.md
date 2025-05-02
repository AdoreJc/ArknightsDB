# UnitManager

**Namespace:** `Torappu.Battle`


## Properties

- `Int32 enemyCnt`

- `Int32 characterCnt`

- `Int32 neutralCnt`


## Methods

- `Void set_allUnits(UnorderedArray`1)`

- `Void set_characters(UnorderedArray`1)`

- `Void set_enemies(UnorderedArray`1)`

- `Void set_neutralUnits(UnorderedArray`1)`

- `Int32 get_enemyCnt()`

- `Int32 get_characterCnt()`

- `Int32 get_neutralCnt()`

- `Int32 GetPlayerCharacterCnt(PlayerSide)`

- `Void SetPlayerCharacterCnt(Int32, PlayerSide)`

- `Void Register(Unit)`

- `Void Unregister(Unit)`

- `Character GetCharacterById(String)`

- `Character GetFirstCharacterByUid(UInt32)`

- `Character GetFirstCharacterByInstanceUid(UInt32)`

- `Character GetCharacterByAlias(String)`

- `Boolean TryGetCharacterById(String, out)`

- `Boolean TryGetCharacterByUid(UInt32, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class UnitManager
{
	private UnorderedArray`1 <allUnits>k__BackingField; // 0x10
	private UnorderedArray`1 <characters>k__BackingField; // 0x18
	private UnorderedArray`1 <enemies>k__BackingField; // 0x20
	private UnorderedArray`1 <neutralUnits>k__BackingField; // 0x28
	private readonly ListDict`2 m_activePlayerCharacterCnt; // 0x30

	public UnorderedArray`1 allUnits { get; set; }
	public UnorderedArray`1 characters { get; set; }
	public UnorderedArray`1 enemies { get; set; }
	public UnorderedArray`1 neutralUnits { get; set; }
	public Int32 enemyCnt { get; }
	public Int32 characterCnt { get; }
	public Int32 neutralCnt { get; }

	// RVA: 0x1c36c30 VA: 0x759424ec30
	public UnorderedArray`1 get_allUnits() { }
	// RVA: 0x1c36c38 VA: 0x759424ec38
	private Void set_allUnits(UnorderedArray`1 value) { }
	// RVA: 0x1c36c40 VA: 0x759424ec40
	public UnorderedArray`1 get_characters() { }
	// RVA: 0x1c36c48 VA: 0x759424ec48
	private Void set_characters(UnorderedArray`1 value) { }
	// RVA: 0x1c36c50 VA: 0x759424ec50
	public UnorderedArray`1 get_enemies() { }
	// RVA: 0x1c36c58 VA: 0x759424ec58
	private Void set_enemies(UnorderedArray`1 value) { }
	// RVA: 0x1c36c60 VA: 0x759424ec60
	public UnorderedArray`1 get_neutralUnits() { }
	// RVA: 0x1c36c68 VA: 0x759424ec68
	private Void set_neutralUnits(UnorderedArray`1 value) { }
	// RVA: 0x1c36c70 VA: 0x759424ec70
	public Int32 get_enemyCnt() { }
	// RVA: 0x1c36cb8 VA: 0x759424ecb8
	public Int32 get_characterCnt() { }
	// RVA: 0x1c36d00 VA: 0x759424ed00
	public Int32 get_neutralCnt() { }
	// RVA: 0x1c36d48 VA: 0x759424ed48
	public Int32 GetPlayerCharacterCnt(PlayerSide playerSide) { }
	// RVA: 0x1c36ddc VA: 0x759424eddc
	public Void SetPlayerCharacterCnt(Int32 delta, PlayerSide side) { }
	// RVA: 0x1c36ee0 VA: 0x759424eee0
	public Void .ctor(Int32 capacity, List`1 activePlayers) { }
	// RVA: 0x1c370bc VA: 0x759424f0bc
	public Void Register(Unit unit) { }
	// RVA: 0x1c371d8 VA: 0x759424f1d8
	public Void Unregister(Unit unit) { }
	// RVA: 0x1c28ca0 VA: 0x7594240ca0
	public UnorderedArray`1 GetUnitsBySingleSide(SideType sidePower2) { }
	// RVA: 0x1c372f8 VA: 0x759424f2f8
	public Character GetCharacterById(String id) { }
	// RVA: 0x1c37438 VA: 0x759424f438
	public Character GetFirstCharacterByUid(UInt32 uniqueId) { }
	// RVA: 0x1c37578 VA: 0x759424f578
	public Character GetFirstCharacterByInstanceUid(UInt32 instanceUid) { }
	// RVA: 0x1c376a8 VA: 0x759424f6a8
	public Character GetCharacterByAlias(String alias) { }
	// RVA: 0x1c377f0 VA: 0x759424f7f0
	public Boolean TryGetCharacterById(String id, out Character character) { }
	// RVA: 0x1c3787c VA: 0x759424f87c
	public Boolean TryGetCharacterByUid(UInt32 uniqueId, out Character character) { }
}
```