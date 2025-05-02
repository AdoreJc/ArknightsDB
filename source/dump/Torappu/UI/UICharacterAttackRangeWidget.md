# UICharacterAttackRangeWidget

**Namespace:** `Torappu.UI`


## Fields

- `Sprite _tileEmpty`

- `Sprite _tileStand`

- `Sprite _tileAttack`

- `String m_cachedRangeId`

- `GridLayoutGroup m_grid`


## Properties

- `GridLayoutGroup grid`


## Methods

- `GridLayoutGroup get_grid()`

- `Void RenderAttackRange(AttackRangeDescModel)`

- `Boolean _CheckIfRangeDirty(AttackRangeDescModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterAttackRangeWidget : MonoBehaviour, IHotfixable
{
	protected Sprite _tileEmpty; // 0x18
	protected Sprite _tileStand; // 0x20
	protected Sprite _tileAttack; // 0x28
	private String m_cachedRangeId; // 0x30
	protected GridLayoutGroup m_grid; // 0x38
	private static DelegateBridge __Hotfix0_get_grid; // 0x0
	private static DelegateBridge __Hotfix0_RenderAttackRange; // 0x8
	private static DelegateBridge __Hotfix0__CheckIfRangeDirty; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected GridLayoutGroup grid { get; }

	// RVA: 0x212a278 VA: 0x7594742278
	protected GridLayoutGroup get_grid() { }
	// RVA: 0x212a42c VA: 0x759474242c
	public Void RenderAttackRange(AttackRangeDescModel attackRange) { }
	// RVA: 0x212a814 VA: 0x7594742814
	private Boolean _CheckIfRangeDirty(AttackRangeDescModel attackRange) { }
	// RVA: 0x212a3bc VA: 0x75947423bc
	public Void .ctor() { }
}
```