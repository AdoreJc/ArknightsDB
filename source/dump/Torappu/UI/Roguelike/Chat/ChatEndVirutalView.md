# ChatEndVirutalView

**Namespace:** `Torappu.UI.Roguelike.Chat`


## Fields

- `Boolean isLastChat`

- `Action onClicked`


## Methods

- `Void <>xLuaBaseProxy_OnViewClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Chat
public class ChatEndVirutalView : ChatSimpleViewBase
{
	public Boolean isLastChat; // 0x40
	public Action onClicked; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnViewClicked; // 0x8
	private static DelegateBridge __Hotfix0_UpdateContent; // 0x10


	// RVA: 0x2bba4cc VA: 0x75951d24cc
	public Void .ctor(RoguelikeChatSimpleComp prefab) { }
	// RVA: 0x2bba550 VA: 0x75951d2550
	protected override Void OnViewClicked() { }
	// RVA: 0x2bba5d4 VA: 0x75951d25d4
	protected override DisplayControl UpdateContent() { }
	// RVA: 0x2bba6bc VA: 0x75951d26bc
	private Void <>xLuaBaseProxy_OnViewClicked() { }
}
```