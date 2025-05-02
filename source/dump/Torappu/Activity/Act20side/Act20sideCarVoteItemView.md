# Act20sideCarVoteItemView

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `GameObject _panelFriendInfo`

- `Transform _avatarContainer`

- `Single _avatarViewScale`

- `Text _levelNum`

- `Text _name`

- `Text _nickName`

- `GameObject _panelName`

- `Text _note`

- `GameObject _panelNote`

- `Button _btnRequest`

- `GameObject _panelRequest`

- `GameObject _panelLevel`

- `UIAtlasImage _npcAvatar`

- `GameObject _panelChoose`

- `GameObject _panelVote`

- `UIAtlasImage _iconNew`

- `Act20sideCarObject _carPrefab`

- `Transform _carContainer`

- `Single _carViewScale`

- `UIAnimationLocation _showAnim`

- `UIIntEvent _onClickEvent`

- `UIIntEvent _onFriendRequestEvent`

- `UIIntEvent _onCarDetailEvent`

- `CarVoteBtnSwitchTween m_switchTween`

- `Boolean m_isInited`

- `Int32 m_cachedIndex`

- `Act20sideCarObject m_carView`

- `PlayerAvatarView m_avatarView`


## Methods

- `Void _InitIfNot()`

- `Void Render(VoteCarViewModel, Int32, Boolean)`

- `Void OnClick()`

- `Void OnFriendRequestClick()`

- `Void OnCarDetailClick()`

- `Void _ApplyAvatar(AvatarInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCarVoteItemView : MonoBehaviour, IHotfixable
{
	private const Single SHOW_ANIM_DURATION; // 0x0
	private GameObject _panelFriendInfo; // 0x18
	private Transform _avatarContainer; // 0x20
	private Single _avatarViewScale; // 0x28
	private Text _levelNum; // 0x30
	private Text _name; // 0x38
	private Text _nickName; // 0x40
	private GameObject _panelName; // 0x48
	private Text _note; // 0x50
	private GameObject _panelNote; // 0x58
	private Button _btnRequest; // 0x60
	private GameObject _panelRequest; // 0x68
	private GameObject _panelLevel; // 0x70
	private UIAtlasImage _npcAvatar; // 0x78
	private GameObject _panelChoose; // 0x80
	private GameObject _panelVote; // 0x88
	private UIAtlasImage _iconNew; // 0x90
	private Act20sideCarObject _carPrefab; // 0x98
	private Transform _carContainer; // 0xa0
	private Single _carViewScale; // 0xa8
	private UIAnimationLocation _showAnim; // 0xb0
	private UIIntEvent _onClickEvent; // 0xc0
	private UIIntEvent _onFriendRequestEvent; // 0xc8
	private UIIntEvent _onCarDetailEvent; // 0xd0
	private CarVoteBtnSwitchTween m_switchTween; // 0xd8
	private Boolean m_isInited; // 0xe0
	private Int32 m_cachedIndex; // 0xe4
	private Act20sideCarObject m_carView; // 0xe8
	private PlayerAvatarView m_avatarView; // 0xf0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge __Hotfix0_OnFriendRequestClick; // 0x18
	private static DelegateBridge __Hotfix0_OnCarDetailClick; // 0x20
	private static DelegateBridge __Hotfix0__ApplyAvatar; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x32fc7d8 VA: 0x75959147d8
	private Void _InitIfNot() { }
	// RVA: 0x32fca48 VA: 0x7595914a48
	public Void Render(VoteCarViewModel data, Int32 index, Boolean isFocused) { }
	// RVA: 0x32fcfe8 VA: 0x7595914fe8
	public Void OnClick() { }
	// RVA: 0x32fd07c VA: 0x759591507c
	public Void OnFriendRequestClick() { }
	// RVA: 0x32fd11c VA: 0x759591511c
	public Void OnCarDetailClick() { }
	// RVA: 0x32fce34 VA: 0x7595914e34
	private Void _ApplyAvatar(AvatarInfo avatarInfo) { }
	// RVA: 0x32fd1b0 VA: 0x75959151b0
	public Void .ctor() { }
}
```