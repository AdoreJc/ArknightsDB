# SiracusaChatDecisionItem

**Namespace:** `Torappu.UI.SiracusaMap.Chat`


## Fields

- `Text _content`

- `Button _button`

- `Int32 m_cachedIndex`


## Methods

- `Void set_onClickedAction(Action`1)`

- `TextGenerationSettings GenerateContentSettings()`

- `Void Render(Int32, String, Boolean)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap.Chat
public class SiracusaChatDecisionItem : MonoBehaviour, IHotfixable
{
	private Text _content; // 0x18
	private Button _button; // 0x20
	private Int32 m_cachedIndex; // 0x28
	private Action`1 <onClickedAction>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_onClickedAction; // 0x0
	private static DelegateBridge __Hotfix0_set_onClickedAction; // 0x8
	private static DelegateBridge __Hotfix0_GenerateContentSettings; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onClickedAction { get; set; }

	// RVA: 0x241fe64 VA: 0x7594a37e64
	private Action`1 get_onClickedAction() { }
	// RVA: 0x241fc44 VA: 0x7594a37c44
	public Void set_onClickedAction(Action`1 value) { }
	// RVA: 0x241fd90 VA: 0x7594a37d90
	public TextGenerationSettings GenerateContentSettings() { }
	// RVA: 0x241fcc8 VA: 0x7594a37cc8
	public Void Render(Int32 index, String content, Boolean selectable) { }
	// RVA: 0x241fecc VA: 0x7594a37ecc
	public Void EventOnClicked() { }
	// RVA: 0x241ff6c VA: 0x7594a37f6c
	public Void .ctor() { }
}
```