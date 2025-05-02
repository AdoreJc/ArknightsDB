# PlayerInfoGroup

**Namespace:** ` `


## Fields

- `Text _playerNameTxt`

- `Text _playerTitleTxt`

- `Text _playerLvTxt`

- `Image _effectImg`

- `Image _effectTinyImg`

- `Transform _avatarContainer`

- `UIAnimationLocation _readyAnim`

- `Boolean m_isInited`

- `AnimationSwitchTween m_readyAnimSwitchTween`

- `PlayerAvatarView m_avatarView`


## Methods

- `Void _InitIfNot()`

- `Void Render(ILoadAsset, PlayerViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PlayerInfoGroup : IHotfixable
{
	private Text _playerNameTxt; // 0x10
	private Text _playerTitleTxt; // 0x18
	private Text _playerLvTxt; // 0x20
	private Image _effectImg; // 0x28
	private Image _effectTinyImg; // 0x30
	private Transform _avatarContainer; // 0x38
	private UIAnimationLocation _readyAnim; // 0x40
	private Boolean m_isInited; // 0x50
	private AnimationSwitchTween m_readyAnimSwitchTween; // 0x58
	private PlayerAvatarView m_avatarView; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3164ec8 VA: 0x759577cec8
	private Void _InitIfNot() { }
	// RVA: 0x31642f4 VA: 0x759577c2f4
	public Void Render(ILoadAsset assetLoader, PlayerViewModel playerViewModel) { }
	// RVA: 0x3165024 VA: 0x759577d024
	public Void .ctor() { }
}
```