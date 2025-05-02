# CharacterInfoSelectSkillView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterInfoSkillView _skillView`

- `GameObject _onSelected`

- `GameObject _onNotSelected`

- `Int32 m_indexCache`


## Methods

- `Void EventOnToggleButtonClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoSelectSkillView : MonoBehaviour
{
	protected CharacterInfoSkillView _skillView; // 0x18
	private GameObject _onSelected; // 0x20
	private GameObject _onNotSelected; // 0x28
	protected Int32 m_indexCache; // 0x30
	public Action`1 onToggleClick; // 0x38


	// RVA: 0x2d88d0c VA: 0x75953a0d0c
	public virtual Void Render(SkillItemViewModel viewModel, Int32 index, Boolean isSelected) { }
	// RVA: 0x2d88da0 VA: 0x75953a0da0
	public Void EventOnToggleButtonClick() { }
	// RVA: 0x2d88dc0 VA: 0x75953a0dc0
	public Void .ctor() { }
}
```