# RL04FragmentOverloadDialogPlugin

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Text _textHeavy`


## Methods

- `String _GetHeavyDebuffDesc()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentOverloadDialogPlugin : Plugin, IHotfixable
{
	private Text _textHeavy; // 0x18
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0__GetHeavyDebuffDesc; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2b1c00c VA: 0x759513400c
	public override Void OnRender(Options options) { }
	// RVA: 0x2b1c104 VA: 0x7595134104
	private String _GetHeavyDebuffDesc() { }
	// RVA: 0x2b1c2c4 VA: 0x75951342c4
	public Void .ctor() { }
}
```