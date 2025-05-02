# FriendListItem

**Namespace:** `Torappu.UI.Friend`


## Fields

- `FriendListState state`

- `Text _friendName`

- `Text _awayTime`

- `Text _friendLvl`

- `Text _aliasName`

- `TwoStateToggle _onlineState`

- `UIRenderTextureImage _backImage`

- `Shader _blurShader`

- `GameObject _buttonContainer`

- `GameObject _buttonContainerDown`

- `GameObject _iconVisited`

- `CanvasGroup _canvasGroup`

- `InfoShareWidget _infoShareWidget`

- `Transform _avatarContainer`

- `Single _avatarViewScale`

- `Image _background`

- `FriendListView parentView`

- `Int32 index`

- `FriendData m_friendData`

- `String m_cachedUid`

- `GetOtherPlayerNameCardResponse m_cachedResponse`

- `String m_alias`

- `Vector3 _parentViewPos`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Start()`

- `Void OpenBuilding()`

- `Void OnOpenShow()`

- `Void OnHideView(Int32)`

- `Void OnDetailClick()`

- `Void OnCloseDetail()`

- `Void OnNameCardClick()`

- `Void _OpenFriendNameCard(GetOtherPlayerNameCardResponse)`

- `Void OnDeleteFriend()`

- `Void OnSetAlias()`

- `Void ApplyData(FriendData, Vector3, String)`

- `IEnumerator UpdateLayout(Vector3)`

- `Void ApplyData(FriendData, String)`

- `Void ApplyData(SquadFriendData, String)`

- `Void _ApplyAvatar(FriendCommonData)`

- `Void <OnNameCardClick>b__35_0(GetOtherPlayerNameCardResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendListItem : UIStylerApplier`1, IHotfixable
{
	private const String FRIEND_NAME_FORMAT; // 0x0
	public FriendListState state; // 0x20
	private FriendSharedCharHeadIcon[] _charList; // 0x28
	private GameObject[] _emptyList; // 0x30
	private Text _friendName; // 0x38
	private Text _awayTime; // 0x40
	private Text _friendLvl; // 0x48
	private Text _aliasName; // 0x50
	private TwoStateToggle _onlineState; // 0x58
	private UIRenderTextureImage _backImage; // 0x60
	private Shader _blurShader; // 0x68
	private GameObject _buttonContainer; // 0x70
	private GameObject _buttonContainerDown; // 0x78
	private GameObject _iconVisited; // 0x80
	private CanvasGroup _canvasGroup; // 0x88
	private InfoShareWidget _infoShareWidget; // 0x90
	private Transform _avatarContainer; // 0x98
	private Single _avatarViewScale; // 0xa0
	private Image _background; // 0xa8
	public FriendListView parentView; // 0xb0
	public Int32 index; // 0xb8
	protected FriendData m_friendData; // 0xc0
	protected String m_cachedUid; // 0xc8
	protected GetOtherPlayerNameCardResponse m_cachedResponse; // 0xd0
	protected String m_alias; // 0xd8
	private Vector3 _parentViewPos; // 0xe0
	private const Single UPDOWNTHERSOLD; // 0x0
	private UIPageFinder m_pageFinder; // 0xf0
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge __Hotfix0_OpenBuilding; // 0x8
	private static DelegateBridge __Hotfix0_OnOpenShow; // 0x10
	private static DelegateBridge __Hotfix0_OnHideView; // 0x18
	private static DelegateBridge __Hotfix0_OnDetailClick; // 0x20
	private static DelegateBridge __Hotfix0_OnCloseDetail; // 0x28
	private static DelegateBridge __Hotfix0_OnNameCardClick; // 0x30
	private static DelegateBridge __Hotfix0__OpenFriendNameCard; // 0x38
	private static DelegateBridge __Hotfix0_OnDeleteFriend; // 0x40
	private static DelegateBridge __Hotfix0_OnSetAlias; // 0x48
	private static DelegateBridge __Hotfix0_ApplyData; // 0x50
	private static DelegateBridge __Hotfix0_UpdateLayout; // 0x58
	private static DelegateBridge __Hotfix1_ApplyData; // 0x60
	private static DelegateBridge __Hotfix2_ApplyData; // 0x68
	private static DelegateBridge __Hotfix0__ApplyAvatar; // 0x70
	private static DelegateBridge __Hotfix0_OnApplyStyle; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x28cc184 VA: 0x7594ee4184
	private Void Start() { }
	// RVA: 0x28cc2c0 VA: 0x7594ee42c0
	public Void OpenBuilding() { }
	// RVA: 0x28cc4dc VA: 0x7594ee44dc
	public Void OnOpenShow() { }
	// RVA: 0x28cc554 VA: 0x7594ee4554
	public Void OnHideView(Int32 focusIndex) { }
	// RVA: 0x28cc62c VA: 0x7594ee462c
	public Void OnDetailClick() { }
	// RVA: 0x28cc9e0 VA: 0x7594ee49e0
	public Void OnCloseDetail() { }
	// RVA: 0x28ccaa4 VA: 0x7594ee4aa4
	public Void OnNameCardClick() { }
	// RVA: 0x28cccd4 VA: 0x7594ee4cd4
	private Void _OpenFriendNameCard(GetOtherPlayerNameCardResponse response) { }
	// RVA: 0x28ccde8 VA: 0x7594ee4de8
	public Void OnDeleteFriend() { }
	// RVA: 0x28cce70 VA: 0x7594ee4e70
	public Void OnSetAlias() { }
	// RVA: 0x28ccefc VA: 0x7594ee4efc
	public Void ApplyData(FriendData data, Vector3 parentViewPos, String alias) { }
	// RVA: 0x28cc828 VA: 0x7594ee4828
	private IEnumerator UpdateLayout(Vector3 parentViewPos) { }
	// RVA: 0x28cd000 VA: 0x7594ee5000
	public Void ApplyData(FriendData data, String alias) { }
	// RVA: 0x28cda8c VA: 0x7594ee5a8c
	public Void ApplyData(SquadFriendData data, String alias) { }
	// RVA: 0x28cd8fc VA: 0x7594ee58fc
	private Void _ApplyAvatar(FriendCommonData data) { }
	// RVA: 0x28cdc30 VA: 0x7594ee5c30
	protected override Void OnApplyStyle(NameCardV2SkinStyle style) { }
	// RVA: 0x28cdd1c VA: 0x7594ee5d1c
	public Void .ctor() { }
	// RVA: 0x28cddb8 VA: 0x7594ee5db8
	private Void <OnNameCardClick>b__35_0(GetOtherPlayerNameCardResponse response) { }
}
```