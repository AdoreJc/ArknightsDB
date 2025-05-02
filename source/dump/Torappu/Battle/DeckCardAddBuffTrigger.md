# DeckCardAddBuffTrigger

**Namespace:** `Torappu.Battle`


## Fields

- `String _deckBuffKey`

- `Boolean _checkOneWithoutBuff`

- `Boolean _filterIsInHand`

- `Boolean _exceptTokenAndTrap`


## Methods

- `Boolean <>xLuaBaseProxy_get_isReadyToTrig()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class DeckCardAddBuffTrigger : TargetTrigger
{
	private String _deckBuffKey; // 0x20
	private Boolean _checkOneWithoutBuff; // 0x28
	private Boolean _filterIsInHand; // 0x29
	private Boolean _exceptTokenAndTrap; // 0x2a
	private static DelegateBridge __Hotfix0_get_target; // 0x0
	private static DelegateBridge __Hotfix0_get_isReadyToTrig; // 0x8
	private static DelegateBridge __Hotfix0_Search; // 0x10
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override Entity target { get; }
	public override Boolean isReadyToTrig { get; }

	// RVA: 0x1bd4b14 VA: 0x75941ecb14
	public override Entity get_target() { }
	// RVA: 0x1bd4b78 VA: 0x75941ecb78
	public override Boolean get_isReadyToTrig() { }
	// RVA: 0x1bd4be0 VA: 0x75941ecbe0
	public override Boolean Search(Boolean force) { }
	// RVA: 0x1bd4d30 VA: 0x75941ecd30
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1bd4dac VA: 0x75941ecdac
	public Void .ctor() { }
	// RVA: 0x1bd4e28 VA: 0x75941ece28
	private Boolean <>xLuaBaseProxy_get_isReadyToTrig() { }
}
```