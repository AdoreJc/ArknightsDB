# NameCardV2AvatarModuleView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Text _doctorLevel`

- `Text _doctorName`

- `Text _doctorUid`

- `Image _bgImg`

- `Transform _avatarContainer`

- `Button _avatarModifyBtn`

- `UIColorGraphic _avatarColorGraphic`

- `Button _copyUidBtn`

- `GameObject _crossAppShareBtn`

- `CrossAppShareStartDynAssetContent _avatarContent`

- `Boolean m_hasInited`

- `PlayerAvatarView m_avatarView`

- `String m_cachedNameCardSkinId`

- `Int32 m_cachedNameCardSkinTmpl`

- `Boolean m_isSelfAvatar`


## Methods

- `Void _InitIfNot()`

- `Void OpenAvatarPage()`

- `Void CopyUid()`

- `Void CrossAppShare()`

- `Void <>xLuaBaseProxy_OnApplyStyle(NameCardV2SkinStyle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2AvatarModuleView : NameCardV2BaseFixedModuleView`1
{
	private const String DOCTOR_NAME_FORMAT; // 0x0
	private Text _doctorLevel; // 0x50
	private Text _doctorName; // 0x58
	private Text _doctorUid; // 0x60
	private Image _bgImg; // 0x68
	private Transform _avatarContainer; // 0x70
	private Button _avatarModifyBtn; // 0x78
	private UIColorGraphic _avatarColorGraphic; // 0x80
	private Button _copyUidBtn; // 0x88
	private GameObject _crossAppShareBtn; // 0x90
	private CrossAppShareStartDynAssetContent _avatarContent; // 0x98
	private Boolean m_hasInited; // 0xa0
	private PlayerAvatarView m_avatarView; // 0xa8
	private String m_cachedNameCardSkinId; // 0xb0
	private Int32 m_cachedNameCardSkinTmpl; // 0xb8
	private Boolean m_isSelfAvatar; // 0xbc
	private static DelegateBridge __Hotfix0_OnModuleViewRendered; // 0x0
	private static DelegateBridge __Hotfix0_OnApplyStyle; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OpenAvatarPage; // 0x18
	private static DelegateBridge __Hotfix0_CopyUid; // 0x20
	private static DelegateBridge __Hotfix0_CrossAppShare; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x28e03a8 VA: 0x7594ef83a8
	public override Void OnModuleViewRendered(NameCardV2AvatarModuleModel model) { }
	// RVA: 0x28e077c VA: 0x7594ef877c
	protected override Void OnApplyStyle(NameCardV2SkinStyle style) { }
	// RVA: 0x28e0618 VA: 0x7594ef8618
	private Void _InitIfNot() { }
	// RVA: 0x28e0824 VA: 0x7594ef8824
	public Void OpenAvatarPage() { }
	// RVA: 0x28e08d4 VA: 0x7594ef88d4
	public Void CopyUid() { }
	// RVA: 0x28e09b4 VA: 0x7594ef89b4
	public Void CrossAppShare() { }
	// RVA: 0x28e0afc VA: 0x7594ef8afc
	public Void .ctor() { }
	// RVA: 0x28e0b8c VA: 0x7594ef8b8c
	private Void <>xLuaBaseProxy_OnApplyStyle(NameCardV2SkinStyle P0) { }
}
```