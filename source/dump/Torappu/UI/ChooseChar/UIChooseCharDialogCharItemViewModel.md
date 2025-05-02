# UIChooseCharDialogCharItemViewModel

**Namespace:** `Torappu.UI.ChooseChar`


## Fields

- `String charId`

- `CharacterData characterData`

- `PlayerCharacter playerCharacter`


## Methods

- `String GetCharId()`

- `Boolean IsOwned()`

- `CharacterData GetCharData()`

- `PlayerCharacter GetPlayerCharacter()`

- `Boolean IsClickable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ChooseChar
public class UIChooseCharDialogCharItemViewModel : ICommonChooseCharCardViewModel, IHotfixable
{
	public String charId; // 0x10
	public CharacterData characterData; // 0x18
	public PlayerCharacter playerCharacter; // 0x20
	private static DelegateBridge __Hotfix0_GetCharId; // 0x0
	private static DelegateBridge __Hotfix0_IsOwned; // 0x8
	private static DelegateBridge __Hotfix0_GetCharData; // 0x10
	private static DelegateBridge __Hotfix0_GetPlayerCharacter; // 0x18
	private static DelegateBridge __Hotfix0_IsClickable; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2c41068 VA: 0x7595259068
	public String GetCharId() { }
	// RVA: 0x2c410d0 VA: 0x75952590d0
	public Boolean IsOwned() { }
	// RVA: 0x2c41140 VA: 0x7595259140
	public CharacterData GetCharData() { }
	// RVA: 0x2c411a8 VA: 0x75952591a8
	public PlayerCharacter GetPlayerCharacter() { }
	// RVA: 0x2c41210 VA: 0x7595259210
	public Boolean IsClickable() { }
	// RVA: 0x2c40d58 VA: 0x7595258d58
	public Void .ctor() { }
}
```