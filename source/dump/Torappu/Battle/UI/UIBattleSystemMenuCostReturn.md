# UIBattleSystemMenuCostReturn

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Text _textReturn`

- `Text _descriptionLabel`

- `Image _iconAp`

- `Image _iconEt`

- `String m_etOrBuffItemId`


## Methods

- `Void SetData(ViewStruct)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBattleSystemMenuCostReturn : MonoBehaviour, IHotfixable
{
	public const Int32 BUFF_COST_RETURN; // 0x0
	private const String AP_RETURN_TEXT_FORMAT; // 0x0
	private Text _textReturn; // 0x18
	private Text _descriptionLabel; // 0x20
	private Image _iconAp; // 0x28
	private Image _iconEt; // 0x30
	private String m_etOrBuffItemId; // 0x38
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x204353c VA: 0x759465b53c
	public Void SetData(ViewStruct viewStruct) { }
	// RVA: 0x2046cd0 VA: 0x759465ecd0
	public Void .ctor() { }
}
```