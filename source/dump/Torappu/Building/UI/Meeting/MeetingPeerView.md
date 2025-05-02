# MeetingPeerView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `Text _nameWithNumberLabel`

- `Text _levelLabel`

- `Text _commentLabel`

- `Text _lastLoginLabel`

- `Text _onlineLabel`

- `GameObject _onlinePanel`

- `GameObject _lastLoginPanel`

- `Transform _avatarContainer`

- `IPeer m_peer`

- `IMeetingSession m_session`

- `Sprite m_originIcon`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Setup(MeetingPeerConfig)`

- `Void _RenderAvatarView(MeetingPeerConfig)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class MeetingPeerView : MonoBehaviour, IHotfixable
{
	private const String PLAYER_NUMBER_COLOR; // 0x0
	private Text _nameWithNumberLabel; // 0x18
	private Text _levelLabel; // 0x20
	private Text _commentLabel; // 0x28
	private Text _lastLoginLabel; // 0x30
	private Text _onlineLabel; // 0x38
	private GameObject _onlinePanel; // 0x40
	private GameObject _lastLoginPanel; // 0x48
	private Transform _avatarContainer; // 0x50
	private IPeer m_peer; // 0x58
	private IMeetingSession m_session; // 0x60
	private Sprite m_originIcon; // 0x68
	private Boolean m_isInited; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Setup; // 0x8
	private static DelegateBridge __Hotfix0__RenderAvatarView; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3dff618 VA: 0x7596417618
	private Void _InitIfNot() { }
	// RVA: 0x3dfd6cc VA: 0x75964156cc
	public Void Setup(MeetingPeerConfig config) { }
	// RVA: 0x3dff68c VA: 0x759641768c
	private Void _RenderAvatarView(MeetingPeerConfig config) { }
	// RVA: 0x3dff89c VA: 0x759641789c
	public Void .ctor() { }
}
```