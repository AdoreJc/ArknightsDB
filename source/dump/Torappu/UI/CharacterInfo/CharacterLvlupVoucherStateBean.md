# CharacterLvlupVoucherStateBean

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterIllustViewProperty illustProperty`

- `CharacterLvlupVoucherViewProperty voucherViewProperty`

- `Int32 charInstId`

- `String voucherItemId`

- `Int32 voucherItemInstId`

- `CharQuery m_charQuery`

- `Int32 <originLevel>k__BackingField`


## Properties

- `String charId`

- `Int32 originLevel`


## Methods

- `String get_charId()`

- `Int32 get_originLevel()`

- `Void set_originLevel(Int32)`

- `CharQuery GetCharQuery()`

- `Void LoadData(Param)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupVoucherStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	public CharacterIllustViewProperty illustProperty; // 0x18
	public CharacterLvlupVoucherViewProperty voucherViewProperty; // 0x20
	public Int32 charInstId; // 0x28
	public String voucherItemId; // 0x30
	public Int32 voucherItemInstId; // 0x38
	private CharQuery m_charQuery; // 0x40
	private List`1 m_equipPairs; // 0x58
	private Int32 <originLevel>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_charId; // 0x0
	private static DelegateBridge __Hotfix0_get_originLevel; // 0x8
	private static DelegateBridge __Hotfix0_set_originLevel; // 0x10
	private static DelegateBridge __Hotfix0_GetCharQuery; // 0x18
	private static DelegateBridge __Hotfix0_GetEquipQueries; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public String charId { get; }
	public Int32 originLevel { get; set; }

	// RVA: 0x2d6279c VA: 0x759537a79c
	public String get_charId() { }
	// RVA: 0x2d62804 VA: 0x759537a804
	public Int32 get_originLevel() { }
	// RVA: 0x2d6286c VA: 0x759537a86c
	public Void set_originLevel(Int32 value) { }
	// RVA: 0x2d628e8 VA: 0x759537a8e8
	public CharQuery GetCharQuery() { }
	// RVA: 0x2d62978 VA: 0x759537a978
	public List`1 GetEquipQueries() { }
	// RVA: 0x2d629e0 VA: 0x759537a9e0
	public Void LoadData(Param param) { }
	// RVA: 0x2d631c4 VA: 0x759537b1c4
	public Void .ctor() { }
}
```