# RoguelikeInitModeRelicContext

**Namespace:** `Torappu.UI.Roguelike.Init`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Init
public class RoguelikeInitModeRelicContext : RoguelikeInitConfirmContext
{
	private List`1 m_relics; // 0x28
	private static DelegateBridge __Hotfix0_get_relicList; // 0x0
	private static DelegateBridge __Hotfix0_get_name; // 0x8
	private static DelegateBridge __Hotfix0_Load; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override List`1 relicList { get; }
	public override String name { get; }

	// RVA: 0x2b81520 VA: 0x7595199520
	public override List`1 get_relicList() { }
	// RVA: 0x2b81588 VA: 0x7595199588
	public override String get_name() { }
	// RVA: 0x2b81614 VA: 0x7595199614
	public override Void Load(PlayerRoguelikePendingEvent evt) { }
	// RVA: 0x2b8194c VA: 0x759519994c
	public Void .ctor() { }
	// RVA: 0x2b81a78 VA: 0x7595199a78
	private List`1 <>xLuaBaseProxy_get_relicList() { }
}
```