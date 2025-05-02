# CommonCharSelectShuffleDefaultViewModel

**Namespace:** `Torappu.UI.TemplateCharSelect.Common`


## Fields

- `ProfessionCategory m_profFilter`

- `CharacterFilterViewModel filter`

- `CharacterCardSortTypeViewModel sort`

- `Boolean showFilter`


## Methods

- `Void UpdateFilter(CharacterFilterViewModel)`

- `Void <>xLuaBaseProxy_OnReset(TemplateCharSelectModelResetData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect.Common
public class CommonCharSelectShuffleDefaultViewModel : TemplateShuffleViewModelBase`1
{
	private ProfessionCategory m_profFilter; // 0x10
	public CharacterFilterViewModel filter; // 0x18
	public CharacterCardSortTypeViewModel sort; // 0x20
	public Boolean showFilter; // 0x28
	private static DelegateBridge __Hotfix0_get_sortType; // 0x0
	private static DelegateBridge __Hotfix0_get_profFilter; // 0x8
	private static DelegateBridge __Hotfix0_OnReset; // 0x10
	private static DelegateBridge __Hotfix0_UpdateFilter; // 0x18
	private static DelegateBridge __Hotfix0_OnSortChar; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override CharacterSortType sortType { get; }
	public override ProfessionCategory profFilter { get; }

	// RVA: 0x2c56894 VA: 0x759526e894
	public override CharacterSortType get_sortType() { }
	// RVA: 0x2c56908 VA: 0x759526e908
	public override ProfessionCategory get_profFilter() { }
	// RVA: 0x2c56970 VA: 0x759526e970
	public override Void OnReset(TemplateCharSelectModelResetData data) { }
	// RVA: 0x2c5653c VA: 0x759526e53c
	public Void UpdateFilter(CharacterFilterViewModel f) { }
	// RVA: 0x2c56a24 VA: 0x759526ea24
	protected override Int32 OnSortChar(TemplateCharSelectCardViewModel a, TemplateCharSelectCardViewModel b) { }
	// RVA: 0x2c56c34 VA: 0x759526ec34
	public Void .ctor() { }
	// RVA: 0x2c56d50 VA: 0x759526ed50
	private Void <>xLuaBaseProxy_OnReset(TemplateCharSelectModelResetData P0) { }
}
```