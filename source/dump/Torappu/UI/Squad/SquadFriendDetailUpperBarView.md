# SquadFriendDetailUpperBarView

**Namespace:** `Torappu.UI.Squad`


## Fields

- `RectTransform _avatarTransform`

- `UIColorGraphic _avatarColorGraphic`

- `Single _avatarScale`

- `Text _levelNumText`

- `Text _nameText`

- `Text _aliasNameText`

- `TwoStateToggle _onlineState`

- `Text _loginTimeText`

- `TwoStateToggle _requestFriendToggle`

- `FriendSharedCharHeadIcon _charViewPrefab`

- `Image _nameCardLongBg`

- `PlayerAvatarView m_avatarView`

- `SquadAssistData m_cacheData`

- `Boolean m_inited`

- `UIStateFinder m_stateFinder`

- `String m_cachedUid`


## Methods

- `Void Render(SquadAssistCharDetailModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadFriendDetailUpperBarView : UIStylerApplier`1, IHotfixable
{
	private RectTransform _avatarTransform; // 0x20
	private UIColorGraphic _avatarColorGraphic; // 0x28
	private Single _avatarScale; // 0x30
	private Text _levelNumText; // 0x38
	private Text _nameText; // 0x40
	private Text _aliasNameText; // 0x48
	private TwoStateToggle _onlineState; // 0x50
	private Text _loginTimeText; // 0x58
	private TwoStateToggle _requestFriendToggle; // 0x60
	private GameObject[] _hideObjectsWhenIsFriend; // 0x68
	private RectTransform[] _charViewContainerList; // 0x70
	private FriendSharedCharHeadIcon _charViewPrefab; // 0x78
	private Image _nameCardLongBg; // 0x80
	private PlayerAvatarView m_avatarView; // 0x88
	private SquadAssistData m_cacheData; // 0x90
	private Boolean m_inited; // 0x98
	private UIStateFinder m_stateFinder; // 0xa0
	private String m_cachedUid; // 0xb0
	private List`1 m_createdCharViews; // 0xb8
	private static DelegateBridge __Hotfix0_OnApplyStyle; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x23c72bc VA: 0x75949df2bc
	protected override Void OnApplyStyle(NameCardV2SkinStyle style) { }
	// RVA: 0x23c73a4 VA: 0x75949df3a4
	public Void Render(SquadAssistCharDetailModel model) { }
	// RVA: 0x23c769c VA: 0x75949df69c
	private Void _InitIfNot() { }
	// RVA: 0x23c7904 VA: 0x75949df904
	public Void .ctor() { }
}
```