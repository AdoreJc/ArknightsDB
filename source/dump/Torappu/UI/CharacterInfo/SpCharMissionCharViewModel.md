# SpCharMissionCharViewModel

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `String charId`

- `Int32 charInstId`

- `String name`

- `Boolean isCurrnet`

- `String skinId`


## Methods

- `Void LoadData(PlayerCharacter, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class SpCharMissionCharViewModel : IHotfixable
{
	public String charId; // 0x10
	public Int32 charInstId; // 0x18
	public String name; // 0x20
	public Boolean isCurrnet; // 0x28
	public String skinId; // 0x30
	public List`1 missionModels; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2d65c1c VA: 0x759537dc1c
	public Void LoadData(PlayerCharacter playerChar, Boolean isCur) { }
	// RVA: 0x2d65b58 VA: 0x759537db58
	public Void .ctor() { }
}
```