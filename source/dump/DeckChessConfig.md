# DeckChessConfig

**Namespace:** ` `


## Fields

- `String chessId`

- `AdvancedCharacterInst inst`

- `String overrideName`

- `String cultivateEffectId`

- `CharSkinData skinData`

- `Boolean preloadAsCharacter`

- `ProfessionCategory profession`


## Methods

- `String <>xLuaBaseProxy_ToString()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DeckChessConfig : IHotfixable
{
	public String chessId; // 0x10
	public AdvancedCharacterInst inst; // 0x18
	public String overrideName; // 0x20
	public String cultivateEffectId; // 0x28
	public CharSkinData skinData; // 0x30
	public Boolean preloadAsCharacter; // 0x38
	public ProfessionCategory profession; // 0x3c
	private static DelegateBridge __Hotfix0_ToString; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x1c9b86c VA: 0x75942b386c
	public override String ToString() { }
	// RVA: 0x1c9ab4c VA: 0x75942b2b4c
	public Void .ctor() { }
	// RVA: 0x1c9b900 VA: 0x75942b3900
	private String <>xLuaBaseProxy_ToString() { }
}
```