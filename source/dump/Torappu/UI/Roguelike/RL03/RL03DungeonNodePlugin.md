# RL03DungeonNodePlugin

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `GameObject _clearPart`

- `GameObject _hidePart`

- `GameObject _hasTotem`

- `SimpleLayoutContent _content`

- `RoguelikeDetailNodeDialog _dialog`

- `Adapter m_adapter`

- `Boolean m_isInited`

- `RoguelikeDungeonNode m_node`


## Methods

- `Void _InitIfNot()`

- `Void OnDialogDetail()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03DungeonNodePlugin : RoguelikeDungeonNodePlugin
{
	private GameObject _clearPart; // 0x18
	private GameObject _hidePart; // 0x20
	private GameObject _hasTotem; // 0x28
	private SimpleLayoutContent _content; // 0x30
	private RoguelikeDetailNodeDialog _dialog; // 0x38
	private Adapter m_adapter; // 0x40
	private Boolean m_isInited; // 0x48
	private RoguelikeDungeonNode m_node; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnDialogDetail; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2b8b258 VA: 0x75951a3258
	private Void _InitIfNot() { }
	// RVA: 0x2b8b394 VA: 0x75951a3394
	public override Void Render(RoguelikeDungeonNode node) { }
	// RVA: 0x2b8b558 VA: 0x75951a3558
	public Void OnDialogDetail() { }
	// RVA: 0x2b8b884 VA: 0x75951a3884
	public Void .ctor() { }
}
```