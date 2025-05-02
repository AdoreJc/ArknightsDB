# FriendAssistSkillItem

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Image _skillIcon`

- `GameObject _iconPanel`

- `GameObject _slectedPanel`

- `GameObject _noneSkillPanel`

- `GameObject _lockSkillPanel`

- `GameObject _detailPanel`

- `GameObject _levelPanel`

- `Text _textName`

- `Text _textLevel`

- `Image _levelBg`

- `Image _skillSpecializedLevelIcon`

- `GameObject _skillLevelPanel`

- `GameObject _skillSpecializedLevelPanel`

- `GameObject _hotspot`

- `Color _normalSkillBgColor`

- `Color _limitSkillBgColor`

- `Single _unselectAlpha`

- `String m_cachedSkillId`


## Methods

- `Void Render(PlayerCharSkill, Int32, RenderOptions)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendAssistSkillItem : MonoBehaviour, IHotfixable
{
	private Image _skillIcon; // 0x18
	private GameObject _iconPanel; // 0x20
	private GameObject _slectedPanel; // 0x28
	private GameObject _noneSkillPanel; // 0x30
	private GameObject _lockSkillPanel; // 0x38
	private GameObject _detailPanel; // 0x40
	private GameObject _levelPanel; // 0x48
	private Text _textName; // 0x50
	private Text _textLevel; // 0x58
	private Image _levelBg; // 0x60
	private Image _skillSpecializedLevelIcon; // 0x68
	private GameObject _skillLevelPanel; // 0x70
	private GameObject _skillSpecializedLevelPanel; // 0x78
	private GameObject _hotspot; // 0x80
	private Color _normalSkillBgColor; // 0x88
	private Color _limitSkillBgColor; // 0x98
	private Single _unselectAlpha; // 0xa8
	public Action`2 onItemClicked; // 0xb0
	private String m_cachedSkillId; // 0xb8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x28c9bc4 VA: 0x7594ee1bc4
	public Void Render(PlayerCharSkill charSkill, Int32 mainSkillLvl, RenderOptions options) { }
	// RVA: 0x28c9ee0 VA: 0x7594ee1ee0
	public Void OnClick() { }
	// RVA: 0x28c9f6c VA: 0x7594ee1f6c
	public Void .ctor() { }
}
```