# RoguelikeInitManualRecruitContext

**Namespace:** `Torappu.UI.Roguelike.Init`


## Fields

- `Int32 m_showCharCnt`

- `Input <charSelInput>k__BackingField`


## Properties

- `Input charSelInput`


## Methods

- `Input get_charSelInput()`

- `Void set_charSelInput(Input)`

- `Void _JumpToRoguelikeCharSelect(String)`

- `Void _OnSelectRecruitResponse(String, Int32, Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Init
public class RoguelikeInitManualRecruitContext : RoguelikeInitRecruitContext
{
	private List`1 m_list; // 0x28
	private Int32 m_showCharCnt; // 0x30
	private String[] m_tickets; // 0x38
	private Input <charSelInput>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_charSelInput; // 0x0
	private static DelegateBridge __Hotfix0_set_charSelInput; // 0x8
	private static DelegateBridge __Hotfix0_get_list; // 0x10
	private static DelegateBridge __Hotfix0_get_name; // 0x18
	private static DelegateBridge __Hotfix0_Load; // 0x20
	private static DelegateBridge __Hotfix0_OnSelect; // 0x28
	private static DelegateBridge __Hotfix0__JumpToRoguelikeCharSelect; // 0x30
	private static DelegateBridge __Hotfix0__OnSelectRecruitResponse; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Input charSelInput { get; set; }
	public override List`1 list { get; }
	public override String name { get; }

	// RVA: 0x2b80264 VA: 0x7595198264
	public Input get_charSelInput() { }
	// RVA: 0x2b802cc VA: 0x75951982cc
	private Void set_charSelInput(Input value) { }
	// RVA: 0x2b80350 VA: 0x7595198350
	public override List`1 get_list() { }
	// RVA: 0x2b803b8 VA: 0x75951983b8
	public override String get_name() { }
	// RVA: 0x2b80444 VA: 0x7595198444
	public override Void Load(PlayerRoguelikePendingEvent evt) { }
	// RVA: 0x2b80cf0 VA: 0x7595198cf0
	public override Void OnSelect(Int32 idx) { }
	// RVA: 0x2b80ff4 VA: 0x7595198ff4
	private Void _JumpToRoguelikeCharSelect(String ticketIndex) { }
	// RVA: 0x2b81118 VA: 0x7595199118
	private Void _OnSelectRecruitResponse(String ticketId, Int32 result, Action callback) { }
	// RVA: 0x2b81300 VA: 0x7595199300
	public Void .ctor() { }
}
```