# RoguelikeInitRecruitSetContext

**Namespace:** `Torappu.UI.Roguelike.Init`


## Methods

- `Void _AddRecruitSet(String, Boolean, RoguelikeTopicDetail)`

- `Void <OnSelect>b__8_0(RoguelikeSelectInitialRecruitSetResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Init
internal class RoguelikeInitRecruitSetContext : RoguelikeInitOptionContext
{
	private List`1 m_list; // 0x28
	private List`1 m_recuitGrps; // 0x30
	private static DelegateBridge __Hotfix0_get_list; // 0x0
	private static DelegateBridge __Hotfix0_get_name; // 0x8
	private static DelegateBridge __Hotfix0_Load; // 0x10
	private static DelegateBridge __Hotfix0__AddRecruitSet; // 0x18
	private static DelegateBridge __Hotfix0_OnSelect; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override List`1 list { get; }
	public override String name { get; }

	// RVA: 0x2b82030 VA: 0x759519a030
	public override List`1 get_list() { }
	// RVA: 0x2b82098 VA: 0x759519a098
	public override String get_name() { }
	// RVA: 0x2b82124 VA: 0x759519a124
	public override Void Load(PlayerRoguelikePendingEvent evt) { }
	// RVA: 0x2b823d8 VA: 0x759519a3d8
	private Void _AddRecruitSet(String grpId, Boolean unlockBySvr, RoguelikeTopicDetail detail) { }
	// RVA: 0x2b82778 VA: 0x759519a778
	public override Void OnSelect(Int32 idx) { }
	// RVA: 0x2b829c4 VA: 0x759519a9c4
	public Void .ctor() { }
	// RVA: 0x2b82ad4 VA: 0x759519aad4
	private Void <OnSelect>b__8_0(RoguelikeSelectInitialRecruitSetResponse response) { }
}
```