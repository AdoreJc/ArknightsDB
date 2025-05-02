# ActMultiV3PhotoSelectNameCardView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Text _titleText`

- `Text _doctorLevel`

- `Text _doctorName`

- `Text _doctorUid`

- `Image _bgImg`

- `Transform _avatarContainer`

- `GameObject _applyFriendPart`

- `GameObject _appliedFriendPart`

- `GameObject _addedFriendPart`

- `Boolean m_inited`

- `PlayerAvatarView m_avatarView`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(ActMultiV3PhotoDetailViewModel)`

- `Void OnApplyFriend()`

- `Void OnCheckNameCard()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3PhotoSelectNameCardView : UIStylerApplier`1, IHotfixable
{
	private Text _titleText; // 0x20
	private Text _doctorLevel; // 0x28
	private Text _doctorName; // 0x30
	private Text _doctorUid; // 0x38
	private Image _bgImg; // 0x40
	private Transform _avatarContainer; // 0x48
	private GameObject _applyFriendPart; // 0x50
	private GameObject _appliedFriendPart; // 0x58
	private GameObject _addedFriendPart; // 0x60
	private Boolean m_inited; // 0x68
	private PlayerAvatarView m_avatarView; // 0x70
	private UIStateFinder m_stateFinder; // 0x78
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnApplyFriend; // 0x8
	private static DelegateBridge __Hotfix0_OnCheckNameCard; // 0x10
	private static DelegateBridge __Hotfix0_OnApplyStyle; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x311c148 VA: 0x7595734148
	public Void Render(ActMultiV3PhotoDetailViewModel selectedPhoto) { }
	// RVA: 0x311c444 VA: 0x7595734444
	public Void OnApplyFriend() { }
	// RVA: 0x311c4e8 VA: 0x75957344e8
	public Void OnCheckNameCard() { }
	// RVA: 0x311c58c VA: 0x759573458c
	protected override Void OnApplyStyle(NameCardV2SkinStyle style) { }
	// RVA: 0x311c310 VA: 0x7595734310
	private Void _InitIfNot() { }
	// RVA: 0x311c62c VA: 0x759573462c
	public Void .ctor() { }
}
```