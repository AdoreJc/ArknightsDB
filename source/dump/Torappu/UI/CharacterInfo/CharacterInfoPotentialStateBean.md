# CharacterInfoPotentialStateBean

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Int32 charInstId`

- `PlayerCharacter playerChar`

- `CharacterData charData`

- `CharacterInfoPotentialViewModel potentialViewModel`

- `Boolean ignoreNoClassicHint`

- `Boolean showFadeInAnim`


## Methods

- `Void LoadData(Param)`

- `Void RefreshData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoPotentialStateBean : IStateBean, IHotfixable
{
	public Int32 charInstId; // 0x10
	public PlayerCharacter playerChar; // 0x18
	public CharacterData charData; // 0x20
	public CharacterInfoPotentialViewModel potentialViewModel; // 0x28
	public Boolean ignoreNoClassicHint; // 0x30
	public Boolean showFadeInAnim; // 0x31
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d46700 VA: 0x759535e700
	public Void LoadData(Param param) { }
	// RVA: 0x2d476d0 VA: 0x759535f6d0
	public Void RefreshData() { }
	// RVA: 0x2d47a8c VA: 0x759535fa8c
	public Void .ctor() { }
}
```