# BossRushSquadTabView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `TwoStateToggle _toggle`

- `Text _name`

- `Text _nameUnselected`

- `Image _imgSelect`

- `Image _imgUnselect`

- `Sprite _spriteTeamSelect`

- `Sprite _spriteTeamUnselect`

- `Sprite _spriteFreeTeamSelect`

- `Sprite _spriteFreeTeamUnselect`

- `GameObject _objFreeTeamDec`

- `Int32 m_indexCache`


## Methods

- `Void Render(Int32, String, Boolean, Boolean)`

- `Void EventOnTabClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushSquadTabView : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _toggle; // 0x18
	private Text _name; // 0x20
	private Text _nameUnselected; // 0x28
	private Image _imgSelect; // 0x30
	private Image _imgUnselect; // 0x38
	private Sprite _spriteTeamSelect; // 0x40
	private Sprite _spriteTeamUnselect; // 0x48
	private Sprite _spriteFreeTeamSelect; // 0x50
	private Sprite _spriteFreeTeamUnselect; // 0x58
	private GameObject _objFreeTeamDec; // 0x60
	private Int32 m_indexCache; // 0x68
	public Action`1 onTabClick; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnTabClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2e630a4 VA: 0x759547b0a4
	public Void Render(Int32 index, String name, Boolean isSelected, Boolean isFreeTeam) { }
	// RVA: 0x2e6e738 VA: 0x7595486738
	public Void EventOnTabClick() { }
	// RVA: 0x2e6e7c0 VA: 0x75954867c0
	public Void .ctor() { }
}
```