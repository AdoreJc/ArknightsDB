# SquadFriendListItem

**Namespace:** `Torappu.UI.Squad`


## Fields

- `UIAtlasImage _charPortrait`

- `Text _charNameText`

- `Text _charLevelText`

- `GameObject _specMaxPart`

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

- `UIFriendEvent m_uiFriendEvent`

- `SquadAssistData m_cacheData`

- `SharedCharData m_sharedChar`

- `Boolean m_isFriend`

- `Boolean m_locked`

- `Boolean m_inited`

- `PlayerAvatarView m_avatarView`

- `UICommonEquipTypeIcon m_equipIcon`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(Params)`

- `Void _InitIfNot()`

- `Void OnApplyAssist()`

- `Void OnFriendAvatarClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadFriendListItem : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _charPortrait; // 0x18
	private Text _charNameText; // 0x20
	private Text _charLevelText; // 0x28
	private GameObject _specMaxPart; // 0x30
	private Image _eliteImg; // 0x38
	private Image _potentialImg; // 0x40
	private GameObject _noskillPanel; // 0x48
	private GameObject _skillPanel; // 0x50
	private Image _skillImg; // 0x58
	private Image _skillLevelBkg; // 0x60
	private Color _normalLevelColor; // 0x68
	private Color _limitLevelColor; // 0x78
	private Text _skillLevelText; // 0x88
	private Image _skillSpecializedImg; // 0x90
	private GameObject _noEquipPanel; // 0x98
	private GameObject _equipPanel; // 0xa0
	private UICommonEquipTypeIcon _equipIconPrefab; // 0xa8
	private Transform _equipIconContainer; // 0xb0
	private Single _equipIconScale; // 0xb8
	private GameObject _equipLevelPanel; // 0xc0
	private Text _equipLevelText; // 0xc8
	private RectTransform _avatarContainer; // 0xd0
	private UIColorGraphic _avatarColorGraphic; // 0xd8
	private Single _avatarScale; // 0xe0
	private Text _friendLevelText; // 0xe8
	private GameObject _panelNoteObject; // 0xf0
	private GameObject _panelNameObject; // 0xf8
	private Text _aliasText; // 0x100
	private Text _nickNameText; // 0x108
	private Text _nickNumText; // 0x110
	private Text _outlineText; // 0x118
	private GameObject _requestFriendObject; // 0x120
	private GameObject _requestSystemObject; // 0x128
	private GameObject _lockedPanel; // 0x130
	private Text _textLocked; // 0x138
	private Text _textLockedExtra; // 0x140
	private Image _bkgLocked; // 0x148
	private Image _iconLocked; // 0x150
	private UIAtlasImage _crisisV2Img; // 0x158
	private Text _crisisV2Score; // 0x160
	private UIFriendEvent m_uiFriendEvent; // 0x168
	private SquadAssistData m_cacheData; // 0x170
	private SharedCharData m_sharedChar; // 0x178
	private Boolean m_isFriend; // 0x180
	private Boolean m_locked; // 0x181
	private Boolean m_inited; // 0x182
	private PlayerAvatarView m_avatarView; // 0x188
	private UICommonEquipTypeIcon m_equipIcon; // 0x190
	private UIStateFinder m_stateFinder; // 0x198
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnApplyAssist; // 0x10
	private static DelegateBridge __Hotfix0_OnFriendAvatarClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x23c821c VA: 0x75949e021c
	public Void Render(Params param) { }
	// RVA: 0x23c8e68 VA: 0x75949e0e68
	private Void _InitIfNot() { }
	// RVA: 0x23c906c VA: 0x75949e106c
	public Void OnApplyAssist() { }
	// RVA: 0x23c910c VA: 0x75949e110c
	public Void OnFriendAvatarClick() { }
	// RVA: 0x23c9204 VA: 0x75949e1204
	public Void .ctor() { }
}
```