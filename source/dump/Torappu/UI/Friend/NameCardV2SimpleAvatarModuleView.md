# NameCardV2SimpleAvatarModuleView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Text _doctorLevel`

- `Text _doctorName`

- `Text _doctorUid`

- `Transform _avatarContainer`

- `Single _avatarScale`

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

- `Void ExtendNameCard()`

- `Void <>xLuaBaseProxy_OnApplyStyle(NameCardV2SkinStyle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2SimpleAvatarModuleView : NameCardV2BaseFixedModuleView`1
{
	private const String DOCTOR_NAME_FORMAT; // 0x0
	private Text _doctorLevel; // 0x50
	private Text _doctorName; // 0x58
	private Text _doctorUid; // 0x60
	private Transform _avatarContainer; // 0x68
	private Single _avatarScale; // 0x70
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
	private static DelegateBridge __Hotfix0_ExtendNameCard; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x28e77d8 VA: 0x7594eff7d8
	public override Void OnModuleViewRendered(NameCardV2AvatarModuleModel model) { }
	// RVA: 0x28e7c1c VA: 0x7594effc1c
	protected override Void OnApplyStyle(NameCardV2SkinStyle style) { }
	// RVA: 0x28e7a90 VA: 0x7594effa90
	private Void _InitIfNot() { }
	// RVA: 0x28e7c9c VA: 0x7594effc9c
	public Void OpenAvatarPage() { }
	// RVA: 0x28e7d4c VA: 0x7594effd4c
	public Void CopyUid() { }
	// RVA: 0x28e7e2c VA: 0x7594effe2c
	public Void CrossAppShare() { }
	// RVA: 0x28e7f74 VA: 0x7594efff74
	public Void ExtendNameCard() { }
	// RVA: 0x28e80e4 VA: 0x7594f000e4
	public Void .ctor() { }
	// RVA: 0x28e8174 VA: 0x7594f00174
	private Void <>xLuaBaseProxy_OnApplyStyle(NameCardV2SkinStyle P0) { }
}
```