# CharacterInfoRightSkillSpreadItem

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterInfoSkillIconView _skillView`

- `UIColorGraphic _alphaGroup`

- `GameObject _onSelected`

- `SkillItemViewModel m_cacheViewModel`


## Methods

- `Void Render(SkillItemViewModel, Int32, Boolean, Boolean)`

- `Void EventOnToggleButtonClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoRightSkillSpreadItem : MonoBehaviour, IHotfixable
{
	protected CharacterInfoSkillIconView _skillView; // 0x18
	private UIColorGraphic _alphaGroup; // 0x20
	private GameObject _onSelected; // 0x28
	protected SkillItemViewModel m_cacheViewModel; // 0x30
	public Action`1 onToggleClick; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnToggleButtonClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d87564 VA: 0x759539f564
	public Void Render(SkillItemViewModel viewModel, Int32 index, Boolean isSelected, Boolean cacheSelect) { }
	// RVA: 0x2d87658 VA: 0x759539f658
	public Void EventOnToggleButtonClick() { }
	// RVA: 0x2d876ec VA: 0x759539f6ec
	public Void .ctor() { }
}
```