# SquadFriendCharView

**Namespace:** `Torappu.UI.Squad`


## Fields

- `GameObject _emptyViewObject`

- `GameObject _charViewObject`

- `Image _charImg`

- `Text _levelText`

- `Image _eliteImg`

- `Image _skillImg`

- `GameObject _skillObject`

- `Text _skillLevelText`

- `Image _skillSpecializedImg`

- `Image _skillLevelBg`

- `Color _normalSkillBgColor`

- `Color _limitSkillBgColor`

- `GameObject _emptySkillObject`

- `UICommonEquipTypeIcon _equipIconPrefab`

- `Transform _equipIconContainer`

- `Single _equipIconScale`

- `GameObject _panelEquip`

- `GameObject _panelEquipLevel`

- `Text _equipLevelText`

- `GameObject _emptyEquipObject`

- `UICommonEquipTypeIcon m_equipIcon`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(SharedCharData, Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadFriendCharView : MonoBehaviour, IHotfixable
{
	private GameObject _emptyViewObject; // 0x18
	private GameObject _charViewObject; // 0x20
	private Image _charImg; // 0x28
	private Text _levelText; // 0x30
	private Image _eliteImg; // 0x38
	private Image _skillImg; // 0x40
	private GameObject _skillObject; // 0x48
	private Text _skillLevelText; // 0x50
	private Image _skillSpecializedImg; // 0x58
	private Image _skillLevelBg; // 0x60
	private Color _normalSkillBgColor; // 0x68
	private Color _limitSkillBgColor; // 0x78
	private GameObject _emptySkillObject; // 0x88
	private UICommonEquipTypeIcon _equipIconPrefab; // 0x90
	private Transform _equipIconContainer; // 0x98
	private Single _equipIconScale; // 0xa0
	private GameObject _panelEquip; // 0xa8
	private GameObject _panelEquipLevel; // 0xb0
	private Text _equipLevelText; // 0xb8
	private GameObject _emptyEquipObject; // 0xc0
	private UICommonEquipTypeIcon m_equipIcon; // 0xc8
	private Boolean m_isInited; // 0xd0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x23c5fe0 VA: 0x75949ddfe0
	private Void _InitIfNot() { }
	// RVA: 0x23c6144 VA: 0x75949de144
	public Void Render(SharedCharData charData, Boolean isSelect, Boolean isSkillLimited) { }
	// RVA: 0x23c666c VA: 0x75949de66c
	public Void .ctor() { }
}
```