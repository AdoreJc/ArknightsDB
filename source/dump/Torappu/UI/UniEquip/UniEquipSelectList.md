# UniEquipSelectList

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `CharQuery charQuery`

- `CharacterData charData`

- `PlayerCharacter playerCharacter`

- `Int32 instCharId`

- `String selectEquipId`

- `String uniEquipId`

- `Input attributeInput`

- `AttributesData attributeData`

- `AttributeRawDelta attributeDelta`

- `String traitDesc1`

- `String traitDesc2`

- `String cacheFocus`

- `AVGConfig m_avgConfig`

- `Int32 m_focusIndex`

- `Boolean m_needFocus`


## Properties

- `Boolean isUnlocked`

- `Int32 focusIndex`

- `Boolean needFocus`


## Methods

- `Boolean get_isUnlocked()`

- `Int32 get_focusIndex()`

- `Boolean get_needFocus()`

- `Void LoadData(LoadParam)`

- `Void SwitchEquip(String, Boolean)`

- `Boolean CheckNeedUnlockAvg(Int32)`

- `Boolean CheckNeedLevelupAvg(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipSelectList : IHotfixable
{
	public CharQuery charQuery; // 0x10
	public CharacterData charData; // 0x28
	public PlayerCharacter playerCharacter; // 0x30
	public Int32 instCharId; // 0x38
	public List`1 talentDescsDictionary; // 0x40
	public Dictionary`2 viewModelDict; // 0x48
	public List`1 selectViewModels; // 0x50
	public String selectEquipId; // 0x58
	public String uniEquipId; // 0x60
	public Input attributeInput; // 0x68
	public AttributesData attributeData; // 0x80
	public AttributeRawDelta attributeDelta; // 0x88
	public String traitDesc1; // 0x90
	public String traitDesc2; // 0x98
	public String cacheFocus; // 0xa0
	private AVGConfig m_avgConfig; // 0xa8
	private Int32 m_focusIndex; // 0xbc
	private Boolean m_needFocus; // 0xc0
	private static DelegateBridge __Hotfix0_get_isUnlocked; // 0x0
	private static DelegateBridge __Hotfix0_get_focusIndex; // 0x8
	private static DelegateBridge __Hotfix0_get_needFocus; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_SwitchEquip; // 0x20
	private static DelegateBridge __Hotfix0_CheckNeedUnlockAvg; // 0x28
	private static DelegateBridge __Hotfix0_CheckNeedLevelupAvg; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean isUnlocked { get; }
	public Int32 focusIndex { get; }
	public Boolean needFocus { get; }

	// RVA: 0x2303dbc VA: 0x759491bdbc
	public Boolean get_isUnlocked() { }
	// RVA: 0x2303f18 VA: 0x759491bf18
	public Int32 get_focusIndex() { }
	// RVA: 0x2303e98 VA: 0x759491be98
	public Boolean get_needFocus() { }
	// RVA: 0x230a3c4 VA: 0x75949223c4
	public Void LoadData(LoadParam param) { }
	// RVA: 0x230b4b0 VA: 0x75949234b0
	public Void SwitchEquip(String uniEquipId, Boolean needFocus) { }
	// RVA: 0x23049d4 VA: 0x759491c9d4
	public Boolean CheckNeedUnlockAvg(Int32 index) { }
	// RVA: 0x2304b04 VA: 0x759491cb04
	public Boolean CheckNeedLevelupAvg(Int32 index) { }
	// RVA: 0x230c568 VA: 0x7594924568
	public Void .ctor() { }
}
```