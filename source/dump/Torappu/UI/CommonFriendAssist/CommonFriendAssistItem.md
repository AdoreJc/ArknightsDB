# CommonFriendAssistItem

**Namespace:** `Torappu.UI.CommonFriendAssist`


## Fields

- `UIAtlasImage _charPortrait`

- `Text _charNameText`

- `Text _charLevelText`

- `Image _eliteImg`

- `Image _potentialImg`

- `GameObject _noskillPanel`

- `GameObject _skillPanel`

- `Image _skillImg`

- `Image _skillLevelBkg`

- `Color _normalLevelColor`

- `Color _limitLevelColor`

- `Text _skillLevelText`

- `Image _skillSpecializedImg`

- `GameObject _noEquipPanel`

- `GameObject _equipPanel`

- `UICommonEquipTypeIcon _equipIconPrefab`

- `Transform _equipIconContainer`

- `Single _equipIconScale`

- `GameObject _equipLevelPanel`

- `Text _equipLevelText`

- `RectTransform _avatarContainer`

- `UIColorGraphic _avatarColorGraphic`

- `Single _avatarScale`

- `Text _friendLevelText`

- `GameObject _panelNoteObject`

- `GameObject _panelNameObject`

- `Text _aliasText`

- `Text _nickNameText`

- `Text _nickNumText`

- `Text _outlineText`

- `GameObject _requestFriendObject`

- `GameObject _requestSystemObject`

- `GameObject _lockedPanel`

- `Text _textLocked`

- `Text _textLockedExtra`

- `Image _bkgLocked`

- `Image _iconLocked`

- `UIAtlasImage _crisisV2Img`

- `Text _crisisV2Score`

- `Boolean m_isCharShowMultiSlot`

- `FriendItemModel m_cacheModel`

- `SquadAssistData m_cacheData`

- `ICtrl m_ctrl`

- `SharedCharData m_sharedChar`

- `Boolean m_locked`

- `Boolean m_inited`

- `PlayerAvatarView m_avatarView`

- `UICommonEquipTypeIcon m_equipIcon`


## Methods

- `Void Render(FriendItemModel, ICtrl)`

- `Void _InitIfNot()`

- `Void EventOnCharDetailClick()`

- `Void EventOnApplyAssist()`

- `Void EventOnFriendAvatarClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CommonFriendAssist
public class CommonFriendAssistItem : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _charPortrait; // 0x18
	private Text _charNameText; // 0x20
	private Text _charLevelText; // 0x28
	private Image _eliteImg; // 0x30
	private Image _potentialImg; // 0x38
	private GameObject _noskillPanel; // 0x40
	private GameObject _skillPanel; // 0x48
	private Image _skillImg; // 0x50
	private Image _skillLevelBkg; // 0x58
	private Color _normalLevelColor; // 0x60
	private Color _limitLevelColor; // 0x70
	private Text _skillLevelText; // 0x80
	private Image _skillSpecializedImg; // 0x88
	private GameObject _noEquipPanel; // 0x90
	private GameObject _equipPanel; // 0x98
	private UICommonEquipTypeIcon _equipIconPrefab; // 0xa0
	private Transform _equipIconContainer; // 0xa8
	private Single _equipIconScale; // 0xb0
	private GameObject _equipLevelPanel; // 0xb8
	private Text _equipLevelText; // 0xc0
	private RectTransform _avatarContainer; // 0xc8
	private UIColorGraphic _avatarColorGraphic; // 0xd0
	private Single _avatarScale; // 0xd8
	private Text _friendLevelText; // 0xe0
	private GameObject _panelNoteObject; // 0xe8
	private GameObject _panelNameObject; // 0xf0
	private Text _aliasText; // 0xf8
	private Text _nickNameText; // 0x100
	private Text _nickNumText; // 0x108
	private Text _outlineText; // 0x110
	private GameObject _requestFriendObject; // 0x118
	private GameObject _requestSystemObject; // 0x120
	private GameObject _lockedPanel; // 0x128
	private Text _textLocked; // 0x130
	private Text _textLockedExtra; // 0x138
	private Image _bkgLocked; // 0x140
	private Image _iconLocked; // 0x148
	private UIAtlasImage _crisisV2Img; // 0x150
	private Text _crisisV2Score; // 0x158
	private Boolean m_isCharShowMultiSlot; // 0x160
	private FriendItemModel m_cacheModel; // 0x168
	private SquadAssistData m_cacheData; // 0x170
	private ICtrl m_ctrl; // 0x178
	private SharedCharData m_sharedChar; // 0x180
	private Boolean m_locked; // 0x188
	private Boolean m_inited; // 0x189
	private PlayerAvatarView m_avatarView; // 0x190
	private UICommonEquipTypeIcon m_equipIcon; // 0x198
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_EventOnCharDetailClick; // 0x10
	private static DelegateBridge __Hotfix0_EventOnApplyAssist; // 0x18
	private static DelegateBridge __Hotfix0_EventOnFriendAvatarClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2c47c4c VA: 0x759525fc4c
	public Void Render(FriendItemModel model, ICtrl ctrl) { }
	// RVA: 0x2c484a0 VA: 0x75952604a0
	private Void _InitIfNot() { }
	// RVA: 0x2c486a4 VA: 0x75952606a4
	public Void EventOnCharDetailClick() { }
	// RVA: 0x2c487b0 VA: 0x75952607b0
	public Void EventOnApplyAssist() { }
	// RVA: 0x2c48898 VA: 0x7595260898
	public Void EventOnFriendAvatarClick() { }
	// RVA: 0x2c48990 VA: 0x7595260990
	public Void .ctor() { }
}
```