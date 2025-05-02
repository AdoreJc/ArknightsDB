# RoguelikeFriendAssistSearchView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `SimpleLayoutContent _professionTabList`

- `SimpleLayoutContent _assistList`

- `Boolean m_hasInited`

- `ProfessionTabAdapter m_professionTabAdapter`

- `AssistListAdapter m_assistListAdapter`

- `RoguelikeFriendAssistSearchModel m_model`


## Methods

- `Void set_onAssistItemClick(Action`1)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeFriendAssistSearchView : DataBinder`1
{
	private SimpleLayoutContent _professionTabList; // 0x20
	private SimpleLayoutContent _assistList; // 0x28
	private Boolean m_hasInited; // 0x30
	private ProfessionTabAdapter m_professionTabAdapter; // 0x38
	private AssistListAdapter m_assistListAdapter; // 0x40
	private RoguelikeFriendAssistSearchModel m_model; // 0x48
	private Action`1 <onAssistItemClick>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_onAssistItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onAssistItemClick; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onAssistItemClick { get; set; }

	// RVA: 0x2a3b9ec VA: 0x75950539ec
	private Action`1 get_onAssistItemClick() { }
	// RVA: 0x2a3a03c VA: 0x759505203c
	public Void set_onAssistItemClick(Action`1 value) { }
	// RVA: 0x2a3ba54 VA: 0x7595053a54
	public override Void OnValueChanged(RoguelikeFriendAssistSearchProperty property) { }
	// RVA: 0x2a3bb34 VA: 0x7595053b34
	private Void _InitIfNot() { }
	// RVA: 0x2a3bd80 VA: 0x7595053d80
	public Void .ctor() { }
}
```