# RoguelikeRelicCharChecker

**Namespace:** `Torappu`


## Methods

- `Boolean Verify(Char)`

- `Boolean _Check(Char, RoguelikeGameRelicCheckType, RoguelikeGameRelicCheckParam)`

- `Boolean _CheckProfession(Char, RoguelikeGameRelicCheckParam)`

- `Boolean _CheckSubProfession(Char, RoguelikeGameRelicCheckParam)`

- `Boolean _CheckUpgrade(Char, RoguelikeGameRelicCheckParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RoguelikeRelicCharChecker : IHotfixable
{
	private List`1 m_checkTypes; // 0x10
	private List`1 m_checkParams; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Verify; // 0x8
	private static DelegateBridge __Hotfix0__Check; // 0x10
	private static DelegateBridge __Hotfix0__CheckProfession; // 0x18
	private static DelegateBridge __Hotfix0__CheckSubProfession; // 0x20
	private static DelegateBridge __Hotfix0__CheckUpgrade; // 0x28


	// RVA: 0x353a270 VA: 0x7595b52270
	public Void .ctor(List`1 checkTypes, List`1 checkParams) { }
	// RVA: 0x353a31c VA: 0x7595b5231c
	public Boolean Verify(Char charData) { }
	// RVA: 0x353a490 VA: 0x7595b52490
	private Boolean _Check(Char charData, RoguelikeGameRelicCheckType checkType, RoguelikeGameRelicCheckParam checkParam) { }
	// RVA: 0x353a5a0 VA: 0x7595b525a0
	private Boolean _CheckProfession(Char charData, RoguelikeGameRelicCheckParam checkParam) { }
	// RVA: 0x353a6e0 VA: 0x7595b526e0
	private Boolean _CheckSubProfession(Char charData, RoguelikeGameRelicCheckParam checkParam) { }
	// RVA: 0x353a838 VA: 0x7595b52838
	private Boolean _CheckUpgrade(Char charData, RoguelikeGameRelicCheckParam checkParam) { }
}
```