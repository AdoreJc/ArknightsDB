# Act20sideCarVotePlayerDetailView

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `UIBlurFloatPanel _fullScreenImg`

- `RectTransform _avatarTransform`

- `Single _avatarScale`

- `Text _levelNumText`

- `Text _nameText`

- `TwoStateToggle _onlineState`

- `Text _loginTimeText`

- `TwoStateToggle _requestFriendToggle`

- `SquadFriendCharView _charViewPrefab`

- `UIStringEvent _onFriendRequestSucEvent`

- `PlayerAvatarView m_avatarView`

- `ExhibitionFriendCard m_cacheData`

- `Boolean m_inited`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void _InitIfNot()`

- `Void Render(ExhibitionFriendCard, Boolean)`

- `Void _SendFriendProcessRequestListRequest(ExhibitionFriendCard)`

- `Void _OnSendFriendReqSuc()`

- `Void OnAlreadyRequestClick()`

- `Void OnFriendRequestClick()`

- `Void Dismiss()`

- `Void <_SendFriendProcessRequestListRequest>b__18_0(SendFriendResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCarVotePlayerDetailView : MonoBehaviour, IHotfixable
{
	private UIBlurFloatPanel _fullScreenImg; // 0x18
	private RectTransform _avatarTransform; // 0x20
	private Single _avatarScale; // 0x28
	private Text _levelNumText; // 0x30
	private Text _nameText; // 0x38
	private TwoStateToggle _onlineState; // 0x40
	private Text _loginTimeText; // 0x48
	private TwoStateToggle _requestFriendToggle; // 0x50
	private RectTransform[] _charViewContainerList; // 0x58
	private SquadFriendCharView _charViewPrefab; // 0x60
	private UIStringEvent _onFriendRequestSucEvent; // 0x68
	private PlayerAvatarView m_avatarView; // 0x70
	private ExhibitionFriendCard m_cacheData; // 0x78
	private Boolean m_inited; // 0x80
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__SendFriendProcessRequestListRequest; // 0x18
	private static DelegateBridge __Hotfix0__OnSendFriendReqSuc; // 0x20
	private static DelegateBridge __Hotfix0_OnAlreadyRequestClick; // 0x28
	private static DelegateBridge __Hotfix0_OnFriendRequestClick; // 0x30
	private static DelegateBridge __Hotfix0_Dismiss; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Boolean isShow { get; }

	// RVA: 0x32f4d50 VA: 0x759590cd50
	public Boolean get_isShow() { }
	// RVA: 0x32fd584 VA: 0x7595915584
	private Void _InitIfNot() { }
	// RVA: 0x32f594c VA: 0x759590d94c
	public Void Render(ExhibitionFriendCard friendCard, Boolean canRequest) { }
	// RVA: 0x32fd72c VA: 0x759591572c
	private Void _SendFriendProcessRequestListRequest(ExhibitionFriendCard friendData) { }
	// RVA: 0x32fd914 VA: 0x7595915914
	private Void _OnSendFriendReqSuc() { }
	// RVA: 0x32fda04 VA: 0x7595915a04
	public Void OnAlreadyRequestClick() { }
	// RVA: 0x32fdab8 VA: 0x7595915ab8
	public Void OnFriendRequestClick() { }
	// RVA: 0x32f4dc4 VA: 0x759590cdc4
	public Void Dismiss() { }
	// RVA: 0x32fdb3c VA: 0x7595915b3c
	public Void .ctor() { }
	// RVA: 0x32fdbb8 VA: 0x7595915bb8
	private Void <_SendFriendProcessRequestListRequest>b__18_0(SendFriendResponse response) { }
}
```