# UniEquipAttributeView

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `Text _maxHp`

- `Text _atk`

- `Text _def`

- `Text _res`

- `Text _reviveTime`

- `GameObject _reviveUpFlag`

- `GameObject _reviveDownFlag`

- `Text _cost`

- `Text _blockNum`

- `Text _atkSpeed`

- `GameObject _atkSpeedUpFlag`

- `GameObject _atkSpeedDownFlag`


## Methods

- `Void Render(AttributesData, AttributeRawDelta)`

- `Void _ApplyText(Text, Int32, Int32, Boolean)`

- `Void _ApplyText(Text, Single, Single)`

- `Void _ApplySymbol(GameObject, GameObject, Text, Single, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipAttributeView : MonoBehaviour, IHotfixable
{
	private Text _maxHp; // 0x18
	private Text _atk; // 0x20
	private Text _def; // 0x28
	private Text _res; // 0x30
	private Text _reviveTime; // 0x38
	private GameObject _reviveUpFlag; // 0x40
	private GameObject _reviveDownFlag; // 0x48
	private Text _cost; // 0x50
	private Text _blockNum; // 0x58
	private Text _atkSpeed; // 0x60
	private GameObject _atkSpeedUpFlag; // 0x68
	private GameObject _atkSpeedDownFlag; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__ApplyText; // 0x8
	private static DelegateBridge __Hotfix1__ApplyText; // 0x10
	private static DelegateBridge __Hotfix0__ApplySymbol; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x22fe428 VA: 0x7594916428
	public Void Render(AttributesData data, AttributeRawDelta delta) { }
	// RVA: 0x22feaec VA: 0x7594916aec
	private Void _ApplyText(Text text, Int32 value, Int32 delta, Boolean eorFlag) { }
	// RVA: 0x22fe840 VA: 0x7594916840
	private Void _ApplyText(Text text, Single value, Single delta) { }
	// RVA: 0x22fed2c VA: 0x7594916d2c
	private Void _ApplySymbol(GameObject upSymbol, GameObject downSymbol, Text text, Single delta, Boolean eorFlag) { }
	// RVA: 0x22fef38 VA: 0x7594916f38
	public Void .ctor() { }
}
```