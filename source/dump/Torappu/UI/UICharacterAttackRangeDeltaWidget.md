# UICharacterAttackRangeDeltaWidget

**Namespace:** `Torappu.UI`


## Fields

- `Sprite _tileDelta`

- `Int32 m_endCol`

- `Int32 m_endRow`

- `Int32 m_initCol`

- `Int32 m_initRow`


## Methods

- `Void _InitPos(AttackRangeDescModel, AttackRangeDescModel)`

- `Boolean _CheckAvalid(AttackRangeDescModel, Int32, Int32)`

- `Void RenderAttackRange(AttackRangeDescModel, AttackRangeDescModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterAttackRangeDeltaWidget : UICharacterAttackRangeWidget
{
	private Sprite _tileDelta; // 0x40
	private Int32 m_endCol; // 0x48
	private Int32 m_endRow; // 0x4c
	private Int32 m_initCol; // 0x50
	private Int32 m_initRow; // 0x54
	private static DelegateBridge __Hotfix0__InitPos; // 0x0
	private static DelegateBridge __Hotfix0__CheckAvalid; // 0x8
	private static DelegateBridge __Hotfix0_RenderAttackRange; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2129b68 VA: 0x7594741b68
	private Void _InitPos(AttackRangeDescModel attackRangeInit, AttackRangeDescModel attackRangeEnd) { }
	// RVA: 0x2129d6c VA: 0x7594741d6c
	private Boolean _CheckAvalid(AttackRangeDescModel attackRange, Int32 row, Int32 col) { }
	// RVA: 0x2129e60 VA: 0x7594741e60
	public Void RenderAttackRange(AttackRangeDescModel attackRangeInit, AttackRangeDescModel attackRangeEnd) { }
	// RVA: 0x212a350 VA: 0x7594742350
	public Void .ctor() { }
}
```