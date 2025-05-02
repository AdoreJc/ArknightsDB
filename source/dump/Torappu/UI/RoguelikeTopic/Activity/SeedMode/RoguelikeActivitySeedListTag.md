# RoguelikeActivitySeedListTag

**Namespace:** `Torappu.UI.RoguelikeTopic.Activity.SeedMode`


## Fields

- `GameObject _selectObj`

- `SeedItemType _tagType`

- `Text _nameText`

- `Color _selectColor`

- `Color _unselectColor`


## Properties

- `SeedItemType tagType`


## Methods

- `SeedItemType get_tagType()`

- `Void Render(Boolean)`

- `Void OnClickSwitchTag()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Activity.SeedMode
public class RoguelikeActivitySeedListTag : MonoBehaviour, IHotfixable
{
	private GameObject _selectObj; // 0x18
	private SeedItemType _tagType; // 0x20
	private Text _nameText; // 0x28
	private Color _selectColor; // 0x30
	private Color _unselectColor; // 0x40
	public Action`1 onClickSwitchTag; // 0x50
	private static DelegateBridge __Hotfix0_get_tagType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnClickSwitchTag; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public SeedItemType tagType { get; }

	// RVA: 0x26e35dc VA: 0x7594cfb5dc
	public SeedItemType get_tagType() { }
	// RVA: 0x26e3644 VA: 0x7594cfb644
	public Void Render(Boolean isSelected) { }
	// RVA: 0x26e3720 VA: 0x7594cfb720
	public Void OnClickSwitchTag() { }
	// RVA: 0x26e37a8 VA: 0x7594cfb7a8
	public Void .ctor() { }
}
```