# RoguelikeDungeonDialogController

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeTopicDialogPlugin m_topicPlugin`

- `String m_topicId`


## Methods

- `IEnumerator ShowDialogs(UICompDialogMgr)`

- `Boolean CheckNeedToShow()`

- `Void <>xLuaBaseProxy_OnCreate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeDungeonDialogController : PageSingleComponent, IHotfixable
{
	private Dictionary`2 m_dialogMgrs; // 0x20
	private RoguelikeTopicDialogPlugin m_topicPlugin; // 0x28
	private List`1 m_dialogs; // 0x30
	private String m_topicId; // 0x38
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_ShowDialogs; // 0x8
	private static DelegateBridge __Hotfix0_CheckNeedToShow; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x29ff288 VA: 0x7595017288
	protected override Void OnCreate() { }
	// RVA: 0x29ff86c VA: 0x759501786c
	public IEnumerator ShowDialogs(UICompDialogMgr compDialogMgr) { }
	// RVA: 0x29ff964 VA: 0x7595017964
	public Boolean CheckNeedToShow() { }
	// RVA: 0x29ffc74 VA: 0x7595017c74
	public Void .ctor() { }
	// RVA: 0x29ffd38 VA: 0x7595017d38
	private Void <>xLuaBaseProxy_OnCreate() { }
}
```