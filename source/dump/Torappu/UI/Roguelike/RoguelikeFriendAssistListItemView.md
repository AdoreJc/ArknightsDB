# RoguelikeFriendAssistListItemView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _avatarContainer`

- `UIColorGraphic _avatarColorGraphic`

- `Single _avatarScale`

- `UIAtlasImage _charPortrait`

- `Text _charNameText`

- `Text _charLevelText`

- `Image _potentialImg`

- `Image _eliteImg`

- `Text _friendLevelText`

- `GameObject _panelNoteObject`

- `GameObject _panelNameObject`

- `Text _aliasText`

- `Text _nickNameText`

- `Text _nickNumText`

- `Text _loginTimeText`

- `GameObject _requestFriendObject`

- `GameObject _requestSystemObject`

- `Text _textPopulation`

- `Color _colorPopulationNormal`

- `Color _colorPopulationLack`

- `GameObject _lockPartGo`

- `Button _clickBtn`

- `FriendAssistData m_assistData`

- `Boolean m_isFriend`

- `Boolean m_inited`

- `PlayerAvatarView m_avatarView`

- `Boolean m_cachePopAvailFlag`

- `UIStateFinder m_stateFinder`

- `String m_cachedUid`


## Methods

- `Void set_onItemClick(Action`1)`

- `Void Render(FriendAssistData, Int32)`

- `Void _InitIfNot()`

- `Void OnItemClick()`

- `Void OnDetailClick()`

- `Void OnFriendAvatarClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeFriendAssistListItemView : MonoBehaviour, IHotfixable
{
	private RectTransform _avatarContainer; // 0x18
	private UIColorGraphic _avatarColorGraphic; // 0x20
	private Single _avatarScale; // 0x28
	private UIAtlasImage _charPortrait; // 0x30
	private Text _charNameText; // 0x38
	private Text _charLevelText; // 0x40
	private Image _potentialImg; // 0x48
	private Image _eliteImg; // 0x50
	private Text _friendLevelText; // 0x58
	private GameObject _panelNoteObject; // 0x60
	private GameObject _panelNameObject; // 0x68
	private Text _aliasText; // 0x70
	private Text _nickNameText; // 0x78
	private Text _nickNumText; // 0x80
	private Text _loginTimeText; // 0x88
	private GameObject _requestFriendObject; // 0x90
	private GameObject _requestSystemObject; // 0x98
	private Text _textPopulation; // 0xa0
	private Color _colorPopulationNormal; // 0xa8
	private Color _colorPopulationLack; // 0xb8
	private GameObject _lockPartGo; // 0xc8
	private Button _clickBtn; // 0xd0
	private FriendAssistData m_assistData; // 0xd8
	private Boolean m_isFriend; // 0xe0
	private Boolean m_inited; // 0xe1
	private PlayerAvatarView m_avatarView; // 0xe8
	private Boolean m_cachePopAvailFlag; // 0xf0
	private UIStateFinder m_stateFinder; // 0xf8
	private String m_cachedUid; // 0x108
	private Action`1 <onItemClick>k__BackingField; // 0x110
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x20
	private static DelegateBridge __Hotfix0_OnDetailClick; // 0x28
	private static DelegateBridge __Hotfix0_OnFriendAvatarClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action`1 onItemClick { get; set; }

	// RVA: 0x2a38bd0 VA: 0x7595050bd0
	private Action`1 get_onItemClick() { }
	// RVA: 0x2a38c38 VA: 0x7595050c38
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x2a38cbc VA: 0x7595050cbc
	public Void Render(FriendAssistData friendAssistData, Int32 population) { }
	// RVA: 0x2a39278 VA: 0x7595051278
	private Void _InitIfNot() { }
	// RVA: 0x2a393c8 VA: 0x75950513c8
	public Void OnItemClick() { }
	// RVA: 0x2a39470 VA: 0x7595051470
	public Void OnDetailClick() { }
	// RVA: 0x2a39624 VA: 0x7595051624
	public Void OnFriendAvatarClick() { }
	// RVA: 0x2a39714 VA: 0x7595051714
	public Void .ctor() { }
}
```