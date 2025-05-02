# SquadFriendDetailLowerView

**Namespace:** `Torappu.UI.Squad`


## Fields

- `Image _eliteImage`

- `Text _levelText`

- `Image _potentialImage`

- `Image _rarityImage`

- `Image _professionImage`

- `Text _charNameText`

- `CharacterInfoIllustWrapper _illustWrapper`

- `SimpleLayoutContent _skillContent`

- `SimpleLayoutContent _equipContent`

- `GameObject _skillLimitObject`

- `UIWrappedScrollRect _equipScroll`

- `Boolean m_inited`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `SquadAssistCharDetailModel m_cachedDetailModel`

- `SkillAdapter m_skillAdapter`

- `EquipAdapter m_equipAdapter`

- `Int32 m_cachedSeqNum`


## Methods

- `Void Render(SquadAssistCharDetailModel)`

- `Void _InitIfNot()`

- `Void _OnEquipClicked(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadFriendDetailLowerView : MonoBehaviour, IHotfixable
{
	private Image _eliteImage; // 0x18
	private Text _levelText; // 0x20
	private Image _potentialImage; // 0x28
	private Image _rarityImage; // 0x30
	private Image _professionImage; // 0x38
	private Text _charNameText; // 0x40
	private CharacterInfoIllustWrapper _illustWrapper; // 0x48
	private SimpleLayoutContent _skillContent; // 0x50
	private SimpleLayoutContent _equipContent; // 0x58
	private GameObject _skillLimitObject; // 0x60
	private UIWrappedScrollRect _equipScroll; // 0x68
	private Boolean m_inited; // 0x70
	private UIPageFinder m_pageFinder; // 0x78
	private UIStateFinder m_stateFinder; // 0x88
	private SquadAssistCharDetailModel m_cachedDetailModel; // 0x98
	private SkillAdapter m_skillAdapter; // 0xa0
	private EquipAdapter m_equipAdapter; // 0xa8
	private Int32 m_cachedSeqNum; // 0xb0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__OnEquipClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x23c66e8 VA: 0x75949de6e8
	public Void Render(SquadAssistCharDetailModel model) { }
	// RVA: 0x23c6918 VA: 0x75949de918
	private Void _InitIfNot() { }
	// RVA: 0x23c6b64 VA: 0x75949deb64
	private Void _OnEquipClicked(String equipId) { }
	// RVA: 0x23c6c60 VA: 0x75949dec60
	public Void .ctor() { }
}
```