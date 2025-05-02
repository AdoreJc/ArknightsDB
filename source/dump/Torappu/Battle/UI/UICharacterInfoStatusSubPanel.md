# UICharacterInfoStatusSubPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Image _eliteIcon`

- `Text _nameEnLabel`

- `Text _nameCnLabel`

- `Text _lvlLabel`

- `Slider _hpSlider`

- `Slider _spSlider`

- `Text _hpLabel`

- `Text _atkLabel`

- `Text _defLabel`

- `Text _magicResistLabel`

- `Text _blockLabel`

- `Text _spLabel`

- `RectTransform _attackRangeContainer`

- `UICharacterAttackRangeWidget _attackRangeWidget`

- `Image _professionImage`

- `Image _uniEquipTypeIcon`


## Methods

- `Void _UpdateUniequipTypeIcon(List`1, Boolean)`

- `Void <>xLuaBaseProxy_SetData(ObjectPtr`1, ModeType, Card)`

- `Void <>xLuaBaseProxy_UpdateData(ObjectPtr`1, ModeType, Card)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UICharacterInfoStatusSubPanel : UICharacterInfoSubPanel
{
	private const String DEFAULT_LABEL_DISPLAY; // 0x0
	private Image _eliteIcon; // 0x20
	private Text _nameEnLabel; // 0x28
	private Text _nameCnLabel; // 0x30
	private Text _lvlLabel; // 0x38
	private Sprite[] _evolveIcons; // 0x40
	private Slider _hpSlider; // 0x48
	private Slider _spSlider; // 0x50
	private Text _hpLabel; // 0x58
	private Text _atkLabel; // 0x60
	private Text _defLabel; // 0x68
	private Text _magicResistLabel; // 0x70
	private Text _blockLabel; // 0x78
	private Text _spLabel; // 0x80
	private RectTransform _attackRangeContainer; // 0x88
	private UICharacterAttackRangeWidget _attackRangeWidget; // 0x90
	protected ProfessionSpritePair[] _professionIcons; // 0x98
	protected Image _professionImage; // 0xa0
	private Image _uniEquipTypeIcon; // 0xa8
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0__UpdateUniequipTypeIcon; // 0x8
	private static DelegateBridge __Hotfix0_UpdateData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2035398 VA: 0x759464d398
	public override Void SetData(ObjectPtr`1 characterPtr, ModeType mode, Card card) { }
	// RVA: 0x2035cb0 VA: 0x759464dcb0
	private Void _UpdateUniequipTypeIcon(List`1 queries, Boolean isToken) { }
	// RVA: 0x2035fbc VA: 0x759464dfbc
	public override Void UpdateData(ObjectPtr`1 characterPtr, ModeType mode, Card card) { }
	// RVA: 0x2036928 VA: 0x759464e928
	public Void .ctor() { }
	// RVA: 0x2036a70 VA: 0x759464ea70
	private Void <>xLuaBaseProxy_SetData(ObjectPtr`1 P0, ModeType P1, Card P2) { }
	// RVA: 0x2036b10 VA: 0x759464eb10
	private Void <>xLuaBaseProxy_UpdateData(ObjectPtr`1 P0, ModeType P1, Card P2) { }
}
```