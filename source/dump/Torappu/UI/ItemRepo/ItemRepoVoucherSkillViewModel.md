# ItemRepoVoucherSkillViewModel

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `SkillGroupViewModel skillGroupViewModel`

- `UIItemViewModel voucherItemViewModel`

- `Int32 <selectedIdx>k__BackingField`


## Properties

- `Int32 selectedIdx`


## Methods

- `Int32 get_selectedIdx()`

- `Void set_selectedIdx(Int32)`

- `Void LoadData(PlayerCharacter, CharacterData, UIItemViewModel)`

- `Void SetChooseState(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoVoucherSkillViewModel : IHotfixable
{
	public SkillGroupViewModel skillGroupViewModel; // 0x10
	public UIItemViewModel voucherItemViewModel; // 0x18
	private Int32 <selectedIdx>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_get_selectedIdx; // 0x0
	private static DelegateBridge __Hotfix0_set_selectedIdx; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_SetChooseState; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Int32 selectedIdx { get; set; }

	// RVA: 0x2d27a1c VA: 0x759533fa1c
	public Int32 get_selectedIdx() { }
	// RVA: 0x2d2e68c VA: 0x759534668c
	private Void set_selectedIdx(Int32 value) { }
	// RVA: 0x2d2e4b8 VA: 0x75953464b8
	public Void LoadData(PlayerCharacter playerChar, CharacterData charData, UIItemViewModel itemModel) { }
	// RVA: 0x2d2e438 VA: 0x7595346438
	public Void SetChooseState(Int32 idx) { }
	// RVA: 0x2d2e708 VA: 0x7595346708
	public Void .ctor() { }
}
```