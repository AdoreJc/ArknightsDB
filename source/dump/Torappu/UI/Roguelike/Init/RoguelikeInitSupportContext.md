# RoguelikeInitSupportContext

**Namespace:** `Torappu.UI.Roguelike.Init`


## Methods

- `RoguelikeRewardShowType _GetUnderText(RoguelikeGameChoiceData, out)`

- `Void <OnSelect>b__9_0(RoguelikeSelectChoiceResponse)`

- `Boolean <>xLuaBaseProxy_get_showHint()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Init
public class RoguelikeInitSupportContext : RoguelikeInitOptionContext
{
	private List`1 m_list; // 0x28
	private List`1 m_choices; // 0x30
	private static DelegateBridge __Hotfix0_get_list; // 0x0
	private static DelegateBridge __Hotfix0_get_showHint; // 0x8
	private static DelegateBridge __Hotfix0_get_name; // 0x10
	private static DelegateBridge __Hotfix0_Load; // 0x18
	private static DelegateBridge __Hotfix0_OnSelect; // 0x20
	private static DelegateBridge __Hotfix0__GetUnderText; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override List`1 list { get; }
	public override Boolean showHint { get; }
	public override String name { get; }

	// RVA: 0x2b82ad8 VA: 0x759519aad8
	public override List`1 get_list() { }
	// RVA: 0x2b82b40 VA: 0x759519ab40
	public override Boolean get_showHint() { }
	// RVA: 0x2b82ba8 VA: 0x759519aba8
	public override String get_name() { }
	// RVA: 0x2b82c34 VA: 0x759519ac34
	public override Void Load(PlayerRoguelikePendingEvent evt) { }
	// RVA: 0x2b833c8 VA: 0x759519b3c8
	public override Void OnSelect(Int32 idx) { }
	// RVA: 0x2b83280 VA: 0x759519b280
	private RoguelikeRewardShowType _GetUnderText(RoguelikeGameChoiceData choiceData, out String itemIcon) { }
	// RVA: 0x2b836bc VA: 0x759519b6bc
	public Void .ctor() { }
	// RVA: 0x2b837cc VA: 0x759519b7cc
	private Void <OnSelect>b__9_0(RoguelikeSelectChoiceResponse response) { }
	// RVA: 0x2b837d0 VA: 0x759519b7d0
	private Boolean <>xLuaBaseProxy_get_showHint() { }
}
```