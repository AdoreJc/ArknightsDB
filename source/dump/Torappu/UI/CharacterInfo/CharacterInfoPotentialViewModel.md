# CharacterInfoPotentialViewModel

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `PlayerCharacter playerChar`

- `CharacterData charData`

- `PotentialType potentialType`

- `PotentialItemViewModel voucherItem`

- `PotentialItemViewModel charItem`

- `PotentialItemViewModel commonItem`

- `Boolean showMixedHint`


## Methods

- `Void LoadData(PlayerCharacter, CharacterData)`

- `Void RefreshData(PlayerCharacter)`

- `PotentialType _ResolvePotentialType()`

- `PotentialItemViewModel _ResolveVoucherItem()`

- `PotentialItemViewModel _ResolveCharItem()`

- `PotentialItemViewModel _ResolveCommonItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoPotentialViewModel : IHotfixable
{
	public PlayerCharacter playerChar; // 0x10
	public CharacterData charData; // 0x18
	public PotentialType potentialType; // 0x20
	public PotentialItemViewModel voucherItem; // 0x28
	public PotentialItemViewModel charItem; // 0x30
	public PotentialItemViewModel commonItem; // 0x38
	public Boolean showMixedHint; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshData; // 0x8
	private static DelegateBridge __Hotfix0__ResolvePotentialType; // 0x10
	private static DelegateBridge __Hotfix0__ResolveVoucherItem; // 0x18
	private static DelegateBridge __Hotfix0__ResolveCharItem; // 0x20
	private static DelegateBridge __Hotfix0__ResolveCommonItem; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2d57750 VA: 0x759536f750
	public Void LoadData(PlayerCharacter pc, CharacterData cd) { }
	// RVA: 0x2d57858 VA: 0x759536f858
	public Void RefreshData(PlayerCharacter pc) { }
	// RVA: 0x2d579ec VA: 0x759536f9ec
	private PotentialType _ResolvePotentialType() { }
	// RVA: 0x2d57aec VA: 0x759536faec
	private PotentialItemViewModel _ResolveVoucherItem() { }
	// RVA: 0x2d57c50 VA: 0x759536fc50
	private PotentialItemViewModel _ResolveCharItem() { }
	// RVA: 0x2d57e84 VA: 0x759536fe84
	private PotentialItemViewModel _ResolveCommonItem() { }
	// RVA: 0x2d5797c VA: 0x759536f97c
	public Void .ctor() { }
}
```